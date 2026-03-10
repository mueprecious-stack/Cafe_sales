# Data Cleaning Project
---
### Project Overview
---
The Dirty Cafe Sales dataset contains 10,000 rows of data representing sales transactions in a cafe. This dataset  is "dirty", with missing values, inconsistent data, and errors for data cleaning and exploratory data analysis (EDA). The goal is to clean and prepare it for analysis.”

### Data Sources
---
Cafe Sales: the dataset used is the dirty_cafe_sales.csv file, containing detailed information on each sales transaction in a Cafe.

### Tools
---
- Python
  - [Download here](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training)

### Data Cleaning Process
---
1. Importing libraries
2. Data loading and initial inspection
3. Convert all invalid entries in the dataset to null values
4. Change the data type of the numerical columns to float in order to perform mathematical calculations
5. Find missing values in numerical columns using the formula: Total Spent = Quantity * Price Per Unit
6. Fill missing rows in the Item column by mapping price Per Unit
7. Find missing values in categorical columns 'Payment Method' and 'Location' by random sampling
8. Interpolating missing date values  
9. Drop rows with missing values
10. Find and drop duplicated rows


### Data Cleaning summary
---
1. Handling missing data
2. Checking duplicated rows for removal
3. Feature Engineering
4. Final data inspection


