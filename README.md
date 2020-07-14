# Content
#Iris dataset:
#The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician, eugenicist, and biologist Ronald Fisher in his #1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis.[1] It is sometimes called Anderson's Iris data set #because Edgar Anderson collected the data to quantify the morphologic variation of Iris flowers of three related species.[2] Two of the three species were collected #in the Gaspé Peninsula "all from the same pasture, and picked on the same day and measured at the same time by the same person with the same apparatus".[3] Fisher's #paper was published in the journal, the Annals of Eugenics, creating controversy about the continued use of the Iris dataset for teaching statistical techniques #today.
#The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). Four features were measured from each #sample: the length and the width of the sepals and petals, in centimeters. Based on the combination of these four features, Fisher developed a linear discriminant #model to distinguish the species from each other. 
#(From Wikipedia, the free encyclopedia)



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

