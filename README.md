# Demand-Forecasting-Project
# Objective
The objective of this project is to analyze business sales performance by examining revenue trends, evaluating product return patterns, and forecasting future product demand. The project aims to provide actionable insights that help improve decision-making, optimize inventory management, reduce return rates, and enhance overall business profitability.
# Problem Statement
Organizations generate large volumes of sales and transaction data, but converting this data into meaningful business insights remains a challenge. Understanding revenue performance, identifying products with high return rates, and accurately predicting future product demand are critical for effective business planning. Without proper analysis, businesses may face inventory shortages, excess stock, reduced profitability, and increased operational costs. This project addresses these challenges by analyzing revenue and product return data and developing a predictive model to estimate product units sold for the upcoming month, enabling data-driven business decisions.
# Key Features
**DAta Processing**: Handles nulls, duplicates.<br>
**Data Analytics**
        * **Revenue Analysis**: Analysed Category wise Revenue, Product Wise Revenue, Location Wise Revenue and Extracted Top Revenue producing countries and Least                                 Revenue producing Countries.
        * **Return Analysis**: Analysed which Platforms, Countries, and Products are giving high returns and lowest no.of returns. And Visualised Yearly returns.
        * **Time Series Analysis**: Decomposed Revenue to observe Trend and Seasonality.
        * **Predicting Last Month Of Data**: Predicted Last Month Demand to check the accuracy of the model using Prophet model. and Checked the accuracy of the                                                 model using MAPE and RMSE. and Accuracy is very good. The predicted values are very close to the actual values.
**Predicted Next Month Demand**: Predicted One Month Demand for each Inventory Item. and checked the Accuracy using MAE, RMSE, and WMAPE metrics.
# Results & Insights
* Vitamin categories are given more revenue.Because under vitamin and mineral category we had 3 products. but for other categories we had only 1 or 2 products.
* In canada and USA we have more returns from Amazon platform.
* There is stable trend till mid 2021 and after that trend has increased, and then recovered in 2023 again.In mid 2023 there is stable trend again.
* 2 Products require more safety stock for next month as the demand will be high than other products.
* The forecasting results support data-driven inventory management by helping maintain optimal stock levels and minimizing excess inventory costs.
        
