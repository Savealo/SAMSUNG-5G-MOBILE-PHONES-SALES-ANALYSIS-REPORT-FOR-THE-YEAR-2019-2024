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
DATA VISUALIZATIONS & CHARTS

YEARLY REVENUE GROWTH
![image](https://github.com/user-attachments/assets/ed132ecb-0fab-484b-8172-74dd6649f0fa)
Samsung’s 5G phone revenue demonstrated extreme volatility from 2019–2024, surging 46% to peak at $1.96 billion in 2020 during early 5G adoption, then declining $430 million through 2023 due to market maturation and intensified competition from Chinese manufacturers and Apple, before recovering strongly with a 27% rebound to $1.95 billion in 2024, indicating successful strategic adaptation and positioning Samsung for sustainable growth despite the high market volatility that requires continuous strategic pivots and long-term investment perspectives in the rapidly evolving 5G segment.

REGIONAL REVENUE CONTRIBUTION

![image](https://github.com/user-attachments/assets/80ead09d-f310-42bc-ba1f-4a7e3e109b8e)
Samsung’s 5G revenue distribution reveals a strategically diversified but opportunity-rich global portfolio with Asia-Pacific dominating at $2.32 billion (37.57%), followed by Europe’s $2.04 billion (23.38%) and North America’s $2.44 billion (19.30%), creating balanced geographic risk management across developed markets, while Latin America’s negligible $2.09 million (00.10%) contribution represents a massive untapped growth opportunity that contrasts sharply with the region’s high 5G infrastructure coverage, indicating Samsung must prioritize market penetration strategies and localized pricing models in Latin America while maintaining premium positioning and retention strategies in its three established revenue-generating regions.

AVERAGE REGIONAL COVERAGE
![image](https://github.com/user-attachments/assets/e52482e7-c715-443c-a865-ea2a39294aab)
Samsung faces a strategic paradox where Latin America leads global 5G infrastructure coverage at 69.86% but generates only 00.10% revenue while Asia-Pacific has the lowest coverage at 62.99% yet dominates revenue at 37.57%, with Europe (68.68% coverage, 23.38% revenue) and North America (67.72% coverage, 19.30% revenue) showing more balanced infrastructure-to-revenue ratios, indicating that while all regions demonstrate adequate 5G readiness above 62%, Samsung must address the coverage-revenue disconnect through targeted pricing strategies in Latin America and capitalize on Asia-Pacific’s infrastructure expansion potential to maximize growth in its strongest market, proving that network infrastructure alone doesn’t guarantee commercial success without proper market positioning and economic accessibility

QUATERLY REVENUE GROWTH
![image](https://github.com/user-attachments/assets/4685d379-221f-479d-8e09-59fea32a7fc8)
Samsung’s quarterly 5G revenue demonstrates significant seasonal volatility with Q1 peaking at $2.97 billion before declining $304 million to Q2’s $2.67 billion, continuing downward to Q3’s trough of $2.43 billion, then recovering to Q4’s $2.71 billion, creating a $544 million swing that reveals challenging mid-year market conditions possibly from competitive pressures or consumer spending patterns, while confirming Q1 as optimal for major product launches and Q4 holiday season importance, indicating Samsung must develop more consistent demand generation strategies to address the consecutive Q2-Q3 weakness and capitalize on the strong seasonal bookends for sustained quarterly performance.

TOP 5 PRODUCT MODELS BY REVENUE
![image](https://github.com/user-attachments/assets/e489d0a2-7d7e-486f-b87d-8c3496b300a5)
Samsung’s top 5 5G models generate over $4.36 billion in combined revenue with Galaxy A14 5G leading at $913.1 million despite only 00.16% market share, followed by Galaxy S23 5G’s $894.8 million with 60.86% share, Galaxy S22 5G’s $870.6 million with 07.43% share, Galaxy A52 5G’s $863.1 million with 79.52% share, and Galaxy Z Fold2 5G’s $824.9 million with 97.30% share, demonstrating Samsung’s successful differentiated pricing strategy where premium models achieve high revenue through value-based pricing rather than volume sales, while the portfolio balance across flagship, mid-range, budget premium, and innovative foldable categories validates Samsung’s market segmentation approach and confirms that strategic product concentration maximizes returns from select high-performing models rather than pursuing broad market share competition.

TOP FIVE PRODUCTS MODELS BY UNITS SOLD
![image](https://github.com/user-attachments/assets/5a22a2ef-8484-4f10-aba8-6265345dc038)
Samsung’s unit sales leadership is dominated by Galaxy Z Fold2 5G at 912,096 units, followed closely by Galaxy A73 5G (909,507), Galaxy Z Flip3 5G (901,892), Galaxy A52 5G (891,357), and Galaxy A14 5G (879,660), creating a remarkably consistent volume distribution within a narrow 32,436-unit range that validates Samsung’s strategic innovation investment with two foldable models leading sales despite premium pricing, while three mid-range models (A73, A52, A14) confirm successful penetration of price-conscious segments, demonstrating Samsung’s unique ability to drive substantial volume across both cutting-edge foldable technology and traditional smartphone categories without significant performance gaps, proving that consumer demand supports both innovative form factors and value-oriented offerings equally well in Samsung’s diversified portfolio approach.

TOP FIVE MODELS BASED ON PERCENTAGE AVERAGE 5G PREFERENCE
![image](https://github.com/user-attachments/assets/c148c63d-5749-4021-b924-0c0f5ff29e4a)
![image](https://github.com/user-attachments/assets/02765b73-5bb8-4bce-8e6c-1395bf3bfd1e)
