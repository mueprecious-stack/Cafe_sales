# Data Cleaning Project
---
### Project Overview
---
The Dirty Cafe Sales dataset contains 10,000 rows of data representing sales transactions in a cafe. This dataset  is "dirty", with missing values, inconsistent data, and errors for data cleaning and exploratory data analysis (EDA). The goal is to clean and prepare it for analysis.”

## Table of Contents
* [Data Sources](#data-sources)
* [Tools](#tools)
* [Data Cleaning Process](#data-cleaning-processS)
* [Data Cleaning Summary](#data-cleaning-summary)
* [Limitations](#limitations)
* [Conclusion](#conclusion)

### Data Sources
---
Cafe Sales: the dataset used is the dirty_cafe_sales.csv file, containing detailed information on each sales transaction in a Cafe.

### Tools
---
- Python(pandas, numpy)
  - [Download here](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training)

### Data Cleaning Process
---
1. Importing libraries
2. Data loading and initial inspection
3. Convert all invalid entries in the dataset to null values
4. Change the data type of the numerical columns to float in order to perform mathematical calculations
5. Calculate missing values in numerical columns using the formula: Total Spent = Quantity * Price Per Unit
6. Calculate missing items using the 'Price Per Unit' through mapping
7. Fill missing values in categorical columns 'Payment Method' and 'Location' by random sampling
8. Interpolate missing date values
9. Feature Engineering on date 
10. Drop rows with missing values, and duplicated values

### Data Cleaning summary
---
1. Handling missing data
2. Checking duplicated rows for removal
3. Feature Engineering
4. Final data inspection

### Limitations
---
Over 40% of rows in the 'Payment Method' and 'Location' fields had to be randomly sampled, fortunately, these fields are of little importance in analysis because meaningful business insights can still be found without them.

### Conclusion
---
A remarkably small percentage of rows (0.26) was removed from 10,000 rows of the dataset, and will not affect analysis findings. The data is clean and ready for further analysis. I will continue to explore the provided dataset and perform further analysis in a forthcoming notebook.
