# Final Project(Customer-Conversion-Prediction)

Aim of the Project 

The goal of the Customer Conversion Prediction project is to build a machine learning model that can predict whether a client will subscribe to the insurance based on their demographic and marketing data. The project aims to help the insurance company identify the customers that are most likely to convert, so that they can be targeted via call and the cost of telephonic marketing campaigns can be reduced

1.Libraries Import and Load Dataset
We have imported requrired libraries and also loaded dataset

2.Clean Dataset
we have used functions like remove duplicates,dropped null values,missing values,check data type and removal of outlires.

3.Exploritory Data Analysis
For the good model fit and accuret prediction we've explore the data and done Univariate Analysis, Bivariate Analysis, Correlation Check. Data type check and take dummies.

3.1 Univariate Analysis
y

The class distribution in the target variable is ~89:11 indicating an imbalance dataset
age

Age
3.2 Bivariate Analysis
We've check and learn that which type of occupations have more chances to subscribe our term insurance policy. job-VS-Y

3.3 Correlation
We've checked correlation between differant variables. We can see here Duration of Call is Highly correlated to our target variable.

Corelation

4.Encoding
we have used Label and one hot encodeing for this features['job', 'marital', 'education_qual', 'call_type', 'mon', 'prev_outcome']

5.Models
We used Linear regression,Decision Tree, KNN

6.feature importance
we can see that Dur(Duration) is most important feature in dataset















































































