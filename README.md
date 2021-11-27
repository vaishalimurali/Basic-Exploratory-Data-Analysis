# Basic-Exploratory-Data-Analysis
Assignments on EDA

Name	VAISHALI M
Sub name &Slot	EDA
Assignment name and Date	Digital Assignment-1
 
 
 
1.An e-commerce company asked you to design a model to understand the purchase behaviour of their customers. Being a Data Analytics expert, discuss in detail the various types of Data Analytics that can be applied on the customer data.

There are 4 types of analytics 
1.	Descriptive Analytics
2.	Diagnostic Analytics
3.	Predictive Analytics
4.	Prescriptive Analytics

 ![image](https://user-images.githubusercontent.com/95132467/143683496-10cae50b-045b-4673-b940-60abda7b6250.png)


##Descriptive analysis:

Descriptive Analytics states What Happened
Here the ecommerce dataset for the past 2/3 months is taken into account for analysis. We assume that the data set had the number of visitors, number of logins, the time of purchase, promotions given and transactions.
By descriptive analysis we can come to know the Aggregation of past performance and summary statics of the customer data
Here we analyse what is the average sales in the past month, what are the data to be considered and neglected and what is the frequency of customers visiting the sites
 

 Sample bar chart visualisation for the customer data.
![image](https://user-images.githubusercontent.com/95132467/143683709-b7fda3f9-d634-417e-95e2-b8608ce3eebd.png)


##Diagnostic analysis:

Diagnostic Analytic states Why Did it Happen
Here we determine which factors are influencing trends. For example, in our ecommerce dataset, why was sales lower in the last month? Which promotion is fast moving, which pattern of goods are fast moving, at what time the number of visitors are high and low and if so what are the reasons.
Identify outliers- this specifies for what reasons or why it is an outlier for example if a particular customer alone buys a particular product more than 10 times
Isolate patterns and Uncover relationships.- here for ecommerce data, specific trends like if promotions are given the customers visiting will be more so what type of promotion patterns will fetch more customers is identified. Similarly correlations like promotions and sales, promotion timing and customer logging timings, cost and customer frequency are identified.

##Predictive Analytics

Predictive analytics states what is likely to happen Predictive analysis uses the data we have summarized to make logical predictions of the outcomes of events. This analysis relies on statistical modelling, which requires added technology and manpower to forecast. It is also important to understand that forecasting is only an estimate; the accuracy of predictions relies on quality and detailed data. In predicting future outcomes, predictive analytics isn’t making a judgement on whether or not an event is likely to happen, such as, “Will a new competitor join the marketplace?” but instead is describing what will happen if these conditions are met, i.e. “Based on what happened in 2016 when a disruptor joined the marketplace, our sales could decline by 20%.” The goal is determining a trend, correlation, causation or probability.
For example here we can predict the sales when promotions are given, predict which customer goods are more selling during peak hours.
Demand forecasting is one of the forecasting method which can be used to fill the goods so that there wont be problems like out of shelf for the most visited products. Even server can be kept free during the most busy hours.
Confidence intervals, T statistics, K-S statistics and P values are all part of the umbrella of predictive analytics, applied in machine learning algorithms, classification models and regression models, to name some examples.
Business applications of predictive analysis include:
•	Risk Assessment
•	Sales Forecasting
•	Using customer segmentation to determine which leads have the best chance of converting

##Prescriptive analysis:

Prescriptive analysis states how to male it happen 
Prescriptive analytics builds on predictive analytics by helping determine recommended (prescribed) actions based on desired potential (predicted) outcomes, helping organizations achieve their business objectives.
n the wider view of applying business analytics for organizational success, prescriptive analytics “delivers business value through recommendations” built on the data of results.
Here recommendations for sales improvement can be done . 

2.Take any dataset of your choice,
1.	Identify the data set type
2.	Identify the data attribute type
3.	Apply and discuss suitable mechanism for missing value treatment.
4.	Show the required code to do data analytics either in Python or R

Data set taken : 

datasets on books
![image](https://user-images.githubusercontent.com/95132467/143683727-3e4ac71e-22de-45b9-a465-7578062e9777.png)

This file contains the detailed information about the books, primarily. Detailed description for each column can be found alongside
 
1.Identify the data set type
Types
•	Numerical Dataset
•	Bivariate Dataset
•	Multivariate Dataset
•	Categorical Dataset
•	Correlation Dataset

The above taken data set is a Multivariate Dataset

2.Identify the data attribute type

Numeric values 

bookID
ratings_count
text_reviews_count

Character values 

Title
Authors
publisher
Isbn
isbn13
average_rating
Language_code
num_pages


Date values 

publication_date

3.Apply and discuss suitable mechanism for missing value treatment
 
 ![image](https://user-images.githubusercontent.com/95132467/143683761-86b5dc22-563b-42bb-aa78-98991aeb0d10.png)
 
 Here there are 4 missing values 
 
![image](https://user-images.githubusercontent.com/95132467/143683767-b231adb8-5a96-43b0-9837-09c6adcb2357.png)

![image](https://user-images.githubusercontent.com/95132467/143683779-354bae23-bc29-49a4-8001-e374f5ec2fcc.png)


 

Here we can use mean value imputation as there are only  4 values which will make more sense 

AS per summary the mean value is 3.934 and we can impute the value in all the columns 

Now let us consider the isbn column

![image](https://user-images.githubusercontent.com/95132467/143683790-4528c311-d29c-4418-a29a-85e9546f3fe0.png)

 

This column gives the unique number for the books so in order to impute this field we can choose random value imputation
 ![image](https://user-images.githubusercontent.com/95132467/143683795-f94c1c9b-9c53-475b-9655-3de14c768e1b.png)


AS we can see there are no missing values now .
For  page number we impute mode 
 
 
![image](https://user-images.githubusercontent.com/95132467/143683799-7464ba36-9c61-43c7-acfa-4f5be4bad4c2.png)

![image](https://user-images.githubusercontent.com/95132467/143683806-a3872716-48a5-44e4-9e42-55005c867d0e.png)








4.Show the required code to do data analytics either in Python or R

 ![image](https://user-images.githubusercontent.com/95132467/143683812-e3608549-338f-4aad-b510-7cc86e1ed3a7.png)

![image](https://user-images.githubusercontent.com/95132467/143683837-fcd5f4d0-e33d-4d8f-af63-bbeddfe0ef6c.png)

![image](https://user-images.githubusercontent.com/95132467/143683846-55020b27-c33f-4582-a51d-5f56c5e67e5f.png)

![image](https://user-images.githubusercontent.com/95132467/143683855-e18c668e-5c67-4dad-9d94-081e634dd456.png)

![image](https://user-images.githubusercontent.com/95132467/143683862-e49c5fbc-1e10-456a-8c50-0217b8ec67ce.png)

![image](https://user-images.githubusercontent.com/95132467/143683866-afd35596-6f3b-41a2-a95a-d781662f2426.png)

![image](https://user-images.githubusercontent.com/95132467/143683875-6ba9d282-aa8f-445d-8edc-2e9445a72734.png)

![image](https://user-images.githubusercontent.com/95132467/143683882-82fa31d5-131a-4657-8116-fdde12fd2f80.png)

![image](https://user-images.githubusercontent.com/95132467/143683889-2a477633-f09c-40c3-9bdd-9cb1921c42be.png)



 

 
 
 

 

AS the value is 0.86597 and it is positive we can conclude it is STRONG POSITIVE CORRELATION.


 
 
Regression 
 
 ![image](https://user-images.githubusercontent.com/95132467/143683907-ff875747-94fe-4055-bb3c-a38a5959456f.png)
 
 ![image](https://user-images.githubusercontent.com/95132467/143683934-8a160019-2b9a-4867-8c95-ab1e26403d03.png)

 
