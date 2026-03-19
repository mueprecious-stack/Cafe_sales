# Data Cleaning and Exploratory Data Analysis
---
### Project Overview
---
The Dirty Cafe Sales dataset contains 10,000 rows of data representing sales transactions in a cafe. This dataset  is "dirty", with missing values, inconsistent data, and errors for data cleaning and exploratory data analysis (EDA). The goal is to clean and prepare it for analysis.”

## Table of Contents
* [Data Sources](#data-sources)
* [Tools](#tools)
* [Data Cleaning Process](#data-cleaning-process)
* [Exploratory Data Analysis](#exploratory-data-analysis)
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
1. Handling missing data
2. Checking duplicated rows for removal
3. Feature Engineering
4. Final data inspection

### Exploratory Data Analysis
---
1.Importation of libraries and loading of cleaned dataset
2. Tracking monthly sales trend using a line chart
3. Assesed total sales per Item
4. plotted a heatmap to check correlation between numbers
5. Using a pie chart to assess the contribution of each item towards total revenue
6. Identitified order location prefered by customers

### Limitations
---
Over 40% of rows in the 'Payment Method' and 'Location' fields had to be randomly sampled, fortunately, these fields are of little importance in analysis because meaningful business insights can still be found without them.

### Conclusion
---
A remarkably small percentage of rows (0.26) was removed from 10,000 rows of the dataset, and will not affect analysis findings. The data is clean and ready for further analysis. I will further explore the provided dataset and perform analysis in a forthcoming project.
