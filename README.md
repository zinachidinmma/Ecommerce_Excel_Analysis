# Ecommerce_Excel_Analysis
ECOMMERCE DASHBOARD ANALYSIS
You’ve been hired by an e-commerce store as their data analyst. You’re tasked to carry out Exploratory Data Analysis on their past data to uncover trends and patterns in the business.
Ecommerce Dataset 
Columns
•	Customer ID
•	Age
•	Gender
•	Income Level
•	Marital Status
•	Education Level
•	Occupation
•	Location
•	Purchase Category
•	Purchase Amount
•	Frequency of Purchase
•	Purchase Channel
•	Brand Loyalty
•	Product Rating
•	Time Spent on Product Research(hours)
•	Social Media Influence
•	Return Rate
•	Customer Satisfaction
•	Engagement with Ads
•	Device Used for Shopping
•	Payment Method 
•	Time of Purchase
•	Discount Used
•	Customer Loyalty Program Member
•	Purchase Intent
•	Shipping Preference
•	Time to Decision





Derived Columns
Age Group: This column was derived from the Age column using conditional statements.
 
Customer Satisfaction Level: This was derived from the customer satisfaction column with the range below:
1-3: Very Dissatisfied
4-6: Neutral
7-10: Highly Satisfied
 
Day Name: This column was derived from the time of purchase column using the date function.
 

ANSWERS & ANALYSIS
Metrics:
a)	Total Customers = 100
b)	Total Products = 24
c)	Total Locations = 969
d)	Total Shipping Preference = 3
e)	Total Payment Method = 5
Task
1.	Customer demographics and purchase behavior: you are to group the customer age into two groups young (below 35 years) and old (above 36) and compare which group spends more on products, which category each group patronize more and their income level.
Chart
 
Grouping:
•	Young (Below 35 years)
•	Old (Above 36 years)
Comparison: For this analysis, I focused on the top 2 product categories patronize by the young and old.
Age Group	Top Product Categories Patronized	Spending (Highest Product Count)	Income Level
Young
(<35)	- Baby Products (112)
- Health Supplements (119)
- Furniture (102)	Health Supplements (119)	High
Old
(>36)	- Electronics (142)
- Jewelery & Accessories (118)
- Food & Beverages (108)	Electronics (142)	High/Middle

Key Insights:
Which group spends more:
•	Old customers (above 36 years) spend more overall, especially in Electronics (142 counts), which is the highest purchase count on the chart.
Category Preferences:
•	Old Customers: Prefer Electronics, Jewelry & Accessories, and Food & Beverages.
•	Young Customers: Favor Health Supplements, Baby Products, and Furniture.
Income Levels:
•	Both age groups mostly fall into High income level, especially in categories like Electronics, Health Supplements, and Baby Products.
•	Middle-income customers (both groups) also show notable spending on Furniture, Food & Beverages, and Travel & Leisure (Flights).

Conclusion:
Old customers (above 36) spend more on average, especially on high-value items like Electronics and Jewelry. 
Young customers (below 35) focus on health-related and household products like Health Supplements and Baby Products. 
High-income customers dominate purchases in both groups, particularly for expensive or essential products.

2.	Customer loyalty and retention analysis: how often do customers return purchased items from the store, how customer satisfaction affect brand loyalty.

Note: 
These metrics are plotted against Customer Satisfaction Level on the x-axis, which is categorized from 1 to 10 and grouped into three broader categories:
•	Very Dissatisfied (1-3)
•	Neutral (4-6)
•	Highly Satisfied (7-10)

Chart
 

This chart is a clustered bar chart that visualizes two metrics:
1.	Sum of Return Rate (blue bars)
2.	Count of Brand Loyalty (red bars)
Key Observations:
1.	Very Dissatisfied (1-3):
o	Both Return Rate and Brand Loyalty are relatively high.
o	At Satisfaction Level 1, Brand Loyalty (red) exceeds Return Rate (blue).
o	Slight balance at level 2, with both metrics almost equal.
o	At level 3, Return Rate slightly higher than Brand Loyalty.
2.	Neutral (4-6):
o	Overall, both metrics decline compared to the 'Very Dissatisfied' category.
o	Noticeable drop in both metrics at level 4.
o	Both metrics are lowest at level 5.
o	Increase at level 6, but Brand Loyalty slightly exceeds Return Rate.
3.	Highly Satisfied (7-10):
o	Fluctuations in metrics: 
	Level 7: Return Rate peaks sharply, highest point in the chart.
	Level 8-9: Brand Loyalty consistently remains high, while Return Rate slightly dips.
	Level 10: Brand Loyalty decreases significantly, but Return Rate remains stable.
Key Insights:
•	Return Rate doesn’t consistently decrease as satisfaction increases, which is counterintuitive. It peaks at Satisfaction Level 7, which might suggest factors other than satisfaction (e.g., product issues or high engagement leading to more returns).
•	Brand Loyalty generally trends high, even among dissatisfied customers, though there's a noticeable dip at level 10.
•	There’s an unusual trend: brand loyalty is relatively strong even when customer satisfaction is low (levels 1, 3, and 6). 
•	However, as satisfaction increases (levels 9 & 10), brand loyalty slightly decreases.
Conclusion
Satisfaction Level	Return Rate Trend	Brand Loyalty Trend
Low Satisfaction (1-3)		
		High return rates: dissatisfaction leads to product returns.	Surprisingly high loyalty (possibly due to necessity or lack of alternatives).

Neutral (4-5)		Lower return rates	Loyalty starts to decline slightly.

High Satisfaction (6-10)	Mixed return rates (highest at level 7).	Loyalty peaks at level 6 but declines at the highest satisfaction levels (9-10).

Safe to say that customer loyalty isn't solely dependent on satisfaction; external factors like product uniqueness, lack of alternatives, or loyalty programs may influence it. Return rates don’t strictly correlate with dissatisfaction; other factors like product quality, fit, or personal preference may also play a role.









3.	Pricing and discounts effectiveness: do discount sensitive customers spend more when products are discounted, how does the discount used affect return rate, are customers with high income interested in discounts.
Chart
 
Do discount sensitive customers spend more when products are discounted?
•	Very Sensitive Customers:
o	Highest purchase count: 350
o	These customers are highly responsive to discounts, and their purchase volume is the largest.
•	Somewhat Sensitive Customers:
o	Purchase count: 319
o	They still respond positively to discounts but slightly less than "Very Sensitive."
•	Not Sensitive Customers:
o	Purchase count: 331
o	Despite being labeled "Not Sensitive," their purchase count is still high, almost as much as Very Sensitive customers.
Conclusion: Yes, discount-sensitive customers (especially "Very Sensitive") clearly spend more when products are discounted.
Even "Not Sensitive" customers make a significant number of purchases, showing that discounts may have a universal appeal, though not as strong as for the highly sensitive group.
How does the discount used affect return rate?
•	Return Rate Trend (Blue Bars):
o	Very Sensitive: 321 returns
o	Somewhat Sensitive: 307 returns
o	Not Sensitive: 326 returns (highest return rate)
Insight:
•	"Not Sensitive" customers have the highest return rate (326), despite being the least responsive to discounts.
•	"Very Sensitive" customers also have a high return rate (321), though slightly lower.
•	Somewhat Sensitive customers show the lowest return rate (307).
Conclusion: Discounts may trigger impulse purchases, especially among very sensitive customers, leading to higher returns. Interestingly, even non-sensitive customers return items frequently, suggesting their returns may be unrelated to discount appeal but possibly linked to other factors like product fit or quality.

Are customers with high income interested in discounts?
This chart breaks down Pricing & Discount Effectiveness based on two factors:
•	Customer Sensitivity to Pricing (Very Sensitive, Somewhat Sensitive, Not Sensitive)
•	Income Levels (Middle Income, High Income)
Interpretation:
•	Very Sensitive + High Income:
o	This group shows the highest purchase amount (190) among all categories.
o	It clearly indicates that high-income customers who are very sensitive to discounts are highly engaged and spend more when discounts are offered.
•	Somewhat Sensitive + High Income:
o	Purchase amount (160) is almost the same as middle-income customers (159).
o	Suggests moderate interest in discounts.
•	Not Sensitive + High Income:
o	Purchase amount (165) is slightly lower than middle-income (166), suggesting that discounts are not a strong motivator for this high-income group.
Final conclusion: Yes, high-income customers can be very interested in discounts, especially if they are already price sensitive (Very Sensitive group). However High-income customers who are less sensitive (Not Sensitive) or Somewhat Sensitive show relatively stable or slightly lower purchase behavior, meaning discounts do not significantly influence them.

4.	Purchase behavior and preferences: how does the purchase category affect shipping preference (are customers that purchase a particular product likely to use a particular mode of shipping), what are the peak shopping hours and days of the week?
 
Observations by Category
Category	Express	No Preference	Standard	Dominant Shipping Preference
Electronics	15	22	17	No Preference
Home Appliances	14	16	20	Standard
Jewelry & Accessories	14	17	19	Standard
Sports & Outdoors	12	25	14	No Preference
Toys & Games	13	17	17	No Preference & Standard

Insights:
1.	Electronics:
o	No Preference (22) is the highest.
o	Suggests that electronics buyers are flexible with shipping, possibly focusing more on product features or price.
2.	Home Appliances:
o	Standard shipping (20) dominates.
o	Indicates customers prefer cost-effective, possibly slower delivery for bulky items.
3.	Jewelry & Accessories:
o	Slightly higher preference for Standard shipping (19).
o	Likely due to non-urgency and focus on secure delivery.
4.	Sports & Outdoors:
o	Strong preference for No Preference (25).
o	Implies shipping speed isn’t a priority; customers may prioritize availability or price.
5.	Toys & Games:
o	Equal preference between Standard (17) and No Preference (17).
o	Suggests shipping flexibility, possibly depending on occasion (gifts vs. regular purchase).
Conclusion:
Yes, purchase category affects shipping preference, but not drastically.
•	Standard shipping is slightly preferred for bulkier, non-urgent categories (Home Appliances, Jewelry).
•	No Preference is common across many categories, especially in Electronics, Sports & Outdoors, and Toys, suggesting that many customers may prioritize product or price over delivery speed.
•	Express shipping is consistently the least preferred across all categories, showing that fast delivery isn't a primary concern for most categories.
 
Peak Shopping Days:
•	Tuesday has the highest shopping hours.
•	Thursday and Sunday also show high activity, slightly below Tuesday.
Low Shopping Days:
•	Saturday is the lowest day in terms of hours spent shopping.
•	Wednesday and Friday also have relatively lower activity

Conclusion:  Peak Shopping Days is Tuesday 











5.	Marketing and ad engagement: does social media’s influence affect the purchase amount, does social media influence affect product rating.
       

Social Media Influence on Product Rating
(Referring to the first bar chart titled "Social Media VS Product Rating")
•	High social media influence has the highest product ratings (268 total ratings).
•	Low influence has 249 ratings, None has 247 ratings, and Medium influence has the lowest ratings at 236.
Conclusion:
There’s a positive correlation between higher social media influence and higher product ratings. Products with high social media engagement seem to receive better ratings, possibly due to:
•	Increased brand visibility.
•	Better customer interaction.
•	Peer influence and social proof.
Social Media Influence on Purchase Amount
(Referring to the second bar chart titled "Social Media vs Purchase Amount")
•	High social media influence leads to the highest total purchase amount (76,192.92).
•	Followed by:
o	Low influence: 67,852.32
o	Medium influence: 66,108.02
o	None: 64,910.62
Conclusion:
Again, there is a positive relationship between social media influence and purchase amount.
The higher the social media engagement, the higher the total purchases, likely due to:
•	Effective advertising and promotions.
•	Higher customer awareness and trust.

6.	Return rate and product quality: do product with low rating have higher return rates, which product category has the highest return rate, are dissatisfied customers more likely to return products
Chart
 

For this analysis, I focused on the top 4 purchase categories for this analysis 
Do products with low ratings have higher return rates?
Observation:
•	For Jewelry & Accessories, products rated 1 star have the highest return rates.
•	Gardening & Outdoors and Travel & Leisure (Flights) categories also show relatively high returns at lower ratings (1 or 2 stars).
•	However, in Electronics, surprisingly, 4-star rated products have the highest return rate, not the lowest-rated ones.
Conclusion:
•	Generally, products with lower ratings tend to have higher return rates, especially noticeable in Jewelry & Accessories and Gardening & Outdoors.
•	However, exceptions exist (e.g., Electronics category shows high returns even at 4-star ratings), possibly due to product complexity, user expectations, or warranty returns.

Which product category has the highest return rate overall?
Observation:
•	Jewelry & Accessories (1-star rating) shows the highest return rate peak in the chart.
•	Followed by:
o	Electronics (4-star)
o	Travel & Leisure (Flights, 5-star) has a notably high return rate too, which is unexpected.
Conclusion:
•	Jewelry & Accessories category experiences the highest return rates overall, particularly at 1-star ratings.
3. Are dissatisfied customers more likely to return products?
Observation:
•	In Jewelry & Accessories and Gardening & Outdoors, lower ratings correlate clearly with higher return rates.
•	Dissatisfied customers (those giving 1–2-star ratings) are more likely to return products in most categories.
•	However, Electronics and Travel & Leisure show anomalies, where even higher-rated products get returned. This could be due to:
o	Post-purchase issues (faults, damages).
o	Change in travel plans (flights).
o	Product not matching customer needs despite decent ratings.
Conclusion:
•	Yes, dissatisfied customers (low ratings) are generally more likely to return products.
•	Jewelry & Accessories category has the highest return rate.
