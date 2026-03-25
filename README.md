Churn Modelling Dashboard (Power BI)

Project Overview
The Churn Modelling Dashboard is an interactive Power BI project developed to analyze customer churn and understand the key factors influencing customer retention.
This dashboard transforms raw customer data into meaningful insights using effective visualizations, helping stakeholders make informed business decisions.

Objectives
Analyze customer churn patterns  
Identify factors affecting customer retention  
Compare customer segments across multiple dimensions  
Build an interactive and insightful dashboard  

Dataset Description
The dataset used is Churn Modelling, which includes the following attributes:

- Customer ID  
- Age  
- Gender  
- Geography  
- Balance  
- Credit Score  
- Estimated Salary  
- Tenure  
- Number of Products  
- Active Member Status  
- Churn Status (Exited)  

Visualizations Used

1.Line Chart
Used to display trends and patterns in data over a continuous variable.

2.Clustered Column Chart
Used for comparing churned and non-churned customers across different categories.

3.Bar Chart
Used for horizontal comparison of categories, especially when labels are long.

4.Pie Chart / Donut Chart
Used to represent the proportion of churned vs retained customers.

5.Card Visual (KPI)
Displays key metrics such as:
- Total Customers  
- Total Churned Customers  
- Churn Rate  
- Average Balance  

6.Table Visual
Provides a detailed view of the dataset for deeper analysis.

7.Matrix Visual
Used for hierarchical comparison across multiple dimensions.

8.Stacked Column Chart
Shows both composition and comparison of data across categories.

9.Scatter Plot
Used to identify relationships between numerical variables (e.g., Balance vs Age).

10.Slicers (Filters)
Enables dynamic filtering of data by:
- Gender  
- Geography  
- Age Group  
- Balance Category  

11.Area Chart
Used to visualize trends with emphasis on magnitude over time.


Data Preparation and Modeling

Data Cleaning
- Handled missing values  
- Corrected data types  
- Created derived columns  

DAX Measures
- Total Customers  
- Churn Count  
- Churn Rate  
- Average Balance  
- Active Customers  

Key Insights
- Certain customer segments show higher churn rates  
- Lower engagement leads to higher churn probability  
- Balance and number of products influence retention  
- Inactive members contribute significantly to churn  


Tools and Technologies
- Power BI Desktop  
- DAX (Data Analysis Expressions)  

 How to Use
1. Download the `.pbix` file from this repository  
2. Open it in Power BI Desktop  
3. Use slicers to filter data  
4. Interact with visuals to explore insights  


Future Enhancements
- Add advanced DAX calculations  
- Improve dashboard design  
- Implement predictive churn analysis  
---

## License
This project is open-source and available under the MIT License.
