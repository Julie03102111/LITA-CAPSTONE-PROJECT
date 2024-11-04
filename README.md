# LITA-CAPSTONE-PROJECT

### PROJECT OVERVIEW
---

Payless-Superstore is a retail outlet based in Nigeria. The superstore specializes in selling clothing for both the male and the female genders, the clothing include but not limited to items such as; hat, shirts, shoes jackets, socks etc and also another segment of the store who deals with television subscriptions. This summer, the company hired me as a Business Data Analyst at their Headquarter office located at Victoria Island Lagos. My role is analyzing the sales performance of the superstore and my goal is to help them enhance their business growth and profitability.

### Table of Content
---
-  [PROJECT OVERVIEW](#project-overview)
-  [DATASET](#dataset)
-  [Tools Used](#tools-used)
-  [Data Cleaning & Preparation](#data-cleaning-&-preparation)
-  [Data Collection](#data-collection)
-  [Exploratory Data Analysis](#exploratory-data-analysis)
-  [Data Analysis](#data-analysis)
-  [Business Questions](business-questions)
-  [Basic statistics about the dataset](#basic-statistics-about-the-dataset)
-  [DASHBOARD VISUALIZATION](#dashboard-visualization)
-  [Sales by Region and Product](#sales-by-region-and-product)


### DATASET:
---
The original dataset was given containing two datasets, SalesData and CustomerData. It contains 9922 & 33788 sales transactions respectively that occurred from 2022 to 2024. This dataset encompasses a wide range of information, including order specifics, geographical data, and product-related data. There are no missing values or any irrelevant data types and values. During the inspection process, a duplicate entry was identified and removed for accuracy. For those who are interested in viewing or downloading the refined dataset, it is available in my GitHub repository.

### Tools Used
---
- Microsoft Excel [Download Here](https://docs.google.com/spreadsheets/d/1pBkPSQL5GJ4Z-BdTWzV-SafvD2h02SYQ/edit?usp=drive_link&ouid=105309729759290755400&rtpof=true&sd=true)
  1.  For Data cleaning
  2.  For Data Analysis
  3.  For Data visualization
- SQL Structure Query Language for Querying of Data [Download Here](https://drive.google.com/file/d/19o9r7MTfYD72-apw42q1FrbDLCVhy5_W/view?usp=drive_link)
- SQL Structure Query Language [Download Here](https://drive.google.com/file/d/1YTbBCZ1RswNSX8utgmh3UnSughupBhF5/view?usp=drive_link)
- Github for Portfolio building

### Data Cleaning & Preparation
---
In the initial phase of data cleaning and preparation the following actions were performed
  1.  Data loading & inspection
  2.  Handling of missing variables
  3.  Data cleaning and formating

## Data Collection
The dataset for this analysis was provided by the Capstone Initiative, the organization supplied the datasets for project. The data was provided in CSV format, making it accessible for analysis.

### Exploratory Data Analysis
---
EDA involves exploring the data to answer questions about the data such as;
-  What is the total Sales Revenue.
-  What is the monthly sales trend.
-  What are the top selling products.
-  What is the total sales for each product category.
-  What is the number of sales transactions in each region.
-  Calculate the percentage of total sales contributed by each region.
-  Identify products with no sales in the last quarter.


### Data Analysis
---
This is where we include some basic line codes or queries or even some of the DAX Expressions used during my analysis.

```SQL
Select *From Table [dbo].[LITA Capstone Dataset SQL 2]
where Condition = true
```

### Business Questions:
---
1.  Which Region and states are generating the highest revenue?
2.  Which product category is both the best-selling and the most profitable?
3.  Which product sub-categories and specific products are top performers as well as those that are underperforming?
4.  Are there products that are frequently bought together?
5.  Which customer segment is bringing in the most profit?
6.  How has the company's performance trended over recent months?
7.  What are the KPIs?

### Basic statistics about the dataset:
---
-  Total Sales Clothing: N2,101,090
-  Total Sales Subscription: N67,540,175.
-  Total Product Count Clothing:274,179
-  Total Subscription Count: 182,710

### DASHBOARD VISUALIZATION
<img width="635" alt="image" src="https://github.com/user-attachments/assets/86218a59-1dc7-4975-8f68-1092956526d5">
<img width="629" alt="image" src="https://github.com/user-attachments/assets/8acb7876-12f9-43d2-8077-06238d7a4f42">


### Sales by Region and Product:
---
-  In the Clothing section the South region boasted the highest revenue, with sales amounting to N928k which constitute 44.2% of the total sales, followed by the East region with sales of N486kat 23.14%, in the third position is North Region with a total sale of N387k which is 18,24% of the total sales and lastly at the bottom is the West Region with a total sale of N300k with 14.29%.
-  Within the Television subscription section of the superstore the East Region has the highest sales revenue with a total of N17m which is 25.08% of the total revenue generated followed by South Region at N16.89m at 25.02%, West at N16.86m at 24.96% & North N16.82m at 24.94% respectively the analysis also highlighted some of top selling products which contributes to the major revenue of the company and those at the bottom line, Therefore, the company should focus on marketing efforts and optimizing inventory in those regions to further increase sales.

<img width="497" alt="image" src="https://github.com/user-attachments/assets/40257afd-bbf4-4ba1-a82c-01469d2959fc">
<img width="499" alt="image" src="https://github.com/user-attachments/assets/41018503-648c-4cb2-b0c6-f06ef08031ed">

### Sales Trend Analysis
---
-  In the Television Subscription Section the Basic category emerged as the leading performing product in both sales and revenue generation with total revenue of N33.8m and 16,922 quantity sold thi makes the Basic subscription category to stand out with impressive sales and Revenue, this is followed by the premium and standard category with total sales revenue of N16.9m and 8,446 & 8420 quantities sold respectively. 
-  On the other hand, the Clothing Section showcased some significant sales but had a notably lower sales margin when compared to the Subscription Section. Within the Clothing category, the Shoes displayed decent sales and increased revenue of N613.4k, Shirt N485.6k, Hat N316.2k, Gloves N296.9k, Jacket N206.2k and Socks N180.8k.
-  Additionally, both Premium and Standard subscription type had lower sales turnover when compared to the Basic. These observations raise concerns, suggesting potential issues with the subscription duration and the pricing strategy, especially for the premium and standard categories.

<img width="533" alt="image" src="https://github.com/user-attachments/assets/8aa177f8-d0ec-42d9-b516-9fea5a7786f4">

<img width="550" alt="image" src="https://github.com/user-attachments/assets/de1caa43-c1d1-4771-ac44-a46a0a2e939b">


### Recommendations
1.	Customer Drive: To boost satisfaction and sales, enhance the shopping experience for the clothing section the company should enhance brands are in line with the fashion trend and also offer personalized promotions, loyalty rewards, and targeted marketing to further increase their engagement and spending, driving overall growth.
2.	Sales optimization: Engage more in advertising and other sales strategies across all cities especially for those products that mark the highest revenue generation and also for those at bottom line a market survey could be carried out to get the taste preference of customers as regards to those product and possible upgrade will improve the market for consistent revenue growth. 
3.	Region comparison: Focus on increasing sales initiatives in Regions like the West & Northern regions as these regions’ sales can still be boosted and  sales  growth increased. Implement targeted marketing campaigns and promotions tailored to local preferences to maximize sales opportunities throughout the regions.
4.	Customer satisfaction analysis: To sustain growth and boost loyalty, focus on exceeding the expectations of customers. Consistently deliver exceptional service to foster loyalty, increase retention, and leverage positive word-of-mouth to attract new customers, strengthening our customer base and driving long-term profitability.


### Conclusion:
Payless-Superstores faces slow sales turnover which is unstable with marginal sales increase. Our recommendations focus on boosting revenue through enhanced customer satisfaction, optimized pricing strategies, and leveraging popular product and subscription type. Implementing these strategies aims to improve financial performance and ensure sustainable profitability.

If you have any questions regarding this project, you can email me at juliechukwu16@gmail.com, or connect me on https://www.linkedin.com/in/juliet-ejikeme-aca
