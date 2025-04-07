## Chapter 2: Intermediate Logical Functions
You’ll identify your ideal customer profile using logical functions and create targeted marketing strategies. You’ll explore the concept of customer segmentation and gain the skills to maximize customer success, increase revenue and boost business growth. You’ll utilize functions such as Nested IFs, SWITCH, and COUNTIFS.

## Assignments
### 2.1 - Swapping values with SWITCH
- Senior management is looking to identify upsell opportunities. Upsell means getting non-paying accounts to convert to paying accounts.
- In this dataset, the Subscription Type has four tiers. From worst to best, they are Basic, Premium, Business, and Enterprise.
- We can use a SWITCH() statement to easily transform these strings into numerical values, that can help us provide insights to the senior management team.
![Formatting Example](https://github.com/haileyrthomas01/datacamp-excel-fundamentals/blob/main/data-analysis-in-excel/screenshots/Screenshot%202025-04-07%20154949.png)

### 2.2 - Nesting logical functions
- In the last exercise, we combined functions with SWITCH() to find the Total Upsell $, which found how much money Bananas could have made had all their customers been paying.
- While this is a good theoretical exercise, it does not address which accounts our customer success team should target for upsell opportunities.
- Let's continue to build out some helpful functions with IF(), IFS(), and CONCAT().
![Formatting Example](https://github.com/haileyrthomas01/datacamp-excel-fundamentals/blob/main/data-analysis-in-excel/screenshots/Screenshot%202025-04-07%20155039.png)
![Formatting Example](https://github.com/haileyrthomas01/datacamp-excel-fundamentals/blob/main/data-analysis-in-excel/screenshots/Screenshot%202025-04-07%20155047.png)

### 2.3 - Using COUNTIF and SUMIF
- So far, we've used logical functions and intermediate techniques to create categories of data, but what if we want to aggregate data by certain categories.
- In chapter 1 we used PivotTables to do this, but now we'll focus on using logical aggregation functions.
- COUNTIF and SUMIF are logical statements that will count or sum a specified range within a given criteria. We can use these to aggregate the data by Sales Month and gain some good insight on month-to-month trends.
![Formatting Example](https://github.com/haileyrthomas01/datacamp-excel-fundamentals/blob/main/data-analysis-in-excel/screenshots/Screenshot%202025-04-07%20160904.png)


### 2.4 - COUNTIFS and SUMIFS
- Previously we used COUNTIF() and SUMIF() to aggregate data into groups by Sales Month. We built an interesting trend analysis that lead to more questions.
- COUNTIFS() and SUMIFS() are even more powerful than the previous functions we learned because of their ability to validate multiple logical arguments (hence the S) within the same function.
- We can use these functions to further segment our sales data and perhaps find some answers.
![Formatting Example](https://github.com/haileyrthomas01/datacamp-excel-fundamentals/blob/main/data-analysis-in-excel/screenshots/Screenshot%202025-04-07%20160734.png)
