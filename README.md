# DATA PORTFOLIO: PIZZA SALES PROJECT

<p align="left">
  <a href="https://www.linkedin.com/in/trungbui011/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:ductrung3300754@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

&nbsp;&nbsp;&nbsp;&nbsp;This project focuses on analyzing sales data for a pizza franchise to optimize the product menu and understand customer purchasing behavior. 
The goal is to provide actionable insights into revenue drivers and operational efficiency.

&nbsp;&nbsp;&nbsp;&nbsp;The [Raw Data](./pizza_sales%20raw%20data.xlsx) contains comprehensive sales records for a pizza franchise. It is structured in a flat-table format, including Order IDs, Dates, Times, and Pizza Specifications (Name, Category, Size, Ingredients, and Price).

![](./Raw%20Data.JPG)

## BUSINESS REQUIREMENTS
- To evaluate the distribution of orders across different time dimensions and product specifications.
- To track and rank individual product performance.

## DATA GATHERING AND TRANSFORMATION
Imported the raw data into a **SQL** environment for ETL Data (Extract - Transform - Load). You can see SQL Queries [**here**](./Data%20Cleaning%20Pizza_Sales%20Queries.sql)

I created a **Virtual Table** and utilized functions like **DATENAME** and **DATEPART** to extract time-based dimensions from the raw **order_date**. This allowed for a granular analysis of sales performance, such as identifying peak ordering hours, busiest days of the week, and monthly revenue trends.

## DASHBOARDING
- **Inventory Optimization:** Based on the "Bottom 5" analysis, I recommend re-evaluating the Brie Carre Pizza. Since it has the lowest sales volume, we should consider removing it from the menu or launching a "Buy 1 Get 1" promotion to clear existing stock.
- **Dynamic Staffing:** Data shows a significant peak between 5 PM - 7 PM. Kitchen staffing should be increased by 20% during these hours to reduce wait times and improve customer satisfaction.
- **Targeted Marketing:** The Large (L) size Classic Category is the primary revenue driver. Marketing campaigns should focus on "Combo Deals" involving these popular configurations to increase the Average Order Value (AOV).

![](Pizza_Dashboarding.JPG)

In case you want to see every detail, you can download the full Power BI dashboard [here](./Pizza%20Sales%20Dashboard.pbix).

## Feedback & Contributions
This is a sample project created for self-assessment and skill-building. 
I welcome any feedback or suggestions. Feel free to open an issue or reach out!
