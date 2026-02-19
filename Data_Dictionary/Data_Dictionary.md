  📘 Data Dictionary

Dataset Name: Superstore Sales
Project: Retail Sales Data Cleaning & Business Insights


🧾 Order Information
| Column Name | Data Type | Description                                   | Business Relevance       |
| ----------- | --------- | --------------------------------------------- | ------------------------ |
| Row ID      | Integer   | Unique row identifier                         | Used for indexing        |
| Order ID    | String    | Unique order transaction ID                   | Tracks individual orders |
| Order Date  | Date      | Date when order was placed                    | Sales trend analysis     |
| Ship Date   | Date      | Date when order was shipped                   | Delivery performance     |
| Ship Mode   | String    | Shipping method (First Class, Standard, etc.) | Logistics efficiency     |


👤 Customer Information
| Column Name   | Data Type   | Description                                         | Business Relevance             |
| ------------- | ----------- | --------------------------------------------------- | ------------------------------ |
| Customer ID   | String      | Unique identifier for each customer                 | Customer tracking              |
| Customer Name | String      | Name of customer                                    | Personal identification        |
| Segment       | Categorical | Customer segment (Consumer, Corporate, Home Office) | Customer segmentation strategy |


🌍 Geographic Information
| Column Name | Data Type   | Description           | Business Relevance       |
| ----------- | ----------- | --------------------- | ------------------------ |
| Country     | String      | Country of customer   | Regional analysis        |
| City        | String      | City of customer      | Local sales analysis     |
| State       | String      | State of customer     | Geographic performance   |
| Postal Code | String      | ZIP/Postal code       | Delivery optimization    |
| Region      | Categorical | Region classification | Regional profit analysis |


📦 Product Information
| Column Name  | Data Type   | Description                                               | Business Relevance        |
| ------------ | ----------- | --------------------------------------------------------- | ------------------------- |
| Product ID   | String      | Unique product identifier                                 | Product tracking          |
| Category     | Categorical | Product category (Furniture, Office Supplies, Technology) | Category-level analysis   |
| Sub-Category | Categorical | Product sub-category                                      | Detailed product insights |
| Product Name | String      | Name of product                                           | Product identification    |


💰 Sales & Financial Information
| Column Name | Data Type | Description                  | Business Relevance      |
| ----------- | --------- | ---------------------------- | ----------------------- |
| Sales       | Float     | Total revenue from the order | Revenue KPI             |
| Quantity    | Integer   | Number of units sold         | Sales volume            |
| Discount    | Float     | Discount applied (0–1 scale) | Pricing strategy impact |
| Profit      | Float     | Profit earned from the order | Profitability analysis  |


