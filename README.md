<img width="733" height="361" alt="image" src="https://github.com/user-attachments/assets/35b8621c-0b31-4541-9834-d30ed67ab078" /># Project Background 
GameZone, a fictional company, was founded in 2018 and specializes in selling refurbished gaming products such as Nintendo Switch consoles, PlayStations, and gaming laptops. The dataset used in this analysis covers the period from 2019 to early February 2021. The purpose of this analysis is to extract insights and provide recommendations to enhance the performance of the sales, product, and marketing teams.

## Executive Summary 
This analysis of 21800 orders of GameZone from 2019 to Feb 2012 revealing key trends to inform strategic actions to enchance sales. Gamezone averages $2.8M annual sales, maintining a steady decline of sales to 46% on the Q1 of 2021. North America and 
![image](https://github.com/LeeUNel/GameZome-Analysis/blob/d7639b15ee6d930cf9eff0f3f8bb5b46eccc894e/Annual%20Sales%2C%20Order%2C%20AOV%20Trend.png)
## Insights Deep-Dive
### Sales Trend and Growth Rates
- Gamezone averages $2.8M annual sales with an average of 10,000 orders per year.
- Sales surge by 66.12% in 2020, jumping from $1.5M in 2019 to $4M in 2020. The trend continue to until February 2021.
- Annual AOV increases from 82.44% in 2019 to 107.46% in 2020 and steadily inceases at 109.53% for the 1st quarter of 2021 when COVID-19 quarantine eases and people are starting to go out of their homes.
- Nintendo switch totaled 27.03% ($1.66M) of the sales which is equivalent to the 47.58% (10K) of the total orders. On the other hand, Sony Playstation 5 Bundle accumulated 25.90% ($1.60M) in sales for 4.48% (977) orders only. A huge difference between the two product that drives over half of the total sales.
  
![image](https://github.com/LeeUNel/GameZome-Analysis/blob/main/Annual%20Sales,%20Order,%20AOV.png?raw=true)
![image](https://github.com/LeeUNel/GameZome-Analysis/blob/6d805b576cd64cea6549e37bb328e38a1ad3e25b/Most%20Sold%20Products.png?raw=true)
![image](https://github.com/LeeUNel/GameZome-Analysis/blob/141b95b4db17673c1c052d0e49135d596b9c4558/Geographic%20Location%20Map.png)
 ### Sales by Geographical Location, Marketing Channel, 
- Majority of the customers are from Northern America region specifically the US which holds 57.12% and 56.39% of the total sales and orders, respectively.
- Direct sales accounted for 84.69% ($5.2M) of the GameZone total sales. While email and affiliate marketing  channels gather 8.96% ($611K) and 3.60% ($220K) of the total sales, respectively. 
- The website generates 97.49% of the sales or $6M of the total sales, next is the mobile app which only generates 2.51% or $154K of the total sales. 
![image](https://github.com/LeeUNel/GameZome-Analysis/blob/23dc78c9ade764f7d11c376b96484293e7cff3dd/Geographic%20Location.png)
![image](https://github.com/LeeUNel/GameZome-Analysis/blob/23dc78c9ade764f7d11c376b96484293e7cff3dd/Marrketing%20Channels.png)
![image](https://github.com/LeeUNel/GameZome-Analysis/blob/f7535ad08987bfe35954c36547f130d708c485b2/Purchase%20Platform.png)

## Recommendations 
### Product Mix Optimization
Nintendo Switch drives 47.58% of orders but only 27.03% of sales, meaning it’s a high-volume, lower-value driver. PS5 Bundle, on the other hand, drives 25.90% of sales with only 4.48% of orders, meaning it’s a high-value, low-volume driver. Similarly, JBL Quantum 100 Gaming Headset drives 19.68% of the total orders but has only 1.57% share on the sales. 
- Recommendation:
  - Introduce premium bundles (e.g., Switch + accessories or games) to lift AOV from high-order customers.
  - Increase stock availability or offer financing/payment plans to convert more customers, since high price point may be limiting order volume.
  - Use PS5 buyers’ higher spending habits to promote premium Switch bundles, gaming laptops, or high-margin accessories.
### Sales Channel Focus 
Direct sales dominate revenue at 84.69%, followed by email (8.96%), affiliates (3.60%), and mobile app contributions (2.51%).
- Recommendation:
  - Given email already has traction, invest in segmented campaigns (e.g., product-specific, loyalty rewards) to increase repeat purchases.
  - Recruit more influencers and tech reviewers in the gaming niche to boost affiliate reach, especially in regions outside North America.
  - Enhance app experience with app-exclusive deals, early access to refurbished inventory, and gamified loyalty points to encourage downloads and usage.
### Geographical Diversification
Over 57% of the sales come from the US (North America), this heave reliance on a single region increases risks and limits growth. 
- Recommendation:
  - Target growing gaming markets such as Western Europe, Southeast Asia, and Latin America through localized marketing campaigns and regional inventory hubs.
  -  Partner with regional e-commerce platforms to enter new markets faster.
 
# Assumptions and Caveats
- Order Date Error: Logic suggests that the order date should precede the shipping date. However, 2,005 rows show shipping dates earlier than their corresponding order dates—an anomaly that requires further investigation with the relevant teams.
- Missing Country Code: 37 rows have missing country codes, preventing accurate mapping to their respective regions. If the number of missing entries increases as the dataset grows, it could skew results and potentially lead to biased conclusions.
