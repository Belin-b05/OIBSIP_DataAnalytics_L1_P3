NYC AIRBNB DATA CLEANING AND PREPROCESSING 

Overview

This project involves cleaning and preprocessing a dataset containing information about Airbnb listings in New York City (NYC). The dataset includes details such as listing IDs, host information, location, room types, pricing, and availability.

Data Cleaning

Data Integrity

Total entries: 48,895

Columns: 16

Missing Values

'name' column: 16 missing values

'host_name' column: 21 missing values

'last_review' column: 10,052 missing values

'reviews_per_month' column: 10,052 missing values

Imputing Missing Values

Removed columns 'name', 'host_name', 'last_review'

Imputed missing values in 'reviews_per_month' with the mean value

Duplicate Removal

No duplicate records found

Standardization

Standardized numerical columns using StandardScaler

Outlier Detection

Detected outliers using z-scores with a threshold of 3

Removed outliers from the dataset (3263 outliers removed)

Summary
After cleaning and preprocessing the NYC Airbnb dataset, the resulting dataset is free of missing values, duplicates, and outliers, and the numerical columns have been standardized.
