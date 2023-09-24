
# <div align="center">  **1. Introduction**
### <font color=' #6a6462 ' > The dataset was downloaded from the UCI Machine Learning Repository. The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. This Project was for completion of Data Science Certificate of ABES Engineering College. In this project an exploratory analysis and data preprocessing was conducted for the classification of Quality of Wine from it's features. Wine Dataset was obtained from Kaggle(https://www.kaggle.com/datasets/rajyellow46/wine-quality)
# <div align="center"> **2. The Aim of Analysis**
### <font color="gray"> This study aims to search for the elements which effects WINE QUALITY by using multiclass decision classification methods such as Confusion Matrix, Accuracy, Cross Validation, K-Fold Cross Validation, Grid Search CV using multiple Classifiers such as Logistic Regression, Support Vector Machine and Random Forest Classifier. Hyper Parameter Tuning was performed using GridSearchcv and RepeatedStratifiedKfold. The optimal parameters for each clssifier were selected and data was fitted again with the optimal parameters.
# <div align="center">  **3. General Information of the Data**

### <font color="black">Type:<font color="gray"> Two types of wines such as red wine and white wine.
    
### <font color="black">Fixed acidity:<font color="gray"> Fixed acids include tartaric, malic, citric, and succinic acids which are found in grapes (except succinic)

### <font color="gray">Acids are one of the fundamental properties of wine and contribute greatly to the taste of the wine, Acidity in food and drink tastes tart and zesty. Tasting acidity is also sometimes confused with alcohol. Wines with higher acidity feel lighter-bodied because they come across as “spritzy”. Reducing acids significantly might lead to wines tasting flat. If you prefer a wine that is richer and rounder, you enjoy slightly less acidity.

### <font color="black">Volatile acidity:<font color="gray"> These acids are to be distilled out from the wine before completing the production process. It is primarily constituted of acetic acid though other acids like lactic, formic and butyric acids might also be present. Excess of volatile acids are undesirable and lead to unpleasant flavour.

### <font color="black">Citric acid:<font color="gray"> This is one of the fixed acids which gives a wine its freshness. Usually most of it is consumed during the fermentation process and sometimes it is added separately to give the wine more freshness.

### <font color="black">Residual sugar: <font color="gray">This typically refers to the natural sugar from grapes which remains after the fermentation process stops, or is stopped.

### <font color="black">Chlorides: <font color="gray">Chloride concentration in the wine is influenced by terroir and its highest levels are found in wines coming from countries where irrigation is carried out using salty water or in areas with brackish terrains.

### <font color="black">Free sulfur dioxide:<font color="gray"> This is the part of the sulphur dioxide that when added to a wine is said to be free after the remaining part binds. Winemakers will always try to get the highest proportion of free sulphur to bind. They are also known as sulfites and too much of it is undesirable and gives a pungent odour.

### <font color="black">Total sulfur dioxide:<font color="gray"> This is the sum total of the bound and the free sulfur dioxide. This is mainly added to kill harmful bacteria and preserve quality and freshness. There are usually legal limits for sulfur levels in wines and excess of it can even kill good yeast and give out undesirable odour.

### <font color="black">Density: <font color="gray">This can be represented as a comparison of the weight of a specific volume of wine to an equivalent volume of water. It is generally used as a measure of the conversion of sugar to alcohol. 

### <font color="black">pH: <font color="gray"> Also known as the potential of hydrogen, this is a numeric scale to specify the acidity or basicity the wine. Fixed acidity contributes the most towards the pH of wines. You might know, solutions with a pH less than 7 are acidic, while solutions with a pH greater than 7 are basic. With a pH of 7, pure water is neutral. Most wines have a pH between 2.9 and 3.9 and are therefore acidic.

### <font color="black">Sulphates: <font color="gray">These are mineral salts containing sulfur. Sulphates are to wine as gluten is to food. They are a regular part of the winemaking around the world and are considered essential. They are connected to the fermentation process and affects the wine aroma and flavour. 

### <font color="black">Alcohol: <font color="gray"> It's usually measured in % vol or alcohol by volume (ABV).

### <font color="black">Quality:<font color="gray"> Wine experts graded the wine quality between 0 (very bad) and 10 (very excellent). The eventual quality score is the median of at least three evaluations made by the same wine experts.


![download](https://user-images.githubusercontent.com/82215802/176009981-c178d378-31b0-4679-92ca-6b62d04e31c5.jpeg)
## Contents present in the .ipynb file
1.  Introduction
2.  The Aim of Analysis
3.  General Information of the Data
4.  Data Exploration
5.  Checking for NULL Values 
6.  Filling of NULL values with Mean value
7.  Overview about Outliers 
     * 8.1    Median Imputation
8.  Separating Data into Training and Testing Data
9. Data Normalization
10.  LOGISTIC REGRESSION CLASSIFIER
     * 10.a  LogisticRegression
     * 10.b  Performance Measurements
     * 10.c  Identifying optimal parameters for Logistic Regression using GridSearchCV
     * 10.d  Confusion Matrix
11.  SUPPORT VECTOR MACHINE
     * 11.a  SVM
     * 11.b  Performance Measurements
     * 11.c  Identifying optimal parameters for Support Vector Machine using GridSearchCV
     * 11.d  Confusion Matrix
12.  Random Forest CLassifier
     * 12.a  RandomForestClassifier
     * 12.b  Performance Measurements
     * 12.c  Identifying optimal parameters for Random  Forest Classifier using GridSearchCV
     * 12.d  Confusion Matrix

Link to Wine Dataset used for classififcation:
[Classification on wine Data Set](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
