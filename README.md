# LITA-CAPSTONE-PROJECT

### PROJECT OVERVIEW
---

Payless-Superstore is a retail outlet based in Nigeria. The superstore specializes in selling clothing for both the male and the female genders, the clothing include but not limited to items such as; hat, shirts, shoes jackets, socks etc and also another segment of the store who deals with television subscriptions. This summer, the company hired me as a Business Data Analyst at their Headquarter office located at Victoria Island Lagos. My role is analyzing the sales performance of the superstore and my goal is to help them enhance their business growth and profitability.

### Table of Content
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
Total Sales Clothing: N67,540,175
Total Sales Subscription: N2,101,090.
Total Product Count Clothing:167,500
Total Subscription Count: 131,250

### DASHBOARD VISUALIZATION
<img width="625" alt="image" src="https://github.com/user-attachments/assets/d1624dae-27b7-4991-8e2c-d5c140c2d557">
<img width="633" alt="image" src="https://github.com/user-attachments/assets/7b13335d-ae6f-4f49-9985-ec419f9cfc23">

### Sales by Region and Product:
---
-  In the Clothing section the South region boasted the highest revenue, with sales amounting to N4.9m which constitute 44.2% of the total sales, followed by the East region with sales of N2.5m at 23.14%, in the third position is North Region with a total sale of N2m which is 18,24% of the total sales and lastly at the bottom is the West Region with a total sale of N1.6m with 14.29%. Within the
-  Television subscription section of the superstore the South Region has the highest sales revenue with a total of N37.6m which is 25.08% of the total revenue generated followed by West Region at N37.5m at 25.02%,  East and North at N37.4m at 24.96% a& 24.94% respectively the analysis also highlighted some of top selling products which contributes to the major revenue of the company and those at the bottom line, Therefore, the company should focus on marketing efforts and optimizing inventory in those regions to further increase sales.

<img width="424" alt="image" src="https://github.com/user-attachments/assets/056c066e-ed74-4a57-81fe-e52196d3cd50">
<img width="458" alt="image" src="https://github.com/user-attachments/assets/c65a4be8-e65c-429c-a71d-f8d675e4e34b">

### Sales Trend Analysis
---
The Television Subscription Section category emerged as the leading performer in both sales and revenue generation. Within this category, the Basic subscription category stood out with impressive sales and Revenue figure of N38m. On the other hand, the Clothing Section showcased some significant sales but had a notably lower sales margin when compared to the Subscription Section. Within the Clothing category, the Shoes displayed decent sales and increased revenue. Additionally, both Premium and Standard subscription type had lower sales turnover when compared to the Basic. These observations raise concerns, suggesting potential issues with the subscription duration and the pricing strategy, especially for the premium and standard categories.

<img width="412" alt="image" src="https://github.com/user-attachments/assets/5f9fe740-34bb-47f3-a4ad-f311ccae165f">

 <img width="499" alt="image" src="https://github.com/user-attachments/assets/29ba65ab-a8d7-4213-8ffe-0ef29e27eb29">

Recommendations
1.	Customer Drive: To boost satisfaction and sales, enhance the shopping experience for the clothing section the company should enhance brands are in line with the fashion trend and also offer personalized promotions, loyalty rewards, and targeted marketing to further increase their engagement and spending, driving overall growth.
2.	Sales optimization: Engage more in advertising and other sales strategies across all cities especially for those products that mark the highest revenue generation and also for those at bottom line a market survey could be carried out to get the taste preference of customers as regards to those product and possible upgrade will improve the market for consistent revenue growth. 
3.	Region comparison: Focus on increasing sales initiatives in Regions like the West & Northern regions as these regions’ sales can still be boosted and  sales  growth increased. Implement targeted marketing campaigns and promotions tailored to local preferences to maximize sales opportunities throughout the regions.
4.	Customer satisfaction analysis: To sustain growth and boost loyalty, focus on exceeding the expectations of customers. Consistently deliver exceptional service to foster loyalty, increase retention, and leverage positive word-of-mouth to attract new customers, strengthening our customer base and driving long-term profitability.
