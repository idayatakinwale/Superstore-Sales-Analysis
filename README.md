# Superstore Sales Analysis

This is a powerbi project involving analysis of sales data from a fictional superstore to uncover insights and trends that can help to improve business decisions. The analysis covers various aspects of sales performance, customer demographics, product categories and geographical distribution. 


### Objective
---

The primary objective of this project is to create a comprehensive Power BI dashboard that provides actionable insights into the superstore’s sales performance, helping stakeholders to make data-driven decisions.

### Skills / Concepts Demonstrated
---

The following power BI features were incorporated:

Data Analysis Expressions DAX, Quick measures, Page Navigation, Modelling, Filters, Tooltips.

### Data Source
---

The dataset titled Superstore_Normalized is an excel file downloaded from the GitHub website - https://github.com/theoyinbooke/30Days-of-LearningData-Analysis-Using-Power-BI-for-Students/tree/main/Data%20Modelling%20Dataset. 

It consists of five different tables namely – Sales, Products, Customer, Sales Rep and Location tables.

### Tools Used
---

**Power BI**: Utilized for creating interactive dashboards and visualizations.

**Power Query**: Employed for data extraction, transformation, and cleaning.

**DAX (Data Analysis Expressions)**: Used for creating calculated columns, custom measures and advanced data manipulation with Power BI.

### Data Cleaning / Transformation
---

The dataset is clean to a good extent, so few cleaning steps were carried out using the power query editor on the PowerbI desktop

- For the product table and customer table, their first rows were used as headers by selecting the "Use first row as headers" icon under the transform tab. 
- Neither duplicate nor null values were found in the dataset
- New measures were created for the Total Sales, Total Quantity, Total Profit and Average Delivery Days using the DAX approach. 
- A new column (Delivery days) was added to the Sales table using the ''DATEDIFF'' DAX formula.

### Modelling
---

A perfect star-schema model was automatically generated, with the required relationship. There are 4-dimension tables and one fact table. The dimension tables are all joined to the fact table with a **one-to-many** relationship.



### Data Analysis & Visualization
---

The data model is brought to life through a series of interactive dashboards and reports that provide actionable insights and facilitate data-driven decision-making.

**Detailed Dashboard Features**

**Performance Metrics**: Tracks metrics such as Total Sales, Total Quantity Ordered, Total Profit and Average Delivery Days.

**Dynamic Time Series Analysis**: Offers sales forecasts and trend analysis to predict future performance such as the year-over-year growth for the monthly sales.

**Segmentation and Demographics Analysis**: Provides insights into customer behaviors and preferences, enhancing targeted marketing efforts. This includes Sales by Product Category, Sales by Customer Segment and Sales by Region

**Analysis of the least and most profitable product**: This shows the top 5 and the bottom 5 products by profit.

### Results/Findings
---

The following insights were derived from the dashboard created:

	About 32% of the cumulative sales was gotten from the western region of the country (e.g. in California), closely followed by 30% gotten from the eastern region (e.g. in New York).

	From the product category segment, the highest cumulative sales amount (840k) was gotten from the sale of the technological products such as phones, copiers, accessories.

	The highest amount of sales was always recorded between November and December of every year, and this can be attributed to the months falling within the holiday period.

	The customer segment with the highest amount of sale (51%) was the **Consumer** segment, followed by the **Co-operate** segment (31%) and then the **Home-Office** segment (18%).

	Within the classes of ship modes, about 1.4M sales were made from goods shipped by the **Standard-Class** means, 500k from the **Second-Class**, 400k from the **First-Class** and 100k from the **Same-Day** Shipping

### Recommendations
---

1.	It is recommended that more branches of the superstore should be opened in the two regions with the largest amount of sales (Western and Eastern regions).
2.	More technological products should be supplied to the store as the highest amount of sale and profit are derived from them. 
3.	The following recommendations should be considered due to the peak sales observed in the fourth quarter of the years in consideration:
- the store should increase inventory by ensuring adequate stock levels to meet customers’ needs and demand during these months 
- the store management is also advised to offer special deals (e.g. discounts, holiday promotions) to attract more customers during these periods 
- they should enhance customer experience during this period (preparing for higher foot traffic and online orders) to get efficient delivery and excellent customer services.










