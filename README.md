# ZICCO-STORES-CHOCOLATE-SALES-ANALYSIS-REPORT
: This project is designed to analyze chocolate product sales performance across different countries, products, salespersons, and time periods
INTRODUCTION

Objective of the Project: This project is designed to analyze chocolate product sales performance across different countries, products, salespersons, and time periods. The report aims to identify top-performing markets, sales trends, high-revenue products, and individual sales performance in order to optimize product distribution, improve sales strategies, and guide business decisions for increased profitability and efficiency.

Problem Being Addressed: it addresses the problem of uneven sales performance and inefficient product distribution across regions, products, and sales representatives.

Key Datasets and Methodologies: The Zicco Stores Sales Report uses sales transaction, product, geographic, salesperson, and time-series data combined with descriptive, trend, comparative, and efficiency analyses to evaluate sales performance, identify top and underperforming areas, and guide strategic decisions.

STORY OF DATA

Data Source: The data was obtained from Kaggle.com

Data Collection Process: This data was obtained from Kaggle.com

Data Structure: The data contains 1,096 rows with each representing a distinct individual’s details and 6 columns representing Salesperson, Country, Product, Date, Amount and Boxes shipped.

Important Features and Their Significance:

I. Salesperson — this represents the individual sales personnel

II. Country — This represents the country

III. Product — this represents the individual products

IV. Date — this is the date of transaction

V. Amount — this is the cost of each transaction

VI. Boxes shipped — this is the number of shipped boxes

Data Limitations or Biases

There is no data limitations observed.

DATA SPLITTING AND PREPROCESSING

Data Cleaning: The data was cleaned by removing duplicates, identifying and removing blanks, and ensuring that no inconsistencies are observed. Thereafter, the data was converted to a standard excel table to ease analysis.

To remove duplicate, simply copy the entire data (ctrl +shift + end) then navigate to the data tab and on the data tools ribbon to select “remove duplicates”.

To identify and remove blanks, simply copy the entire data (ctrl +shift + end) on the home tab navigate to the editing ribbon and click “Find and select”, then navigate to “Go to Special” and select “Blanks”, finally click on OK.

Handling Missing Values: There were no missing values in the data.

Data Transformations: No data transformations were performed.

Data Splitting: The data was splitted into dependent and independent variables. The dependent variables are Date, Amount and Boxes shipped while the independent variables are salesperson, Country and product.

Industry Context: Retail and Consumer Goods

Stakeholders: Sales Managers, Marketing Teams, Operations & Logistics Executives/Decision-Makers, Data Analysts/BI Teams

Value to the Industry: this delivers valuable insights that help the retail industry optimize sales strategies, improve supply chain efficiency, target high-performing markets, and support data-driven decision-making for increased profitability and customer satisfaction.

PRE-ANALYSIS

IN-ANALYSIS

Insights

I. January recorded the highest revenue ($896,105) and boxes shipped (10,148).

II. There was a sharp decline in both sales and shipments in February.

III. Australia had the highest total sales, outperforming all other countries.

IV. Some products like 50% Dark Bites are shipped in high volumes but contribute less to revenue.

V. Salesperson performance varies, with Chess Bonnell generating significantly higher revenue than others.

VI. Sales slightly recovered mid-year (June), then declined steadily toward the end of the year.

Recommendations:

Plan major campaigns and stock preparations in Q4 to maximize January sales.
Launch seasonal promotions or special offers to mitigate the February drop.
Expand product range, marketing, and distribution in Australia based on high sales performance.
Reassess low-revenue, high-shipment products; focus more on high-margin items like Smooth Silky Salty.
Use top performers as benchmarks; provide training and align incentives for underperformers.
Launch bundled deals, loyalty programs, or new product introductions to reverse late-year declines.
Analysis Techniques Used in Excel:

Pivot Tables were used to analyze the data to generate meaningful visual insights.

Other features used are

Grouping- this was used to group the ages into a range.

Sorting- this was used to arrange data from the highest to the lowest and vice versa.

POST-ANALYSIS AND INSIGHTS

Key Findings:

I. January is the best-performing month, with the highest sales revenue ($896,105) and shipment volume (10,148 boxes).

II. February shows a significant sales drop, indicating possible seasonality or low post-holiday demand.

III. Australia is the top market in terms of total sales ($1,137,367), suggesting strong regional demand.

IV. Chess Bonnell is the top-performing salesperson, generating $320,901 in sales.

V. Smooth Silky Salty is the highest revenue-generating product, contributing $349,692 in total.

VI. 50% Dark Bites leads in shipment volume (9,792 boxes), but earns less revenue, highlighting a mismatch between volume and value.

VII. Wide variation in salesperson performance, with some shipping more units but delivering lower revenue.

VIII. Sales trend shows a peak in January, mid-year recovery in June, and a decline toward the end of the year, suggesting seasonal impact and declining momentum.

IX. Underutilization of some markets, where shipment levels are not translating into strong sales performance.

X. Potential inventory inefficiencies, with high shipment volumes not always aligning with product profitability

Comparison with Initial Findings:

I. January was identified early as a strong month, and the final analysis confirmed it had the highest sales and shipments.

II. The initial analysis noted a February dip, which the final findings confirmed as a sharp seasonal drop.

III. Australia was seen as a top country, and the final report validated it with the highest revenue overall.

IV. Chess Bonnell stood out early, and was confirmed as the highest-earning salesperson.

V. Smooth Silky Salty was mentioned as a top product, and final data showed it had the most revenue, while 50% Dark Bites was over-shipped.

VI. Sales trends over time were observed, and the final report confirmed a peak in January, a June rebound, and a decline after.

VII. Differences in salesperson performance were noticed, and final analysis confirmed revenue did not always match shipping effort.

VIII. Shipping inefficiencies were suspected, and were confirmed with high shipments not always producing high returns.

IX. Some markets were overlooked in the early view, and final analysis highlighted underperformance in certain regions.

X. The early focus was on results, while the final analysis connected insights to clear business strategies.
OBSERVATIONS

Sales Trend Analysis

Sales peaked in January ($896,105) and again in June ($865,144).
The lowest sales occurred in February ($699,377).
A steady rise was observed from February to June, followed by a slight decline through August.
Top Countries by Sales

Australia leads with $1,137,367 in sales.
The UK and India follow closely with $1,051,792 and $1,045,800, respectively.
All three countries contribute significantly and fairly evenly to total revenue.
Leading Products by Sales

Smooth Silky Salty is the top revenue-generating product with $349,692.
50% Dark Bites follows with $341,712, and White Choc is close behind at $329,147.
Sales distribution suggests strong competition among top products.
Top Salespersons by Revenue

Ches Bonnell is the top performer with $320,901 in sales.
Oby Sorrel and Madeline Upcott trail closely, making this a competitive leaderboard with minimal variation.
Boxes Shipped Trend

The highest shipments occurred in January (27,535 boxes) and June (26,260 boxes).
February saw the sharpest drop, with a gradual climb through May.
A decrease resumed in July and August, with August at 19,901 boxes.
Top Salespersons by Shipped Boxes

Karlen McCaffrey shipped 9,658 boxes, leading this metric.
Beverie Moffet and Dennison Crosswaite follow with 9,214 and 8,767 boxes, respectively.
These individuals drove a significant portion of product movement.
Top Products by Shipped Quantity

50% Dark Bites had the highest shipment volume at 9,792 units.
Smooth Silky Salty, Eclairs, and Caramel Stuffed Bars were close in volume, ranging between 8,700–8,800 units.
This indicates a strong and consistent demand for multiple product lines.
RECOMMENDATIONS

1. Leverage High-Performing Countries

Focus: Australia, UK, and India

Action: Launch region-specific promotions or loyalty programs in these markets to deepen engagement.
Why: These countries already drive the highest sales — increasing market penetration here offers a strong ROI.
2. Maximize Best-Selling Products

Focus: Smooth Silky Salty & 50% Dark Bites

Action: Bundle these products with new or underperforming items to increase overall sales.
Why: They are proven favorites — using them as anchors can help move other stock.
3. Address Seasonal Slumps

Focus: February & April (low sales and shipments)

Action: Plan promotions, discounts, or limited-edition releases during these months.
Why: These dips indicate an opportunity to stimulate demand when consumer activity naturally slows.
4. Incentivize Mid-Tier Salespersons

Focus: Oby Sorrel, Madelene Upcott, Beverie Moffet

Action: Introduce tiered incentives or bonus structures to encourage competition and boost performance.
Why: They are close to the top in performance and could become top sellers with a small push.
5. Streamline Logistics Based on Shipping Trends

Focus: January and June peaks; August decline

Action: Adjust inventory and logistics capacity for peak months; analyze August dip for potential causes like holiday effects or supply constraints.
Why: Aligning operations with demand ensures better service and reduces costs.
6. Promote High-Volume, Low-Revenue Products

Example: 50% Dark Bites (highest shipped, not top in revenue)

Action: Consider slight price adjustments or premium packaging options to boost per-unit revenue.
Why: You’re moving large volumes but may not be capturing full value.
7. Cross-Sell Based on Popularity

Example Pairing: Smooth Silky Salty with Eclairs or Drinking Coco

Action: Create bundled offers or curated gift boxes featuring top products.
Why: This encourages higher basket sizes and increases product visibility.
Unexpected Outcomes:

1. Mismatch Between Sales Volume and Quantity Shipped:

50% Dark Bites leads in shipped quantity (9,792 boxes) but is second in sales value. Meanwhile, Smooth Silky Salty, which has lower shipment volume (8,810 boxes), leads in sales value ($349,692).
This suggests pricing or profitability differences between products.
3. Top Salesperson Differs from Top Shipper:

Chess Bonnell tops in sales value, but Karlen McCaffrey leads in boxes shipped.
This could indicate varying pricing strategies, product focus, or efficiency in moving inventory.
5. Sales Peak Doesn’t Match Shipment Peak:

Highest sales occurred in January ($896,105), while the highest shipment was in June (26,260 boxes).
Indicates a possible mismatch in demand forecasting or seasonal stockpiling.
7. Australia Outperforms UK and India Slightly Despite Similar Numbers:

The top three countries by sales are very close in performance (Australia: $1,137,367, UK: $1,051,792, India: $1,045,800).
Suggests an evenly distributed global market, yet raises questions about competitive advantage and marketing strategy in each region.
9. High Sales Without Dominating Shipments:

Chess Bonnell achieved top sales with fewer shipped boxes than some peers.
This implies a possible focus on higher-value products or better upselling techniques.
CONCLUSION

Zicco Stores has demonstrated strong overall sales performance with key contributions from top-performing countries such as Australia, the UK, and India, and standout products like Smooth Silky Salty and 50% Dark Bites. While sales and shipment trends show seasonal fluctuations, January and June represent performance peaks. The analysis reveals a capable and balanced sales team, although certain discrepancies between shipping volume and revenue suggest opportunities to optimize pricing, sales strategy, and inventory alignment. Continued focus on high-performing products, countries, and staff — combined with strategic planning during slower months — will enhance profitability and efficiency across operations

Limitations:

1. Lack of Customer Demographics:
No data on customer segments (age, gender, preferences), which limits insights into targeted marketing or buying behavior.

2. No Profit or Cost Information:
The dashboard focuses on revenue and shipment volume but doesn’t include profit margins or production costs, restricting profitability analysis.

3. Absence of Regional Trends Beyond Top 3 Countries:
Data is limited to the top-performing countries only, omitting insights into underperforming or emerging markets.

4. Limited Timeframe:
The data spans only a few months (up to August), making it difficult to identify long-term or annual trends.

5. No Channel Breakdown:
There is no information on sales channels (e.g., online, retail, wholesale), which restricts analysis of channel performance and customer touchpoints.

6. No Inventory or Stock-Out Data:
Without stock level insights, it’s hard to assess whether dips in sales or shipments are due to demand drops or supply constraints.

7. Sales Person Attribution Lacks Detail:
It’s unclear whether each salesperson handles specific regions, products, or accounts — limiting understanding of sales team dynamics

Future Research

1. Customer Segmentation Analysis:
Collect and analyze demographic and behavioral data to identify key customer segments and tailor marketing strategies accordingly.

2. Profitability by Product and Region:
Integrate cost data to assess net profit margins per product and per country to shift focus from volume to value.

3. Sales Channel Performance:
Examine how different channels (e.g., online, retail, wholesale) contribute to sales and customer acquisition to better allocate resources.

4. Seasonality and Demand Forecasting:
Conduct deeper time-series analysis to predict peak periods, allowing for proactive inventory and marketing planning.

5. Inventory and Fulfillment Efficiency:
Analyze stock levels, delivery times, and stock-out frequency to identify supply chain bottlenecks and opportunities for improvement.

6. Sales Team Productivity Metrics:
Introduce KPIs such as conversion rates, average deal size, and customer retention per salesperson to evaluate efficiency beyond revenue.

7. Customer Satisfaction and Feedback Loops:
Incorporate customer reviews, return rates, or satisfaction surveys to link product performance with user experience.

8. Competitor Benchmarking:
Compare performance with industry peers to identify gaps or competitive advantages in product pricing, positioning, or regional strength.

REFERENCEE: The data for this project was obtained from Kaggle.com






