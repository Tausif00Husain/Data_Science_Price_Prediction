# Data_Science_Price_Prediction

1) About Project
    -In this porject we build a machine learning model who is predict the price of the house.
    -In this project, we use supervised learning.

2) Data Cleaning
    - We remove some columns for fast performance.
    - For deal with null values, we take median for some column and drop null rows for some rows.
    - There were some values ​​like '2 BHK' in the size column from which we removed the text and took the integer  
      by using regex.
    - In the total_sqft we have 2100 - 2850 this type of value for deal this type of value we use a function that 
      is take average of 2100 - 2850 this type of value and if the value is float then return as it is.
