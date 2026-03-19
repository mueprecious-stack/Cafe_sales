# Data Cleaning and Exploratory Data Analysis
---
### Project Overview
---
The Dirty Cafe Sales dataset contains 10,000 rows of data representing sales transactions in a cafe. This dataset  is "dirty", with missing values, inconsistent data, and errors for data cleaning and exploratory data analysis (EDA). The goal is to clean and prepare it for analysis.”

### Correlation Heatmap

<img width="520" height="423" alt="Correlation Heatmap" src="https://github.com/user-attachments/assets/ee114eb8-a1fb-43af-929a-c029fa0796e6" />


## Table of Contents
* [Data Sources](#data-sources)
* [Tools](#tools)
* [Data Cleaning and Preparation](#data-cleaning-and-preparation)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Business Insights](#business-insights)
* [Recommendations](#recommendations)
* [Limitations](#limitations)
* [Conclusion](#conclusion)

### Data Sources
---
Cafe Sales: the dataset used is the dirty_cafe_sales.csv file, containing detailed information on each sales transaction in a Cafe.

### Tools
---
- Python(pandas, numpy)
  - [Download here](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training)

### Data Cleaning and Preparation
---
1. Handling missing data
2. Checking duplicated rows for removal
3. Feature Engineering
4. Final data inspection

### Exploratory Data Analysis
---
The exploratory data analysis(EDA) addressed key business questions including:
  1. How sales trended throughout the year.
  2. Which items generated the highest sales and the reasons behind their performance.
  3. The relationship between quantity sold, price and total amount spent.
  4. Which items contributed most to overall revenue.
  5. Which locations were most prefered by customers. 
     
### Business insights
---
1. Sales peak in June and decline in February and November.
2. Higher-priced items tend to generate higher sales, as shown by the strong positive correlation (0.65) between 'Price Per Unit' and 'Total Spent'.
3. Item price appears to have little influence on customer purchasing behaviour as indicated by the very weak positive correlation (0.0073) between 'Price Per Unit' and 'Quantity' ordered.
4. Sales revenue increase as the number of items ordered increases, indicating a direct positive correlation(0.70) between 'Quantity' and 'Total Spent'
5.  Coffee contributes the most to overall sales at 12.9%, while Cookie contributes the least at 11.9%
6.   Customers prefer in-store orders to Takeaway orders

### Recommendations
---
1. Allocate more inventory and staff during the June peak, and increase marketing efforts during declines in February and November
2. Since customer purchasing behaviour does not appear to be significantly affected by item prices, introducing premium packages could be a viable strategy to increase overall sales and profit.
3. Given the high demand for coffee, increasing its quantity can maximize sales.
4. Customers Preference for in-store orders suggests that expanding the cafe could drive growth

### Limitations
---
Over 40% of rows in the 'Payment Method' and 'Location' fields had to be randomly sampled, however, meaningful business insights can still be made.

### Conclusion
---
Only a very small fraction of rows (0.26%) was removed from the dataset, which does not impact the analysis results. The data is clean and ready for further analysis, and actionable business insights and recommendations have been derived.
