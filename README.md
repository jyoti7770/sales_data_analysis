# Excel Sales Analysis and Visualization for Business Decision
![Ecommerce sales logo](https://github.com/jyoti7770/sales_data_analysis/blob/main/worldwide-ecommerce-sales.jpg)

## Objective
To perform a comprehensive analysis of e-commerce sales data using Excel and charts,aimed at
identifying key sales trends and customer purchasing behaviours and profit.
the analysis is focus on improving sales forcasting and enhancing profitability through data-driven insight.

## Dataset
the data for this project is taken from kaggle dataset:
-**Dataset link:**[Sample superstore datset](https://www.kaggle.com/datasets/bravehart101/sample-supermarket-dataset)

## Analysis steps
### Cleaning data 
To ensure data quality and prepare it for accurate analysis, the following data cleaning procedures were performed:
 1. Removed duplicate records to eliminate redundancy and maintain data integrity.
 2. Eliminated blank or empty rows to ensure consistency and avoid errors during analysis.
 3. Validated and corrected data types for each column to match the expected format, enabling accurate computations and visualizations.

### Data processing
As part of the data preparation process, key time-based features were derived from the Order_Date column to facilitate temporal analysis:

1. Month Extraction:
 Extracted the full month name from the Order_Date column using the formula:
 =TEXT(cell_reference, "mmmm")
 This allows for monthly trend analysis and seasonality insights.

2. Year Extraction:
 Extracted the year from the Order_Date column using the formula:
 =TEXT(cell_reference, "yyyy")
 This enables year-over-year comparison and time series aggregation.

### data analysis using pivot table 
1. Sales by Sub-category :
   It helps to analyze which sub-categories are underperforming and which products are most popular among customer
   in each sub-category.

   ![image](https://github.com/jyoti7770/sales_data_analysis/blob/main/analysis%20sales%20by%20sub-category.png)
   
2. Year wise Sales:
   helps to analyze Sales growth trends, it shows whether sales are increasing,decreasing,or constant over the year.

   ![image](https://github.com/jyoti7770/sales_data_analysis/blob/main/year%20wise%20sales.png)
3. Month wise sales:
   helps to analyze monthly sales growth trends

    ![image](https://github.com/jyoti7770/sales_data_analysis/blob/main/monthly%20sales.png)
4. Profit by top 5 customers:
   helps to know who is the top 5 customers contributing in business profits

   ![image](https://github.com/jyoti7770/sales_data_analysis/blob/main/profit%20by%20top%205%20customer.png)
5. Sales and Profit by top 5 state:
    it is not necessary that more sales means more profit ,sometimes company faces loss also.so this analysis helps to know which state is performing
   well in both sales and profit.

   ![image](https://github.com/jyoti7770/sales_data_analysis/blob/main/sales%20and%20profit%20by%20state.png)
### Sales Analysis Dashboard 
![image](https://github.com/jyoti7770/sales_data_analysis/blob/main/sales%20analysis%20dashboard.png)
### Insights
1. In Sub-Category we can see that Phones,Chairs,Storage,Tables ,Binders and Machines are perfroming well
   and Supplies,Arts,Envelops,Labels and Fasteners are underperforming.
2. If we see line chart in dashboard it shows sales are growing year over year .
3. Some months sales are perfoming well that is March,September and November and remaining months its little decreases.
4. Our 5 top customers are Tumaran Chand,Raymond Buch,Sanjit Chand,Hunter Lopez and Adrain barton.
5. We can see that California,New York,Washington are performing well by sales and also giving good profit
   but Pennsylvania and Taxax are perfroming well in sales but they provided loss to business.
 ### Concluison 
 Based on the sales analysis, the company can significantly enhance its business growth by optimizing its product strategy. It is recommended to increase the production of high-demand products such as Phones, Chairs, Storage units, Tables, and Binders, while discontinuing or reducing the manufacturing of low-demand items. This targeted approach will streamline operations and improve overall efficiency.
Additionally, implementing seasonal promotional offers during peak sales months can help boost revenue and customer engagement. These offers can incentivize bulk purchases and attract new customers, thereby increasing market reach.
From a regional perspective, it is advisable for the company to cease selling Furniture, Office Supplies, and Technology products in Pennsylvania, and Furniture and Supplies in Texas, as these categories show poor performance in those areas. Instead, the company should focus on expanding these categories in regions or countries where they are in higher demand, maximizing profitability and reducing potential losses.
By aligning production and sales efforts with market demand and regional trends, the company can enhance its productivity, profitability, and long-term sustainability.
