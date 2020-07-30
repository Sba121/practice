# Content
Iris dataset:

The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician, eugenicist, and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis.[1] It is sometimes called Anderson's Iris data set because Edgar Anderson collected the data to quantify the morphologic variation of Iris flowers of three related species.[2] Two of the three species were collected in the Gaspé Peninsula "all from the same pasture, and picked on the same day and measured at the same time by the same person with the same apparatus".[3] Fisher's paper was published in the journal, the Annals of Eugenics, creating controversy about the continued use of the Iris dataset for teaching statistical techniques today.

The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). Four features were measured from each sample: the length and the width of the sepals and petals, in centimeters. Based on the combination of these four features, Fisher developed a linear discriminant model to distinguish the species from each other. 
(From Wikipedia, the free encyclopedia)



Loan prediction:

One of the most poplar practice problem powered by Analytics Vidhya. It's about solving a real life case study of Dream Housing Finance. The company deals in all home loans. They have a presence across all urban, semi-urban and rural areas. Customers first apply for a home loan after that company validates the customer's eligibility. The company wants to automate the loan eligibility process (real-time) based on customer detail provided while filling online application form.

    Loan_id  - A unique loan number assigned to each loan customers
    Loan_status - Whether a loan is paid off, in collection, new customer yet to payoff, or paid off after the collection efforts
    Principal Basic - principal loan amount at the origination
    terms - Can be weekly (7 days), biweekly, and monthly payoff schedule
    Effective_date - When the loan got originated and took effects
    Due_date - Since it’s one-time payoff schedule, each loan has one single due date
    Paidoff_time - The actual time a customer pays off the loan
    Pastdue_days - How many days a loan has been past due
    Age, education, gender - A customer’s basic demographic information



Big Mart sales:

The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store. Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales. Please note that the data may have missing values as some stores might not report all the data due to technical glitches. Hence, it will be required to treat them accordingly.

We have train (8523) and test (5681) data set, train data set has both input and output variable(s). You need to predict the sales for test data set.

    Variable : Description
    Item_Identifier : Unique product ID
    Item_Weight : Weight of product
    Item_Fat_Content : Whether the product is low fat or not
    Item_Visibility : The % of total display area of all products in a store allocated to the particular product
    Item_Type : The category to which the product belongs
    Item_MRP : Maximum Retail Price (list price) of the product
    Outlet_Identifier : Unique store ID
    Outlet_Establishment_Year : The year in which store was established
    Outlet_Size : The size of the store in terms of ground area covered
    Outlet_Location_Type : The type of city in which the store is located
    Outlet_Type : Whether the outlet is just a grocery store or some sort of supermarket
    Item_Outlet_Sales : Sales of the product in the particulat store. This is the outcome variable to be predicted.
    My approch: after reading and analyzing data it is found that:
    Item_Fat_Content has catagories ['Low Fat', 'reg', 'Regular', 'LF', 'low fat'] Corrected the misspeled catagories and converted them to
    'LF', 'low fat' => 'Low Fat' 'reg' => 'Regular'
    
(https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/)



The Boston Housing Dataset:

The Boston Housing Dataset is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA. The following describes the dataset columns:

    CRIM - per capita crime rate by town
    ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
    INDUS - proportion of non-retail business acres per town.
    CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
    NOX - nitric oxides concentration (parts per 10 million)
    RM - average number of rooms per dwelling
    AGE - proportion of owner-occupied units built prior to 1940
    DIS - weighted distances to five Boston employment centres
    RAD - index of accessibility to radial highways
    TAX - full-value property-tax rate per $10,000
    PTRATIO - pupil-teacher ratio by town
    B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
    LSTAT - % lower status of the population
    MEDV - Median value of owner-occupied homes in $1000's



Wine Quality:

The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult: [Web Link] or the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.

    Attribute Information:

    For more information, read [Cortez et al., 2009].
    Input variables (based on physicochemical tests):
    1 - fixed acidity
    2 - volatile acidity
    3 - citric acid 
    4 - residual sugar
    5 - chlorides
    6 - free sulfur dioxide
    7 - total sulfur dioxide
    8 - density
    9 - pH
    10 - sulphates
    11 - alcohol
    Output variable (based on sensory data):
    12 - quality (score between 0 and 10)
    
Relevant Papers:

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties.
In Decision Support Systems, Elsevier, 47(4):547-553, 2009. 

(From https://archive.ics.uci.edu/ml/datasets)
    
