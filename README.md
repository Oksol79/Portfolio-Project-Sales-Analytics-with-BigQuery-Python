# Portfoilio Project Sales Analytics with BigQuery Python

## **Description:**

In this portfolio project, I conducted sales analytics for an online store using BigQuery and Python. I created a single dataset by merging the orders and sessions tables, which also included data from unregistered users. A detailed selection of join types (JOIN) helped to preserve all relevant data and ensure the completeness of the analytics, which is especially important due to the small number of registered users. The query resulted in an accurate and complete base for further analysis of sales and user behavior. The resulting dataset was used for further analysis and visualization.

## **Technologies & Libraries:**
 - BigQuery / SQL API (client.query).
 - Python for data analysis.
 - Pandas for data manipulation.
 - NumPy for numerical computing.
 - Matplotlib & Seaborn for data visualization.
 - SciPy (shapiro, normaltest, skew, spearmanr, kendalltau, norm, mannwhitneyu, kruskal) for statistical testing and analysis.
 - Scikit-posthocs for post-hoc tests for multiple comparisons.

## **Dataset:**
The dataset was created using a SQL query to the BigQuery database tables. The dataset included the following fields: order date, session ID, continent, country, device, browser, device model name, operating system, browser language, traffic source information, traffic channel, registered user ID, whether the user confirmed their email, whether the user subscribed to the newsletter, product category, product name, price, short product description. When creating the dataset, the necessary table join types were set. The fact that there are few registered users was also taken into account, but we are interested in all orders and all sessions, even if the user has not registered on the site.

## **List of tasks:**
1. Connecting to a database.
2. Create a SQL query.
3. Description of the received dataset.
4. Data analysis and visualization.
5. Sales dynamics analysis.
6. Data analysis using pivot tables.
7. Statistical analysis of relationships.
8. Statistical analysis of differences between groups.
9. Tableau Public Visualization.
10. Business Summary.

## **Demonstrated Skills:**
In this project, I demonstrated a wide range of skills, including effective data analysis:

1. Connecting to a database using SQL query.  
Connecting to a cloud database and creating a dataset using SQL query to extract, filter, and aggregate sales data.

2. Understanding and exploring data.  
Interpreting and documenting the data set’s structure, variables, and data quality to ensure robust analysis.

3. Cleaning and preparing data.  
Preparing data sets for analysis, including handling missing values, transforming data, and creating features.

4. Exploratory data analysis (EDA).  
Performing in-depth data analysis and visualization to identify trends, patterns, and anomalies in sales data.

5. Sales performance and trend analysis.  
Analyzing sales dynamics over time to assess growth, seasonality, and performance changes.

6. Pivot Table Analysis.  
Use pivot tables to summarize and compare sales figures across multiple dimensions (time, product categories, regions).

7. Statistical Analysis of Relationships.  
Apply correlation analysis and nonparametric statistical methods to assess relationships between variables.

8. Statistical Hypothesis Testing.  
Apply statistical tests to identify significant differences between groups and test analytical assumptions.

9. Data Visualization.  
Create visualizations using Python and Tableau Public to effectively present results.

10. Business Analytics and Decision Support.  
Translate analytical results into actionable business insights and summarize key findings from a given dataset.
