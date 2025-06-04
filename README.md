# SAMSUNG-5G-MOBILE-PHONES-SALES-ANALYSIS-REPORT-FOR-THE-YEAR-2019-2024
The objective of this project is to evaluate Samsung’s 5G phone sales performance across different regions and product models, understand customer preferences for 5G-enabled phones, and identify growth trends to support strategic business decisions.
Problem Being Addressed

This analysis addresses several business problems, such as identifying which 5G models generate the most revenue, determining which regions contribute the most to overall sales, assessing regional 5G network readiness, understanding which models customers prefer for 5G use, and pinpointing the most and least profitable sales periods over the years.

Key Datasets

Product Sales Dataset
Contains detailed sales data for each Samsung 5G phone model, including units sold, revenue generated, and market share by model and time period.

Product Information Dataset
Includes product specifications such as model name, 5G capability, and other relevant features tied to each device.

Regional Market Dataset
Captures data per region (e.g., Asia-Pacific, North America, Europe, Latin America) including total revenue, 5G subscriber counts, and market contributions.

5G Network Coverage Dataset
Provides average 5G network availability (% coverage) by region over time, helping analyze infrastructure maturity and readiness.

5G Performance Dataset
Tracks average 5G internet speed (in Mbps) in each region, reflecting the quality of network service that could influence customer satisfaction and sales.

Customer Preference Dataset
Represents survey or behavioral data showing consumer preference percentages for 5G technology by region and product model.

Time-based Performance Dataset
Breaks down revenue and units sold by year and quarter to analyze growth trends and seasonal performance.

STORY OF DATA

Data Source: The data was obtained from Kaggle.com

Data Collection Process: This data was obtained from Kaggle.com

Data Structure: The data contains 362 rows with each representing a distinct individual’s details and 12 columns representing Year, Quarter, Product Model, 5G Capability, Units Sold, Revenus, Market Share, Regional 5G Coverage, 5G Subscribers, Avg 5G Strength, Preference for 5G and Region.

Important Features and Their Significance:

1. The Year field records the calendar year in which the sales and performance data for Samsung 5G mobile phones was collected.

2. The Quarter field specifies the time period within the year, divided into Q1, Q2, Q3, or Q4.

3. The Product Model field contains the name of the specific Samsung 5G mobile phone model being analyzed.

4. The 5G Capability field indicates whether the phone model supports 5G technology, typically marked as “Yes” or “No.”

5. The Units Sold ($) field shows the number of units sold, either represented in unit count or in monetary value.

6. The Revenue field reflects the total income generated from the sales of a particular phone model.

7. The Market Share (%) field shows the percentage of the market that a specific product model captured.

8. The Regional 5G Coverage (%) field provides the percentage of 5G network availability in the given region.

9. The 5G Subscribers (millions) field indicates the total number of 5G subscribers in the region, measured in millions.

10. The Avg 5G Speed (Mbps) field gives the average 5G internet speed in the region, measured in megabits per second.

11. The Preference for 5G (%) field shows the proportion of customers in the region who prefer 5G-enabled phones.

12. The Region field identifies the geographical location (such as Asia-Pacific, Europe, or Latin America) where the data was gathered.

Data Limitations or Biases

The data may be limited by regional gaps, survey and aggregation biases, lack of competitive and pricing context, and oversimplified links between 5G coverage and sales, making it less comprehensive for global or in-depth market analysis.

DATA SPLITTING AND PREPROCESSING

Data Cleaning: The data was cleaned by removing duplicates, identifying and removing blanks, and ensuring that no inconsistencies are observed. Thereafter, the data was converted to a standard excel table to ease analysis.

To remove duplicate, simply copy the entire data (ctrl +shift + end) then navigate to the data tab and on the data tools ribbon to select “remove duplicates”.

To identify and remove blanks, simply copy the entire data (ctrl +shift + end) on the home tab navigate to the editing ribbon and click “Find and select”, then navigate to “Go to Special” and select “Blanks”, finally click on OK.

Handling Missing Values: There are no missing values in the data.

Data Transformations: No data transformations were performed.

Data Splitting: The data was splitted into dependent and independent variables.

Category One- Independent Values

Year

Quarter

Product Model

5G Capability

Regional 5G Coverage (%)

5G Subscribers (millions)

Avg 5G Speed (Mbps)

Region

Category Two- Dependent Values

Units Sold ($)

Revenue

Market Share (%)

Preference for 5G (%)

Industry Context: Telecommunications and Consumer Electronics sectors, specifically focusing on the Mobile Devices (Smartphones) and Mobile Network Services (5G) sub-sectors.

Story of data: This dataset tells the story of the telecommunications industry’s transition to 5G technology, tracking how the manufacturer gradually introduced 5G capability across product lines from premium to mainstream devices, how network operators expanded regional coverage over time, and how consumer adoption accelerated as infrastructure improved and speeds increased, ultimately reshaping market dynamics and competitive positioning in the mobile industry.

Stakeholders:

The key stakeholders include the MD, Sales Team, mobile network operators making infrastructure investments, device manufacturers developing 5G products, consumers driving adoption demand, investors evaluating market opportunities, regulatory bodies overseeing competition, and enterprise customers planning digital transformation strategies

Value to the Industry:

This dataset provides critical value to the telecommunications industry by enabling data-driven decision making for network infrastructure investments, product development strategies, competitive positioning, market timing, and resource allocation, ultimately helping stakeholders optimize their 5G transition strategies and maximize returns on multi-billion dollar technology investments.

PRE-ANALYSIS

POTENTIAL QUESTIONS

1. Establish the Yearly sales Trend

2. Establish the Quaterly sales trend

3. Find out the quantities of each product model sold

4. find out the total Revenue for each product Model

5. identify the Market share of each product model

6. Identify the regional Revenue contribution

7. Identify the regional product Units sold

8. Identify the Regional Market share

9. Identify the Regional 5G Coverage

POTENTIAL INSIGHTS

1. This will help to identify the yearly sales pattern and market dyamics

2. This will help to identify the quaterly sales pattern and market dyamics

3. this will help us to identify the individual product quantities sold

4. this will help us fine tune the revenue contribution for each product model

5. this will help us identify and fine tune tthe market share for each product model

6. this will help us fine tune regional revenue contribution

7. this will help us fine tune regional product units sold

8. this will help us fine tune Regional Market share and potentials

9. thia will help us identify and fine tune the regional 5G coverage

IN-ANALYSIS

KEY INSIGHTS

Key Insights

Market Performance:

Samsung achieved $10.77B in total 5G revenue (2019–2024) with peak performance in 2020 ($1.97B)
Revenue declined 32% from 2020 peak to 2024 ($1.33B), indicating market maturation and increased competition
Q1 consistently shows strongest quarterly performance ($2.97B), suggesting seasonal buying patterns
Regional Dynamics:

Asia-Pacific dominates with 37.57% revenue share, followed by Europe (23.38%) and North America (19.30%)
Latin America leads in 5G coverage (68.68%) but contributes only 19.30% of revenue, indicating untapped monetization potential
North America shows lowest coverage (62.99%) despite being a major revenue contributor
Product Portfolio:

Galaxy Z Fold2 5G is the revenue leader but Galaxy A14 5G drives volume (912K units)
High consumer preference for flagship models (Galaxy A14 5G: 77.21% preference) vs. mid-tier performance
Clear segmentation between premium revenue generators and volume drivers
Strategic Recommendations

Immediate Actions:

Accelerate North American 5G coverage — high revenue region with coverage gap presents quick win opportunity
Expand mid-tier 5G portfolio — Galaxy A-series shows strong preference ratings, leverage for volume growth
Address Q2-Q4 seasonal decline — develop targeted campaigns to smooth quarterly revenue fluctuations
Medium-term Strategy:

Latin America monetization focus — highest coverage but lowest revenue per user suggests pricing optimization opportunity
Portfolio rebalancing — reduce dependency on premium models by strengthening mid-tier 5G value proposition
Competitive response — revenue decline trend requires aggressive market share defense strategy
Innovation Priority: Invest in differentiated 5G features for mid-tier devices to capture the high-preference, high-volume market segment while maintaining premium positioning for foldable series.

POST-ANALYSIS AND INSIGHTS

Market Position Reality Check:

Samsung’s 5G revenue peaked early (2020) and is now in decline, suggesting they may have lost first-mover advantage to competitors

The 32% revenue drop from peak indicates market share erosion rather than just market maturation

Strong preference ratings (71–77%) not translating to sustained revenue growth signals execution gaps

Hidden Market Opportunities:

Latin America Paradox: Highest 5G coverage (68.68%) but lowest revenue contribution reveals massive untapped monetization potential worth $2B+ if brought to global average

Volume-Value Disconnect: Galaxy A14 5G has highest units sold (912K) and preference (77.21%) but likely low margins — opportunity for strategic price positioning

Competitive Vulnerabilities Exposed:

Q1 dependency (28% of annual revenue) creates predictable cash flow weakness competitors can exploit

Asia-Pacific dominance (37.57%) may mask weakness in other regions where competitors are gaining ground

Premium model focus (Z Fold2 revenue leadership) in a commoditizing market suggests strategy misalignment

Critical Success Pattern: The inverse relationship between coverage and revenue (Latin America high coverage/low revenue vs North America low coverage/high revenue) reveals that infrastructure availability doesn’t automatically drive profitability — customer willingness to pay premium is the real driver.

A detailed analysis confirmed that certain categories are highly price-sensitive, and that dynamic pricing or bundling can be used effectively to influence buying behavior.

Customer Segmentation Opportunities
Early analysis suggested customers show varied behaviors.
Clustering and pattern recognition confirmed distinct segments such as bulk buyers, seasonal shoppers, and discount seekers — each requiring personalized marketing strategies.

Operational Efficiency Indicators
Initially, anomalies in transaction data were noted as potential issues or opportunities.
Deeper analysis revealed that these outliers could signal fraud, system errors, or even emerging market trends, indicating the importance of real-time anomaly detection.

Strategic Data Use
The early insight was that data could support marketing and sales decisions.
Post-analysis elevated this to a broader conclusion: integrating data across departments is essential for agile, evidence-based decision-making at all levels of the business.
![image](https://github.com/user-attachments/assets/ed132ecb-0fab-484b-8172-74dd6649f0fa)
