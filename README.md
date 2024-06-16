# CPDTECH-TASK1
Name-Sarthak Mangal
Company- CODTECH IT SOLUTIONS
ID-CT08DS1491
Domain-Artificial Intelligence
Duration-4 weeks
Mentor- SRAVANI GOUNI
OBJECTIVE-

DATA PROCESSING
 before applying AI algorithms, data often needs to be preprocessed to
 ensure its quality and suitability for analysis. This task involves cleaning,
 transforming, and preparing raw data for AI model training

 ABOUT DATA PROCESSIONG-
 Data preprocessing is a crucial step before applying AI algorithms! Here's a basic Python program to demonstrate common data preprocessing techniques using Pandas library:

This is a simplified example, and there are many other data preprocessing techniques depending on your specific data and AI application. Some further steps you might consider include:

Encoding categorical variables: Convert categorical data (like text labels) into numerical values that machine learning algorithms can understand.
Scaling or normalization: Scale or normalize numerical features to a common range for better model performance.
Outlier handling: Identify and address outliers that may skew your data.
Remember, data preprocessing is an iterative process. You may need to explore different techniques and assess their impact on your model's performance.






OUTPUT OF CODE-







Original Data:
   col1 col2  col3
0   1.0    A   1.2
1   2.0    B   3.5
2   NaN    C   NaN
3   4.0    D   7.8

Missing Values:
col1    1
col2    0
col3    1
dtype: int64
d:\py\FIRST TASK.PY:17: FutureWarning: A value is trying to be set on a copy of a DataFrame or Series through chained assignment using an inplace method.
The behavior will change in pandas 3.0. This inplace method will never work because the intermediate object on which we are setting values always behaves as a copy. 

For example, when doing 'df[col].method(value, inplace=True)', try using 'df.method({col: value}, inplace=True)' or df[col] = df[col].method(value) instead, to perform the operation inplace on the original object.


  df['col1'].fillna(df['col1'].mean(), inplace=True)  # Fill missing values in col1 with mean

Data Types:
col1    float64
col2     object
col3    float64
dtype: object

Preprocessed Data:
   col1 col2  col3
0   1.0    A   1.2
1   2.0    B   3.5
3   4.0    D   7.8
