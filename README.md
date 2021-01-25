# Selecting-Seaborn-Plot
Univariate Distribution Analysis distplot()is the best place to start for 
this analysis rugplot() and kdeplot()can be useful alternatives

RegressionAnalysis
lmplot()performs regression analysis and supports faceing

Categorical Plots Explore data with the categorical plot sand facet with

pairplot()andjointplot()
Perform regression analysis with lmplot() Analyze distributions with distplot

# Clear out the pandas histogram
plt.clf()

import matplotlib.pyplot as plt
import pandas as pd

df = pd.read_csv("wines.csv")
fig, ax = plt.subplots()
ax.hist(df['alcohol'])

By default,generates a Gaussian Kernel Density Estimate(KDE)
import seaborn as sns
sns.distplot(df['alcohol'])
