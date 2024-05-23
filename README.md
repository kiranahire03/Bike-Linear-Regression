# Bike-Linear-regression

## **Abstract**:

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. The client is Seoul Bike, which participates in bike share program in Seoul, South Korea. An accurate prediction of bike count is critical to the success of Seoul Bike share program. It is important to make rental bike available and accessible to the public at right time as it lessens the waiting time. Eventually providing a city with stable supply of motor bikes become a major concern. The final aim of this project is Prediction of bike count required at each hour for stable supply of rental bikes.
           The provided dataset contains the weather information which are the features (Temperature, Humidity, Wind speed, Visibility, Dew point, Solar radiation, Snowfall, Rainfall), the target is the number of bikes rented per hour and date information. The dataset presents the company's data between December the 1st of 2017 and finishes one year later.

## **1.Problem Statement**

 We have given a dataset with the Weather information in which  the independent variables  are Temperature, Humidity, Wind speed, Visibility, Dew point, Solar radiation, Snowfall, Rainfall and  the Dependent variable is the number of bikes rented per hour and date information. The goal of the project is to predict number of rental bikes required at each hour for stable supply of rental bikes.
 We have given the following information in our dataset: 
     
•	**Date** - Year-month-day

•	**Rented Bike count** - Count of bikes rented at each hour

•	**Hour** - Hour of the day

•	**Temperature** - Temperature in Celsius

•	**Humidity** - %

•	**Windspeed** - m/s

•	**Visibility** - 10m

•	**Dew point temperature** - Celsius

•	**Solar radiation** - MJ/m2

•	**Rainfall** - mm

•	**Snowfall** - cm

•	**Seasons** - Winter, Spring, Summer, Autumn

•	**Holiday** - Holiday/No holiday

•	**Functional Day** – No Func(Non Functional Hours), Fun(Functional hours)

## **2. Introduction**

We have given a dataset with the Weather information in which the independent variables are Temperature, Humidity, Wind speed, Visibility, Dew point, Solar radiation, Snowfall, Rainfall and   the Dependent variable is the number of bikes rented per hour and date information.
Our dataset has 8760 rows and 14 columns. The goal of the project is to predict number of rental bikes required at each hour for stable supply of rental bikes. which could us to get basic understanding of our dataset, finding outliers, finding correlation between the data, perform Data visualization , models implementation and finally getting conclusion.

## **3. Steps Involved**

**●	Data Summary**
After loading the dataset we performed this step to understand the data better in the dataset and creating various graphical representations to get some conclusion from it.
This step is an important method for getting a grasp on the meaning of the content of a large collection of data. It basically simplify data for better understanding of our dataset. 

**•	Data Preprocessing**
First we check for missing values thankfully there are no null values in our dataset then we rename some column name for ease of understanding. Then we break the Date column into 3 different column Year, Month and Day.


**•	Identify relationships in dataset**
Correlation matrix measures the statistical relationship between two different variables. Correlation evaluates the direction as well as strength of a relationship between continuous variables. Correlation coefficient can range from -1 to +1, which signifies strong negative to strong positive relation between the variables


**●	Encoding of categorical columns** 
We used One Hot Encoding to produce binary integers of 0 and 1 to encode our categorical features because categorical features that are in string format cannot be understood by the machine and needs to be converted to numerical format.

**●	Exploratory Data Analysis** 
After loading the dataset we performed this method by comparing our target variable that is Rented Bike Count with other independent variables. This process helped us figuring out various aspects and relationships among the target and the independent variables. It gave us a better idea of which feature behaves in which manner compared to the target variable. With the help of Exploratory data analysis we analyzed the categorical as well as numerical features in the dataset.

## **●	Models implemented**
1.	**Linear Regression** - Linear Regression is a machine learning algorithm based on supervised learning. It performs a regression task. Regression models a target prediction value based on independent variables. It is mostly used for finding out the relationship between variables and forecasting.
2.	**Lasso Regression** - Lasso Regression is an extension of linear regression that adds a regularization penalty to the loss function during training.


## **•	Conclusion**
1.	Starting with loading the data so far we have done EDA , null values treatment, encoding of categorical columns, Outliers detection and removing and then model building.
2.	In Linear Regression R2 score value is 0.77 that means our model is able to capture most of the data variance.
