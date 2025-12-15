# Portfoilio-Project-Sales-Analytics-with-BigQuery-Python

## **Description:**

In this portfolio project, I conducted sales analytics for an online store using BigQuery and Python. I created a single dataset by merging the orders and sessions tables, which also included data from unregistered users. A detailed selection of join types (JOIN) helped to preserve all relevant data and ensure the completeness of the analytics, which is especially important due to the small number of registered users. The query resulted in an accurate and complete base for further analysis of sales and user behavior. The resulting dataset was used for further analysis and visualization.

## **Technologies & Libraries:**
 - Python for data analysis.
 - Pandas for data manipulation.
 - NumPy for numerical computing.
 - Matplotlib & Seaborn for data visualization.
 - SciPy (shapiro, normaltest, skew, spearmanr, kendalltau, norm, mannwhitneyu, kruskal) for statistical testing and analysis.
 - Scikit-posthocs for post-hoc tests for multiple comparisons.

## **Dataset:**
The dataset was created using a SQL query to the BigQuery database tables. The dataset included the following fields: order date, session ID, continent, country, device, browser, device model name, operating system, browser language, traffic source information, traffic channel, registered user ID, whether the user confirmed their email, whether the user subscribed to the newsletter, product category, product name, price, short product description. When creating the dataset, the necessary table join types were set. The fact that there are few registered users was also taken into account, but we are interested in all orders and all sessions, even if the user has not registered on the site.




