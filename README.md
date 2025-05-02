###Credit Card Dashboard Analysis

##Overview
The Credit Card Dashboard Analysis project focuses on analyzing customer spending patterns to inform product strategies for launching a new line of credit cards. The dashboard provides detailed insights into demographics, spending behaviors, and income utilization across major Indian cities like Mumbai, Delhi NCR, Bengaluru, Hyderabad, and Chennai. It tracks key metrics such as average income utilization (42.8%), total spend (531M), and credit card payment percentage (40.74%), segmented by occupation, age group, gender, and marital status. Visualizations like decomposition trees, bar charts, and pie charts help identify high-value segments, such as salaried IT employees in Mumbai contributing 51.04% of total spend.
This project was created by Gireesh Shewale to support data-driven decision-making for credit card product development and targeted marketing strategies.

##Features

Demographic Segmentation: Analyze customers by city, age group, gender, marital status, and occupation.
Spending Breakdown: View expenditure by category (e.g., groceries, electronics, travel) and payment type (credit card vs. other methods).
Income Utilization Metrics: Track average income utilization (42.8%) and spending trends across segments.
Data Visualizations: Includes decomposition trees, bar charts, pie charts, and stacked area charts for intuitive insights.
Key Metrics Display: Highlights total customers (4,000), average income (206.6M), total spend (531M), and credit card payment percentage (40.74%).

##Project Structure

/data: Placeholder for raw datasets (demographic and spending data).
/visualizations: Stores dashboard screenshots and exported charts.
/docs: Contains documentation, including this README.
/scripts: Placeholder for scripts to automate data processing.

##Prerequisites

Software:
Power BI, Tableau, or Excel for dashboard creation.
Python (optional) for data preprocessing.


Libraries (if using Python):
pandas for data manipulation.
matplotlib or seaborn for visualizations.


Data:
Customer demographics: age, gender, marital status, occupation.
Spending data: categorized by payment type and expenditure category.
Income and utilization metrics.



##Setup Instructions

Clone the Repository:
git clone https://github.com/your-username/credit-card-dashboard-analysis.git
cd credit-card-dashboard-analysis


Prepare the Data:

Obtain demographic and spending data in CSV or Excel format.
Include columns for city, age group, gender, marital status, occupation, income, spend, and payment type.
Place data files in the /data directory.


Set Up the Dashboard:

Import data into Power BI or Tableau.
Recreate the dashboard using the screenshots:
Demographic Classification: Pie charts for age, gender, and marital status.
Spending by Payment Type: Stacked bar charts for credit card vs. other methods.
Decomposition Tree: Breakdown of income utilization by city, occupation, age, gender, and category.
Spending Insights: Bar charts for average spend by category, age, and marital status.




Run Scripts (Optional):

If using Python, install dependencies:pip install pandas matplotlib seaborn


Execute scripts in /scripts for additional analysis.



##Usage

Navigate the Dashboard:

Use filters for city, age group, gender, and marital status to segment data.
Analyze metrics like total spend (531M), average income (206.6M), and credit card payment percentage (40.74%).
Review spending by category (e.g., groceries: 86.3M, electronics: 79.6M) and occupation.


##Key Insights:

High-Value Segment: Salaried IT employees in Mumbai contribute 51.04% of total spend, with 76.29% income utilization.
Spending Trends: Credit card usage is highest in electronics (46.4%) and entertainment (46.5%).
Demographic Patterns: The 35–45 age group (34.75%) and males (64.33%) dominate spending; married customers spend more on groceries (86.3M).
City Breakdown: Mumbai leads with 514.36M in spend; Bengaluru shows the highest average income (70.8K) among business owners.


##Apply Insights:

Tailor credit card features for high-spending segments (e.g., rewards for electronics).
Target marketing towards salaried IT employees in Mumbai and the 35–45 age group.
Offer cashback on groceries for married customers to boost adoption.



##Screenshots

Demographic Classification: 


Spending by Payment Type: Stacked bar chart for credit card vs. other methods.
Decomposition Tree: Breakdown of income utilization by city and occupation.
Spending Insights: Bar charts for average spend by category and marital status.

##Contributing

Fork the repository.
Create a branch:git checkout -b feature/your-feature-name


Commit changes:git commit -m "Add your commit message"


Push and create a pull request:git push origin feature/your-feature-name



Contribution Ideas

Add scripts for automated data preprocessing.
Enhance the dashboard with predictive analytics for spending trends.
Include additional filters for deeper segmentation.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Created by Gireesh Shewale
