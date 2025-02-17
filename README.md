# Cafe-Sales-Data-Analysis
Exploratory Data Analysis - Cafe Sales Data<br>

In this repository, I have taken COVID 19 data from Kaggle and I have done:

1. Data Cleaning:
   <br>Handling inconsistent or erroneous data entries, specifically addressing errors and converting data types for 'Quantity', 'Price Per Unit', 'Total Spent', and 'Transaction Date' columns.<br>
   Standardizing categorical values for 'Payment Method' and 'Location' to ensure consistency.<br>
   Replacing 'ERROR' values with 'None' and handling missing values in key columns.<br>

2. Data Preprocessing:

   <br>Removing rows with missing values in essential columns like 'Item', 'Quantity', 'Price Per Unit', 'Total Spent', and 'Transaction Date'.<br>
   Applying standardization (z-score normalization) and min-max scaling to numerical features ('Quantity', 'Price Per Unit', 'Total Spent') to prepare data for potential modeling.<br>
   Calculating the Interquartile Range (IQR) for outlier analysis.<br>

3.Data Exploration and Visualization:

<br>Generating descriptive statistics to understand the data distribution.<br>
Identifying and reporting missing values in the cleaned dataset.<br>
Visualizing sales trends over time using a line plot.<br>
Analyzing the popularity of items sold using a count plot.<br>

Feel free to download the code and data.
Examining the distribution of payment methods using a count plot.
