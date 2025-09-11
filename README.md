# Bigmart Sales Analysis
Big Mart Integrated Data Analysis Project Using MySQL, Python, Excel and Power BI

## Table of Contents

 - [Project Overview](#project-overview)
 - [Tools and Technologies Used](#tools-and-technologies-used)
 - [Project Flow Summary](#project-flow-summary)
 - [Dataset](#dataset)
 - [Results/Findings](#results-findings)
 - [Recommendations](#recommendations)



 ## Project Overview

  - This project conducts a comprehensive analysis of Big Mart’s sales performance and Inventory distribution to identify key insights and
    opportunities for optimization using various KPI’s and visualizations in Power Bi.
  - The analysis has been carried out using tools such as MySQL, Python, Excel and Power Bi to efficiently handle data, perform exploratory analysis and create visual dashboard.



 ## Tools and Technologies Used  

 - **Database Management:**
    - **MySQL:** :** Used to store, query, manage the sales dataset efficiently along with data cleaning and formatting.

 - **Programming & Data Analysis:**
     - **Python:**  Utilised for transformation and exploratory analysis.
     - **Libraries:**
        - **pandas** for data manipulation and aggregation
        - **matplotlib** and **seaborn** for visualizations
   
 - **Spreadsheet Analysis:**
     - **Microsoft Excel:** Used for pivot tables, charts.

 - **Data Visualization & Dashboarding:**
     - **Power BI:** CrMeated interactive dashboard and visual reports to present findings effectively.
  


 ## Project Flow Summary  
 
   - **MySQL**
      - Created a relational database to store structured data.
      - Used SQL queries to extract and filter the required information.
      - Performed data cleaning and formatting.

   - **Python((Pandas,Matplotlib,Seaborn)**
      - Imported data from MySQL using SQLAlchemy.
      - Conducted exploratory data analysis using python libraries and  generated visualizations.
    
   - **Excel**
      - Exported cleaned data to Excel.
      - Used formulas, pivot tables and charts for additional analysis.

   - **Power BI**
      - Connected to the Excel.
      -	Built interactive dashboard with filters, slicers and KPI’s.
      -	Presented key findings in a user- friendly format.
    



 ## Dataset   
  
  - **Source:** [Bigmart Sales Dataset on Kaggle]( https://www.kaggle.com/datasets/ahmadrezagholami2001/bigmart-sales-dataset)
  - **Number of Records:** 8524 records with 12 columns containing product,sales figures and outlet details.
  - **Issues:**
     - Formatting inconsistencies (e.g., “Low Fat” vs “low fat”) were standardized.
     - Null values were represented as NA in the dataset, which required preprocessing before analysis.


   
 ## Results/Findings

   - **Low Fat Products** account for the highest number of orders and total sales. Although the average sales per order for Low Fat products is slightly lower than that of Regular products, the overall contribution of Low Fat items to revenue is significant and acceptable.    
   - **Small-sized outlets** are generating higher total sales compared to Medium and High outlet sizes. This suggests that investing in and expanding small outlets could be a strategic move for improving profitability in the future.
   - **Tier 2 outlet locations** recorded the highest sales compared to Tier 1 and Tier 3 outlets, with approximately ** 43% higher sales percentage**, indicating that Tier 2 regions are key contributors to revenue.
     
   ![Sales BY Fat Content](images/sales_by_fat_content.png)
   ![Sales By Outlet Location](images/sales_by_outlet_location.png)
   



 ## Recommendations

   - **Promote Low Fat products:** Since Low Fat items generate the highest number of orders and contribute significantly to total revenue, marketing campaigns and inventory strategies should focus on expanding and promoting these products.
   - **Expand Small -sized outlets:** Small outlets are outperforming Medium and High outlet sizes in total sales. Investing more in small outlets and exploring new locations could improve profitability and market reach.
   - **Target Tier 2 locations:**  With Tier 2 outlets approximately **43% higher sales** compared to Tier 1 and Tier 3, expanding operations or running targeted promotions in Tier 2 regions could further boost sales and customer engagement.
   - **Monitor sales trends:**  Regularly analyzing sales across outlet types and regions will help identify emerging patterns and adjust strategies accordingly for sustained growth.
    

 

  
    
    





      
   
      
                  
   

 


