# Police-Dataset
![image](https://user-images.githubusercontent.com/102817921/181227580-d98bf0c3-6fa2-4915-8b45-458da5cd5057.png)

Dataset File - https://drive.google.com/file/d/17j5y...

Project Description:
In this Project, we will learn how to work on a real project of Data Analysis with Python. Questions are given in the project and then solved with the help of Python. It is a project of Data Analysis with Python or you can say, Data Science with Python.

Q. 1) Instruction ( For Data Cleaning ) - Remove the column that only contains missing values.
Q. 2) Question ( Based on Filtering + Value Counts ) - For Speeding , were Men or Women stopped more often ? 
Q. 3) Question ( Groupby ) - Does gender affect who gets searched during a stop ?
Question ( mapping + data-type casting )
Q. 4) Question ( mapping + data-type casting ) - What is the mean stop_duration ?
Q. 5) Question ( Groupby , Describe ) - Compare the age distributions for each violation.

commands that we used in this project :

* import pandas as pd -- To import Pandas library
* pd.read_csv - To import the CSV file in Jupyter notebook
* head() - It shows the first N rows in the data (by default, N=5)
* df.isnull( ).sum( ) - It detects the missing values from each column of the dataframe.
* df.drop(‘Col_name’ )   - To drop a column from dataframe.
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
* df.groupby(‘Col_1’)[‘Col_2’] .sum( ) - To create groups - Two Keys – Apply on Col_2 grouped by Col_1.
* df['Column_name'].map( { old1:new1 , old2:new2} ) – Change the all values of a column from old to new. We have to write for all values of column otherwise Nan will appear.
* df['Column_name'].mean() - To show Mean value of a column.
* df.groupby('Column_1').Column_2.describe() - To create groups based on Column1 and show statistics summary based on Column2.
