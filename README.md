# Taxi-Data-Preprocessing-EDA
n this project, we perform data cleaning and preprocessing on the taxis dataset, focusing on handling missing values and outliers. 

**1. Missing Value Imputation:**

payment: Missing values in the payment column were filled with the most frequent value (mode).
pickup_borough and dropoff_borough: Missing values were handled using forward fill (ffill) and backward fill (bfill) methods to propagate the most relevant data from surrounding rows.

**2.Handling Zero Passengers:**

Identified rows with zero passengers and analyzed if it is valid or needs further investigation.

**3.Exploratory Data Analysis (EDA) Setup:**

Statistical and visual analysis was conducted using libraries such as Seaborn and Matplotlib to identify patterns and insights in the data.

**4.Additional Data Cleaning:**

Columns with null values were filled using appropriate methods, and inconsistent or missing data were handled systematically.
This ensures the dataset is ready for further analysis and model building, with clean and reliable data for insights.



