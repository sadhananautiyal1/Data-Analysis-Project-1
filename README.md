# Customer Behavior Analysis & Dashboard Project
Project Overview
This project focuses on analyzing customer purchasing behavior using **Python, PostgreSQL, and Power BI** to extract meaningful business insights. The objective was to understand customer segments, revenue patterns, product performance, and purchasing trends, and then visualize them through an interactive dashboard.

The dataset contains **3,900 customer records** with attributes such as demographics, purchase details, subscription status, shipping preferences, discounts, and product categories.
##Technologies Used
* **Python** — Data cleaning, preprocessing, and exploratory data analysis (EDA)
* **Pandas— Data manipulation and visualization
* **PostgreSQL** — Advanced querying and business analysis
* **Power BI** — Interactive dashboard creation and visualization
* **Jupyter Notebook / Anaconda** — Development environment
##Project Workflow
### 1️⃣ Data Loading
The dataset was loaded into Python using Pandas for initial inspection and preprocessing.
Key steps:
* Importing CSV file
* Checking data structure (`info()`, `describe()`)
* Identifying missing values
* Understanding categorical and numerical features
### 2️⃣ Exploratory Data Analysis (EDA)
EDA was performed to understand patterns and distributions within the dataset.
Analysis included:
* Customer demographics distribution
* Purchase amount trends
* Category-wise sales patterns
* Subscription behavior
* Shipping preferences
* Review rating distribution
Visualizations helped identify key behavioral insights before moving to advanced analysis.
### 3️⃣ Data Cleaning & Preprocessing
Data cleaning steps included:
* Handling missing values
* Converting categorical variables
* Creating new features such as:
  * Age groups
  * Purchase frequency in days
  * Customer segmentation (New, Returning, Loyal)
* Data type corrections for SQL compatibility
This ensured accurate analysis and smooth database integration.
### 4️⃣ PostgreSQL Database Integration
The cleaned dataset was imported into PostgreSQL for structured querying and business intelligence analysis.
Key SQL analyses performed:
* Revenue comparison by gender
* Impact of discounts on spending behavior
* Top-rated products
* Shipping type vs purchase amount comparison
* Subscription vs non-subscription spending
* Discount usage percentage by product
* Customer segmentation analysis
* Top products within each category
* Repeat buyers vs subscription likelihood
* Revenue contribution by age group
These queries helped extract actionable business insights from raw data.
### 5️⃣ Power BI Dashboard Creation
An interactive **Customer Behavior Dashboard** was created in Power BI to visualize insights dynamically.
Dashboard features:
* KPI Cards:
  * Total Customers
  * Average Purchase Amount
  * Average Review Rating
* Revenue by Category
* Sales by Category
* Revenue by Age Group
* Sales by Age Group
* Subscription Status Distribution
* Interactive Filters:
  * Gender
  * Category
  * Shipping Type
  * Subscription Status
The dashboard allows users to explore customer behavior dynamically across multiple dimensions.
## 📊 Key Insights
* Majority of customers were **loyal (~80%)**, indicating strong retention.
* **Young adults generated the highest revenue**, followed closely by middle-aged customers.
* **Male customers contributed higher revenue** compared to females.
* Express shipping customers had slightly higher average purchase amounts than standard shipping.
* Clothing and accessories were the most purchased categories.
* Subscription did not significantly increase spending, suggesting improvement opportunities.
## 🎯 Business Recommendations
* Improve new customer acquisition strategies.
* Strengthen loyalty and retention programs.
* Target marketing campaigns toward young adult demographics.
* Promote high-demand products such as clothing essentials and accessories.
* Enhance subscription benefits to increase adoption.
* Use discount strategies strategically for apparel categories.
## 📸 Dashboard Preview
<img width="860" height="482" alt="image" src="https://github.com/user-attachments/assets/fe2d7831-e517-451f-b4ff-73874f3736d3" />

## 🙏 Acknowledgement
I would like to sincerely thank **Amlan Mohanty** for guidance and support in helping me learn and complete this project,as i have taken this project for my learning from his channel.

## 🚀 Conclusion
This project demonstrates the complete data analytics pipeline — from raw data processing to business intelligence visualization — using industry-relevant tools such as Python, PostgreSQL, and Power BI. It highlights how data-driven insights can support better business decisions and customer understanding.



