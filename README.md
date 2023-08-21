# E-commerce Data Analysis

The E-commerce Sales Data Analysis project aimed to extract valuable insights from a large dataset of sales transactions in the online retail sector. The project employed a multi-step approach, starting with the creation of a robust data model using SQL Server, ensuring efficient data storage and retrieval. Data cleaning and preprocessing were conducted in Jupyter Notebook, addressing missing values, outliers, and inconsistencies to ensure the accuracy and reliability of the subsequent analysis.

Utilizing the cleaned data, Power BI was employed to create interactive and visually appealing data visualizations. These visualizations provided an in-depth exploration of various sales trends, customer behaviors, product performance, and geographical distribution. Through dynamic dashboards and reports, stakeholders were able to identify key performance indicators, such as top-selling products, peak sales periods, and customer preferences.

The project's comprehensive approach not only facilitated data-driven decision-making for business strategies but also empowered stakeholders to gain actionable insights. By combining SQL Server, Jupyter Notebook, and Power BI, this project demonstrated how a seamless integration of tools can transform raw sales data into meaningful and actionable business intelligence.

# Dataset 
The dataset used was scraped from an e-commerce website using Selenium. 

This dataset contains information related to Ecommerce sales, featuring details such as customer IDs, their names, purchased product categories and names, customer segments, delivery statuses, order dates, IDs, and shipping information. It also includes metrics like days for shipment, order item discount, sales per order, order quantity, and profit per order. The dataset provides insights into customer locations, regions, and countries, as well as various aspects of the sales process, including shipping types and delivery performance.

# Data Model

The model consists of 3 tables, 1 extra table was added to manage the location and be able to obtain important information based off this.

![image](https://github.com/jzuluaga02/ecommerce-data-analysis/assets/114960212/1c0acc45-dbf1-4eae-a622-893dd388419e)

# Data Cleaning

Besides the location table, another table for the dates called Calendar was added. This table is mostly used to generate important information that depends strongly on the data, specifically for the KPIs in our dashboard. 

On the other hand, the dataset contained some null values and format errors in the dates that needed to be changed and cleaned. In Jupyter Notebook using the library pandas this cleaning was possible.

# Dashboard

![Dashboard ecommerce ](https://github.com/jzuluaga02/ecommerce-data-analysis/assets/114960212/24df9c25-8402-4637-97b7-17e06d7464a5)

# Conclusions

Integrated Data Approach: This project harnessed the synergy of SQL Server, Jupyter Notebook, and Power BI to create a cohesive analytical journey.

Optimized Data Handling: SQL Server's robust data model ensured efficient storage and retrieval, enabling quick and reliable access to insights.

Data Reliability: The thorough cleaning and preprocessing of the dataset in Jupyter Notebook enhanced its accuracy and consistency, forming a reliable foundation for analysis.

Visual Storytelling: Through Power BI's interactive dashboards and visualizations, intricate sales trends, customer behaviors, and product performances were vividly revealed.

Strategic Insights: The project's outputs empower stakeholders to make informed decisions, identifying high-performing products, peak sales periods, and customer preferences.

Comprehensive Analysis: The addition of location and calendar tables enriched the analysis, enabling a broader context for understanding customer behavior and facilitating the calculation of key performance indicators.

Holistic Impact: By showcasing how these tools collaborate seamlessly, the project underscores the transformative potential of data-driven insights in shaping strategic direction and operational efficiency.


