# AMAZON WEB EXPLORATORY DATA ANALYSIS
This dataset contains data from fictious B2B SaaS sales transaction from [Kaggle](https://www.kaggle.com/datasets/nnthanh101/aws-saas-sales), and therefore does not represent actual AWS data.

## Background
Amazon Web Services (AWS) is a cloud service launched by Amazon in 2006, designed to provide solutions to customers facing challenges in data storage and security. Through AWS, Amazon offers globally accessible data centers, enabling users to manage and store information with enhanced flexibility and security. One of the flagship services provided is Software as a Service (SaaS).

In the SaaS industry, Amazon faces the need to remain competitive and adapt to market changes. The success of a SaaS business heavily relies on customer base growth, recurring revenue, and effective marketing strategies to retain and attract new customers. Therefore, a deep understanding of the factors influencing sales performance becomes crucial for Amazon.

As data analysts, we can explore product sales based on regions and industry segmentation to identify trends and customer preferences. This analysis will utilize SaaS sales data to uncover significant patterns in sales performance, providing valuable insights for improvement strategies, and future product development.

## Business Problem
The issue of negative profit in SaaS product sales is crucial for the company, as it can have a direct impact on financial health and long-term sustainability. By addressing this issue, the company, not only improve the profitability of its SaaS products, but also gain strategic insights that can be applied to sales, drive growth, and strengthen its competitive position.

## Goals
Analyzing sales performance, product distribution, monthly trends, profit differences, demand, and discount application for AWS SaaS products to identify the causes of negative profit and formulate effective improvement strategies.

## Insight
1. There are 11 SaaS products that had negative profit transactions during the analysis period from January 2020 to December 2023, with Marketing Suite being the only product that experienced a negative profit of -3,472.56, or -1.21 percent of the total profit.
2. The latter months of each year (such as November-December) tend to have higher order volume and sales, which may indicate an increase in year-end demand or seasonal purchasing behavior.
3. Monthly profit fluctuates with several peaks and declines, but the overall trend shows growth, despite two negative profits in July 2020 and January 2021.
4. By region, APJ experienced a negative profit of -9,314.27, while the other regions had positive profits.
5. Based on industry by each region, the sectors contributing to the highest negative profits are only in the APJ region, with the highest being Tech and Healthcare.
6. Regional and industry differences play a significant role in the variation of profit for SaaS products.
7. A high discount (20 percent) is frequently offered, especially during months with high sales. However, profits are not always high despite the substantial discounts. In some months with large discounts, such as January 2021 and July 2020, profits showed negative figures. This may indicate that large discounts can significantly reduce profitability.
8. The implementation of discounts has a significant negative effect on profit; however, their application is not adjusted based on the quantity of products purchased.

## Recommendation
1. Product Promotion Based on Periodic Demand:
   - For all regions, high year-end demand can be leveraged through product service extension options with incentive bonuses, such as free access to premium services for two weeks. This is expected to attract customer loyalty or boost enthusiasm for upgrading their product subscription package.
   - Specifically for the APJ region, free training can be conducted to demonstrate the effectiveness and usefulness of the SaaS product for customer business purposes in the low demand period, which is the first to second quarter of the year. The scope can be focused on sectors that might have high demand potential but negatively contribute to profit, such as Finance, Tech, and Manufacturing.
2. Discount Segmentation Based on Purchase Quantity:
   - Use a progressive discount strategy by offering higher discounts for more expensive products to more effectively maintain profitability, and to encourage higher purchase levels.
   - Adopting the approach from the study by Gong et al. (2015) on movie markets, customers can be given a 5 percent discount for low tier purchases, a 10 percent discount for mid tier, and a 15 percent discount for high tier purchases. The classification is based on the actual product price range of each product.
   - Meanwhile, for low quantity purchases (1 to 4), discounts can be omitted or only non-monetary incentives provided, such as a premium trial feature of sales and marketing automation for two weeks. Note that the portion of the premium subscription price provided as a trial proportion must not exceed the discount amount offered if the customer purchases more than 5 units.
3. Optimize Discount Strategies by Region:
   - Reduce discounts in the APJ regions, especially in Healthcare and Transportation sectors, which having the highest negative profits, to make them more targeted and reduce reliance on discounts as the primary tool for increasing demand.

## Dashboard
See the Dashboard on [Tableau Public](https://public.tableau.com/views/AWSSaaSSalesReports/theDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
![the Dashboard](https://github.com/user-attachments/assets/4fbf2e51-eb94-411b-85bb-504f3a3de238)
