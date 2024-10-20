# Business Analysis Project

## Project Overview
The primary objective of this project is to conduct a comprehensive analysis of the company's sales performance. The analysis aims to identify key insights, such as the company's best-selling stores and products, sales trends, customer segmentation, and customers' purchasing behavior from January 2021 to March 2023. Additionally, the project will explore the effectiveness of different payment methods in driving sales. These insights will empower stakeholders to make data-driven decisions, allowing the company to leverage its top-performing stores and products to boost revenue. Furthermore, strategies will be formulated to improve the sales of underperforming products and overall sales performance. Ultimately, this analysis will provide actionable recommendations to help the company achieve its revenue targets.

## Data Source
The data used for this project was sourced from the Kaggle repository website. The data set encompasses various sales metrics vital for understanding the company's business landscape.
The columns contained in the data included:
- Invoice number
- Customer ID
- Category
- Quantity
- Price
- Invoice date
- Shopping mall
- Gender
- Customer Age
- Payment Method

Click on the link to interact with the [Analysis Dashboard](https://app.powerbi.com/groups/me/reports/9ec9139f-7ecf-4c44-a5fa-22ebabf398a8/ReportSection9139d83852a68818cb3c?experience=power-bi)

## Softwares Used

1) Microsoft Excel: Employed for data cleaning and transformation to prepare the data for analysis.

2) Power Query Editor: Utilized for further data cleaning and transformation, enabling a streamlined approach to handle large datasets effectively.

3) Power BI: Leveraged to create interactive visualizations and dashboards, facilitating the extraction and presentation of key insights from the data.

## Data Cleaning and Transformation

- The first step involved converting the entire dataset into a table format. This was accomplished using the keyboard shortcuts Ctrl + A followed by Ctrl + T. This transformation allows for easier navigation, filtering, and analysis.

- To ensure the integrity of the dataset, duplicate entries across all columns were removed. This was executed using Excel’s "Remove Duplicates" feature, which ensured that unique and relevant data were included in the analysis.

- Unnecessary spaces within the dataset were eliminated using the TRIM function in Excel. This step is crucial as it enhances data quality by ensuring that no extraneous whitespace interferes with analysis.

- Data accuracy was further improved by addressing misspellings. The "Find and Replace" function in both Excel and Power Query was employed to correct erroneous entries, ensuring consistency in data representation.

- VLOOKUP was used to merge the two Excel worksheets containing the data into a single sheet while referencing the Customer ID in both sheets.

- Blank rows in the dataset were deleted to maintain data integrity. This action prevents gaps in the data that could lead to misleading analysis or results.

- The first row of the dataset was transformed to create properly titled and capitalized headers for each column. This step enhances clarity and readability, making it easier to understand the data structure.

- To better analyze customer behavior, I utilized the "Conditional Column" feature in Power Query. This feature enabled me to group customers into various Age brackets, facilitating more detailed insights into purchasing patterns.

- Using Power Query DAX, I calculated the business's Year-over-Year (YoY) sales. This measure provides insights into sales growth over the specified period, allowing for trend analysis.

- To determine the actual sales for each product, I employed the SUMX DAX formula. This calculation multiplies the "Unit Price" column by the "Quantity" column, enabling a clear assessment of revenue generated by each product.

- All columns in the dataset were formatted to accurately reflect their contents. This step ensures standardization across the dataset, making it easier to analyze and interpret the information.

## Exploratory Data Analysis (EDA)

After thoroughly cleaning and transforming the dataset into a usable format, I undertook a comprehensive Exploratory Data Analysis (EDA) to gain an in-depth understanding of the data and derive actionable business insights. The following key business questions guided my analysis and informed the visualizations I created:

- What is the Total Sales?
- Which Store generated the highest Sales?
- Which Product(s) generated the highest Sales?
- Which Payment Method did customers use most frequently?
- What are the Customer's age groups?
- Between Male and Female customers, who made the highest purchases?
- What is the Sales trend?
- What is the Year-over-Year (YoY) Sales?

## Data Analysis

To enhance navigation and comprehension of the insights derived from the data, I structured the visualizations into four distinct dashboards, employing various and appropriate visualizations to ensure clarity and facilitate understanding.

#### The following summarizes the general insights obtained from the analysis:

1) Total Sales: Between January 2021- March 2023, the company generated $68.54 million in Sales. The analysis indicates a consistent upward trajectory in yearly sales.

2) Quantity Sold: A total of 298,712 products were sold during this period, reflecting strong customer engagement and product demand.

3) Sales by Store Location: The highest sales were recorded at the following store locations: Mall of Istanbul; $13.85 million (20%), Kanyon; $13.70 million (19.98%) and Metrocity; $10.24 million (14.9%)

5) Sales by Product Categories: The analysis revealed that the following categories generated the most revenue: Clothing; $31.06 million (45.3%), Shoes; $18.13 million (26.45%) and Technology; $15.77 million (23%)

6) Sales Trend: Analysis of the sales trend indicated that Q1 is the peak selling period for the business, suggesting a seasonal pattern in purchasing behavior.

7) Sales by Payment Methods: Among the three payment methods analyzed, Cash was the most commonly used, followed by Credit Card and Debit Card, with total sales of Cash; $30.7 million, Credit Card; $24.04 million, and Debit Card; $13.79 million.

8) Sales by Gender: The data indicated that sales were higher among Female customers, generating $40.92 million (59.71%), compared to Male customers, who contributed $27.61 million (40.29%).

9) Sales by Age Groups: The customer base ranged in age from 20 to 70 years, with patronage being relatively evenly distributed across different age brackets.

## Recommendations

- Since Q1 is identified as the peak selling period, consider launching targeted marketing campaigns during this time. Promotions or seasonal offers can maximize sales and capitalize on increased patronage.

- Conduct a thorough analysis of store locations, especially Mall of Istanbul, Kanyon, and Metrocity. Identify the factors contributing to their success and explore opportunities for replicating those strategies in lower-performing locations.

- From the analysis, Clothing is the top-selling category, consider expanding the clothing line with new styles or exclusive collections. Additionally, analyzing customer preferences in Shoes and Technology can help tailor inventory to meet demand and boost sales.

- With female customers generating a significantly higher percentage of sales, develop marketing strategies that specifically target this demographic. This could include personalized promotions, collaborations with female influencers, or loyalty programs designed for women. Also, a similar approach for male customers should be implemented to encourage more patronage from the demographic.

- While Cash remains the most popular Payment Method, increasing the availability of digital payment options like Debit and Credit cards could boost overall sales.

- To better understand customer preferences and improve product offerings, establish mechanisms for collecting customer feedback. Surveys, suggestion boxes, or online reviews can provide valuable insights to inform future business decisions and enhance customer satisfaction.

- Use automated and interactive dashboards to continuously monitor real-time overall sales performance of the company, and tweak sales strategies when necessary to improve the company's sales.

## Conclusion

This project has shown the efficacy of using Data Analysis to derive real-time business insights and make strategic data-driven decisions and recommendations that would enable the company to increase its sales, and meet the organization's revenue targets.
