# Flight Booking Price Prediction Project Report

## 1. Introduction

This report details a project focused on analyzing and predicting flight booking prices using a dataset containing various flight details. The project utilizes Python, Pandas, Matplotlib, and Seaborn for data preprocessing and exploratory data analysis (EDA). The primary goal is to understand the factors influencing flight prices and to prepare the data for future predictive modeling.

## 2. Objectives

The primary objectives were:

* To load and inspect the flight booking dataset.
* To perform exploratory data analysis to understand the relationships between different features and flight prices.
* To clean and preprocess the data for further analysis and modeling.
* To visualize key insights from the dataset.

## 3. Methodology

The project followed these steps:

1.  **Data Loading and Initial Inspection:**
    * Imported necessary Python libraries: Pandas, NumPy, Matplotlib, and Seaborn.
    * Loaded the "Flight_Booking.csv" dataset into a Pandas DataFrame.
    * Displayed the first few rows of the DataFrame to understand the data's structure.
    * Checked for data types and null values using `info()`.
    * Used `describe()` to get the statistical description of the numerical data.
    * Checked for duplicated rows.
2.  **Data Preprocessing:**
    * Removed the "Unnamed: 0" column as it was an index column.
3.  **Exploratory Data Analysis (EDA):**
    * Calculated the number of unique flights per airline.
    * Visualized the number of unique flights per airline using a bar plot.
    * Analyzed the statistical description of numerical columns.
    * Checked for duplicate values.
    * Calculated the number of unique flights for each airline.
    * Visualized the number of unique flights for each airline.

## 4. Dataset Description

The "Flight_Booking.csv" dataset contains the following columns:

* **airline:** Name of the airline.
* **flight:** Flight code.
* **source_city:** City from which the flight departs.
* **departure_time:** Time of departure.
* **stops:** Number of stops in the flight.
* **arrival_time:** Time of arrival.
* **destination_city:** City to which the flight arrives.
* **class:** Class of the flight (Economy/Business).
* **duration:** Total duration of the flight.
* **days_left:** Number of days left for departure.
* **price:** Price of the ticket.

## 5. Results and Observations

* The dataset contained 300,153 entries with 11 columns.
* There were no null values in the dataset.
* There were no duplicate records.
* Indigo has the highest number of unique flights.
* The price column has a large range of values.
* The duration column also has a large range of values.
* The days\_left column has a range from 1 to 49.
* The statistical description of numerical data was displayed.
* The unique count of flights per airline was displayed in table form.
* The unique count of flights per airline was displayed in bar chart form.

## 6. Conclusion

This project successfully loaded, cleaned, and explored the flight booking dataset. The EDA provided valuable insights into the distribution and relationships of the features. The data is now ready for further analysis and predictive modeling to forecast flight prices.

## 7. Future Work

Future work on this project could include:

* Encoding categorical variables for modeling.
* Building predictive models to forecast flight prices.
* Performing more in-depth EDA to uncover hidden patterns.
* Feature engineering to create new relevant features.
* Visualizing the distribution of prices, durations and days left.
* Visualizing the relationship between categorical variables and the price.
* Building a predictive model to predict the price of the flight.
