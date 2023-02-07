# Machine-Learning-Projects-for-2023

# [Project 1: House Price Prediction Using Advanced Machine Learning](https://github.com/sbsahane12/Machine-Learning-Projects-for-2023.git)
This is a project I did for my masters research paper, where I build a House Price Prediction system for a House dataset.
## Install
This project requires Python 3.6 and the following libraries installed:
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)

## Models trained on: 
1. Linear Regression Algorithm 
2. Logistic Regression Algorithm 
3. Decision Tree
4. SVM
5. Naïve Bayes
6. KNN
7. K-Means Clustering
8. Random Forest

# [Project 2: Air-quality-prediction Using Advanced Machine Learning](https://github.com/sbsahane12/Machine-Learning-Projects-for-2023.git) 
As air pollution is a complex mixture of toxic components with considerable impact on humans, forecasting air pollution concentration emerges as a priority for improving life quality. So with the help of Python tools and some Machine Learning algorithms, we try to predict the air quality. 

## Aim :
### In this project we will be building an Air Quality Index Predictor with the help of Machine Learning Models and Auto ML library i.e. TPOT

## Install
This project requires Python 3.6 and the following libraries installed:
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included.


## Models trained on: 
1. Linear Regression
2. Xgboost Regressor
3. Random Forest Regressor

****And doing the Hyperameter tuning for the above****

# [Project  3: Ecom-Market-Mix-Modle Using ML](https://github.com/sbsahane12/Machine-Learning-Projects-for-2023.git) 
To build a MMM for ElecKart Ontario based ecommerce company
## Problem Statement  
### Background  - Business Understanding   
ElecKart is an e-commerce firm based out of Ontario, Canada specialising in electronic products. Over the last year, they had spent a significant amount of money on marketing. Occasionally, they had also offered big-ticket promotions (similar to the Big Billion Day). They are about to create a marketing budget for the next year, which includes spending on commercials, online campaigns, and pricing & promotion strategies. The CFO feels that the money spent over the last 12 months on marketing was not sufficiently impactful, and, that they can either cut on the budget or reallocate it optimally across marketing levers to improve the revenue response.  
## Install
This project requires Python 3.6 and the following libraries installed:
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)
## Data Understanding
You have to use the data from July 2015 to June 2016. The data consists of the following types of information:  
   
Order level data  
•	FSN ID: The unique identification of each SKU  
•	Order Date: Date on which the order was placed  
•	Order ID: The unique identification number of each order  
•	Order item ID: Suppose you order 2 different products under the same order, it generates 2 different order Item IDs under the same order ID; orders are tracked by the Order Item ID.  
•	GMV: Gross Merchandise Value or Revenue  
•	Units: Number of units of the specific product sold  
•	Order payment type: How the order was paid – prepaid or cash on delivery  
•	SLA: Number of days it typically takes to deliver the product  
•	Cust id: Unique identification of a customer  
•	Product MRP: Maximum retail price of the product  
•	Product procurement SLA: Time typically taken to procure the product Apart from this, the following information is also available:  
•	Monthly spend on various advertising channels  
•	Days when there was any special sale  
•	Monthly NPS score – this may work as a proxy to ‘voice of the customer’  
•	Stock Index of the company on a monthly basis   

## Data Preparation  
You have to create market mix models for three product subcategories  - camera accessory, home audio and gaming accessory. Also, the models have to be built at a weekly level for each of the sub-categories.  
## Models trained on: 
1. Linear Regression
2. Xgboost Regressor

# [Project 4:Telecom Churn Logistic Regression with PCA](https://github.com/sbsahane12/Machine-Learning-Projects-for-2023.git)
## Telecom Churn: Logistic Regression with PCA
With 21 predictor variables, we need to predict whether a particular customer will switch to another telecom provider or not. In telecom terminology, customer attrition is referred to as 'churn'.
## Install
This project requires Python 3.6 and the following libraries installed:
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)

## Models trained on: 
1. PCA Algorithm 
2. Logistic Regression Algorithm 

# [Project  3: Countries  Clustering  Assignment Using ML](https://github.com/sbsahane12/Machine-Learning-Projects-for-2023.git) 
## Problem Statement
HELP International is an international humanitarian NGO that is committed to fighting poverty and  providing the people of backward countries with basic amenities and relief during the time of  disasters and natural calamities
After the recent funding programmes, they have been able to raise around $ 10 million. Now the  CEO of the NGO needs to decide how to use this money strategically and effectively.
The significant issues that come while making this decision are mostly related to choosing the
countries that are in the direst need of aid.
As a Data Scientist, we need to find the countries in direst need and help CEO of HELP  International in using the fund money to reach right countries
## Problem Approach
As we have the Data of countries like child mortality rate, GDP Per Capita, Income etc. , we can
use Clustering to segregate the countries into different groups
Steps :
Data Inspection – Missing Values if any, EDA
Outlier Analysis
Data Pre-processing
Finding Optimal number of Clusters
Modelling
KMeans Clustering
Hierarchical Clustering – Single and Complete Linkages
Listing down top 5 countries in need
## Install
This project requires Python 3.6 and the following libraries installed:
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)
## Result
- From the list of poor countries we obtained, sorted the list on income, gdpp, child_mortality rate.
- Top 5 countries which are in direst need :
- Congo, Dem Rep
- Liberia
- Burundi
- Niger
- Central African Republic
- Based on Business needs, we can change the sort order to get different list

## Models trained on: Built the model using “Euclidean distance” as metric and linkage type as “Single”
- Plotted the Dendrogram for single linkage, we won’t be able to observe good clusters in single linkage
- Built the model using Complete Linkage, we could clearly observe 3 clusters formed. Used Cut_tree with n_clusters = 3 to get the labels of the clusters formed
