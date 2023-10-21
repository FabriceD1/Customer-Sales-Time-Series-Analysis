# Customer-Sales-Time-Series-Analysis
The dataset used for the time series analysis encompasses sales and customer information, providing valuable insights into the shopping behavior and preferences of a retail business. It consists of two primary sections: Sales Data and Customer Data.

About Dataset
Sales data description:
- Invoice no : Invoice identification number.
- Customer id : Customer identification number.
- Category : General item categorization groups
- Quantity : Number of products
- Price : Price of each product.
- Invoice date : Date of purchase.
- Shopping mall : Shopping mall loaction.

Customer data description:
- Customer id : Customer identification number.
- Gender : Gender( Male/Female)
- Age : Customer age.
- Payment method : Payment used by customer

### This repository contains time series decomposition plots with interpretations for a dataset. The time series has been broken down into its key components, including the Original, Trend, Seasonal, and Residual components. Below is an interpretation of each of these components:

![image](https://github.com/FabriceD1/Customer-Sales-Time-Series-Analysis/assets/90782496/bdbaa04e-e926-4cbc-808a-e2fe41d71ac9)


## Original
- This plot shows the actual data before decomposition.
- It starts at a value close to 2.5e6 and stays relatively stable until around 2022-10, where there is a noticeable drop.

## Trend
- This represents the underlying trend in the data.
- Similar to the original series, the trend is relatively flat until around 2022-10, where there's a decline. This indicates that the long-term direction of the series is downwards starting from that point.

## Seasonal
- This plot showcases the seasonal fluctuations in the data.
- There's a consistent pattern repeating over time, with peaks and troughs at regular intervals. This indicates the presence of seasonality in the data.

## Residual
- This captures the remaining unexplained variability in the data after accounting for the trend and seasonality.
- The residuals seem to be centered around zero, with some fluctuations. This suggests that the decomposition has done a reasonably good job of extracting the trend and seasonality, leaving behind the random fluctuations in the residuals.

In summary:
- The time series has a clear seasonality, as evident from the seasonal plot.
- The underlying trend was stable until 2022-10, after which there's a downward trend.
- The residuals show the random fluctuations in the series after removing the trend and seasonality.

These decomposition plots and their interpretations provide valuable insights into the patterns and trends in the time series data. They can be useful for forecasting, trend analysis, and understanding the underlying structure of the dataset.

## Further Exploration in Tableau Public

We have also merged and uploaded this dataset to Tableau Public for more in-depth exploration and analysis. You can access the merged dataset and interact with it in Tableau Public by following these link to Tableau Public 

## Sales Analysis
![image](https://github.com/FabriceD1/Customer-Sales-Time-Series-Analysis/assets/90782496/49fcb5a3-541b-4348-a5f4-3abc31f8f8d7)

https://public.tableau.com/app/profile/fabrice.delice/viz/TableauProject_Customer_Sales/SalesAnalysisDashboard 

## Revenue insight
![image](https://github.com/FabriceD1/Customer-Sales-Time-Series-Analysis/assets/90782496/3bc97bd9-1fb5-4a09-b887-9c1dd1fd4748)

https://public.tableau.com/app/profile/fabrice.delice/viz/TableauProject_Revenue_Sales/RevenueInsightDashboard 

In Tableau Public, you can create custom visualizations, perform additional analyses, and gain deeper insights into the data.

