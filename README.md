# Sales-Power-Bi-data-Visualization

![sales-data-blog-header-small](https://github.com/corleonethe3rd/Sales-Power-Bi-data-Visualization/assets/73728752/6c0333f3-0083-4a5e-8933-41f52d2d4e6e)


## Introduction

This project aims to provide comprehensive data visualization solutions for analyzing sales data during the months of April and May. By leveraging Power BI's robust features, we enable our client to gain valuable insights, make data-driven decisions, and optimize their sales strategies.

## Project Objectives and Goals
Performance Evaluation: Assessing the performance of sales over the months of April and May allows the company to gauge the effectiveness of its sales strategies.
Decision Support: The insights derived from the analysis act as a foundation for informed decision-making. Understanding sales trends, patterns, and key metrics empowers the management team to make data-driven decisions that can optimize resource allocation, marketing efforts, and overall sales strategies.

Identifying Opportunities and Challenges: By closely examining sales data, the analysis aims to uncover opportunities for growth and areas that may pose challenges. This includes identifying potential markets, customer segments, or products that may need additional focus, as well as recognizing factors that may have contributed to any downturns.

Month-over-Month Comparison: Comparing sales data between April and May provides a valuable perspective on growth or contraction. This comparison allows the company to identify seasonal variations, evaluate the impact of specific initiatives, and understand the overall trajectory of sales performance.

Calculating Total Revenue,Average Revenue per Order,Total Order, Revenue Generated by company,Revenue generated by Category

## Data Sourcing
The following Data sheet below was Provided by Promise Chinonso;
- Categories
- customers
- Employees
- Order_details
- Order
- Products
- Shippers

## Data Transformation
Data cleaning and transformation was carried out using Power Query.
After scrutinizing all the columns, they were found to be valid and devoid of empty cells and errors.

I created the following measures below;
- Average Revenue/Order using the dax function (DIVIDE('order_details'[Revenue],order_details[Total Unique Orders],""))
- Total Revenue using the dax function SUM(order_details[Sales Amount])
- Total Unique Orders using the dax function COUNTROWS(VALUES('order_details'[orderID]))

## Tool Used

- Microsoft Excel
- Microsoft Power Bi

## Skills/Concepts Demonstrated

The following skills and concepts were used:
- Data cleaning 
- Dax Functions
- Chart Visualization
- Data Analysis
- Generating Insights

## Data Modelling

From the sheets provided, relationships where created between the tables using thier primary keys
![Screenshot 2023-12-27 222914](https://github.com/corleonethe3rd/Sales-Data-Analysis/assets/73728752/416c2a9b-4751-43ae-ac0f-076bf4f436c9)

## Analysis and Visualization

![Screenshot 2023-12-27 224636](https://github.com/corleonethe3rd/Sales-Data-Analysis/assets/73728752/1113540d-29d6-4a22-9793-cd85968fd900)

Thee following Insights were discovered;
1. A total Revenue of $1.35M
2. An Average Revenue per Order of $1.65K
3. Top 5 products by Revenue
4. From Revenue by Month and Day, the 5th of May had the most revenue of $7901.5
5. The Highest Revenue Generated By Company United Package Comapany which generated $17.91k
6. The Revenue Generated by the Highest employee was by Robert King in which he Genrated $5192.8

## Recommendations

#### Optimize Product Portfolio:
Focus on the top 5 products that contribute the most to revenue. Consider strategies to promote these products further or explore opportunities to expand the product line based on similar successful products.

#### Strategic Marketing on Peak Days:
Given the insight into the highest revenue day (May 5th), consider implementing targeted marketing campaigns or promotions on similar days in the future to capitalize on peak sales periods.

#### Company-Wide Best Practices:
Analyze the practices of the United Package Company, the top revenue-generating company, to identify best practices that can be implemented across the organization.

#### Employee Recognition and Training:
Recognize and reward high-performing employees like Robert King. Additionally, consider providing training programs or sharing best practices among the sales team to enhance overall performance.

#### Continuous Monitoring and Adaptation:
Implement a system for continuous monitoring of sales data, allowing for quick adaptation to changing trends or identifying emerging opportunities. Regularly update the analysis to stay informed about the dynamic sales landscape.

## Conclusion

The data visualization and analysis conducted on the sales data for the months of April and May have provided valuable insights into the company's performance.From The Revenue by Month and Day , Understanding such peaks can help in optimizing promotions or targeted marketing on specific days. Also, Recognizing high-performing employees can inform incentive programs or training initiatives.
