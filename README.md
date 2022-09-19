# erdemadiguzel.github.io

GDP per Capita Prediction with Regression by Using Life Expectancy Dataset <br>
Gross Domestic Product (GDP) per Capita is an economic indicator which is calculated by the division of country's economic output per person. Higher GDP per capita is often associated with positive outcomes in a wide range of areas such as better health, more education, and even greater life satisfaction [1], in other words the related economic indicator also represents the countries' welfare levels.

On the other hand, Lifetime Expectancy is another indicator to give insights about the welfare level of the countries. Life expectancy has increased rapidly since the Age of Enlightenment. In the early 19th century, life expectancy started to increase in the early industrialized countries while it stayed low in the rest of the world. This led to a very high inequality in how health was distributed across the world. Good health in the rich countries and persistently bad health in those countries that remained poor. [2]

In the case study, there are 2 different datasets used to build a model to predict GDP per Capita. The first one is Life Expectancy Dataset [3], which includes the countries' average lifetimes, including sexual breakdowns as female and male. Second one is, countries' GDP per Capita in terms of US Dollars [4]. Case study is starting with basic Exploratory Data Analysis (EDA) and then continued with Feature Engineering and Model Selection.

Since the aim of the model is predicting GDP per Capita by using lifetime expectancy and geological locations of the countries, target variable is defined as GDP per Capita. After merging two datasets, it is realized that there are some missing values in the target variable (GDP per Capita). The missing values are imputed by K-Numbers of Neighbor (KNN) Imputer algorithm.

Linear Regression, RandomForest Regression and Extreme Gradient Boosting Regression methods have been used in grid search to define the best algorithm, combined with different number of neighbors in KNN Imputer algorithm.


References:

[1] https://www.businesscouncilab.com/work/how-well-does-gdp-per-capita-really-measure-our-well-being/ <br>
[2] Max Roser, Esteban Ortiz-Ospina and Hannah Ritchie - "Life Expectancy" https://ourworldindata.org/life-expectancy <br>
Datasets: <br>
[3] Life Expectancy Dataset: https://www.kaggle.com/datasets/amansaxena/lifeexpectancy <br>
[4] GDP per Capita Dataset: https://data.worldbank.org/indicator/NY.GDP.PCAP.CD
