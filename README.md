# Power BI Project Documentation

---

## Page 1. Sales Overview

### Page Objective
Provide a strategic overview of the company’s financial performance over four years. The visualization helps identify growth patterns, seasonal fluctuations, and key points of change in revenue dynamics. This page lays the foundation for further analysis of sales structure, customer behavior, and operational efficiency.

### Key Business Questions
- Are sales growing steadily or fluctuating?
- Which periods record peak and low values?
- Does the seasonal pattern repeat year after year?
- How does the current period compare to the previous one?
- Which months and quarters bring the highest revenue?
- Is there a decline at the beginning of the calendar year?

<img width="1022" height="568" alt="image" src="https://github.com/user-attachments/assets/01f3edb9-f70b-49e1-beb2-a53333bcec68" />

### KPI Block: Key Financial Metrics
The top block of the report displays aggregated results for the full analysis period. Over four years, there were **4,922 orders** covering **793 unique customers**. Total sales amounted to **2.26M**, with **year-over-year (YoY) growth** reaching **47%**, and a **compound annual growth rate (CAGR)** of **251%**. This confirms active business scaling. The highest sales volume was recorded in **December 2018 (Q4)**, when revenue reached **278,417** — a record quarterly result.

### Quarterly Sales Trend with 3-Month Rolling Average
**Objective:** Show quarterly revenue trends with smoothing using a rolling average.  

The 3-month rolling average removes short-term spikes and reveals the underlying trend more clearly. Despite a wave-like structure, each year shows consistent growth towards Q4, indicating pronounced seasonality. Annual peaks grew from 177K in 2015 to 278K in 2018. Q1 each year is typically accompanied by dips, possibly indicating a post-season decline in activity.

<img width="957" height="239" alt="image" src="https://github.com/user-attachments/assets/a0c47c95-14e1-4d9a-bd47-e668cddd8b1e" />

### Sales Growth Compared to Same Month Last Year
**Objective:** Show the relative growth or decline in revenue by month compared to the same month of the previous year.  
The Year-over-Year (YoY %) metric shows the percentage change in revenue compared to the same month last year, allowing for a true measure of growth independent of business scale.  
The analysis shows YoY dynamics are highly uneven: growth alternates with stagnation periods. Exceptional spikes occur in certain months — for example, June 2016 (+505%) and August 2018 (+2621%) — likely due to a low base in the previous year. High growth is consistently recorded in November and December, confirming Q4’s importance.

<img width="952" height="246" alt="image" src="https://github.com/user-attachments/assets/764b5e48-f9f0-48d2-8c4b-80079a6be6da" />

### Key Insights
The company’s sales are steadily growing, especially since 2016, with a clear seasonal pattern. Q4 of each year is the main source of income. Q1 is traditionally weaker, requiring demand stimulation. Combining the KPI block with two key charts provides not only evidence of growth but also an understanding of its rhythm and stability — critical for accurate planning, seasonal strategy adjustments, and targeted marketing.

---

## Page 2. Geographic Sales

### Page Objective
Visualize and analyze the geographical distribution of sales to identify which regions, states, and cities contribute most to revenue. This analysis reveals **geographic profit centers**, low-activity areas, and helps determine strategic expansion directions and coverage optimization.

### Key Business Questions
- Where are the main sales volumes concentrated?
- Which regions (West, East, Central, South) lead in revenue?
- How evenly is revenue distributed geographically?
- Which territories consistently rank at the top year after year?
- Which geographic zones are strategic?
- Where is expansion possible — which areas show weak activity?

<img width="1013" height="570" alt="image" src="https://github.com/user-attachments/assets/79a3cc7f-89dc-41a5-8dc4-953ce155e98e" />

### Sales Distribution by State and Region
**Objective:** Show the territorial structure of revenue by states and regions to identify **growth points**, **concentration risks**, and **development opportunities**.

### Top Revenue States (Top 20% & Top 10% per Region)
**Objective:** Identify and compare the contribution of leading states in each region to total revenue, revealing local growth drivers and the degree of sales diversification.

### Key Insights
- Sales are geographically concentrated. Over **70% of revenue** comes from 10 states (20% of all states), with the top 5 generating **half of total revenue**.
- **California** generates over 20% of total revenue and remains the absolute leader.
- **New York, Texas, Washington, and Pennsylvania** form the second strategic group. Together with California, they generate about **32% of turnover**, indicating high concentration.
- The **West** region is highly dependent on California (about **63% of the region’s revenue** comes from this state).
- **East** is the most balanced region.
- **Central** shows moderate concentration.
- **South** shows low coverage and untapped potential.

The company’s sales depend on a narrow geographic segment, increasing vulnerability to local demand fluctuations. Central and South have growth potential but remain underutilized.

---

## Page 3. Customer Segments & ABC Analysis of Products

<img width="1007" height="571" alt="image" src="https://github.com/user-attachments/assets/5db1513e-b804-4bdc-8ade-8a8b0053c8ec" />

### Page Objective: Customer Segments
Understand which customer segments generate the main revenue and how their behavior changes over time. Identify the core buyers within each segment and key clients for priority service and retention.

### Key Business Questions
- How does revenue change by segment over time?
- Which customers generate the majority of sales in each segment?
- Is there high dependence on individual buyers?
- Which segments and customers are the highest retention priority?

### Page Objective: ABC Analysis of Products
Determine which product subcategories bring the largest share of revenue, based on the Pareto principle (20/80), and check for anomalies requiring extra attention. The ABC classification helps manage the assortment effectively.

### Key Business Questions
- Which products are in the top 20% by revenue?
- How many products generate the majority of profit?
- Which products bring high revenue with low purchase frequency?
- Where is the “long tail” of underperforming items?

<img width="499" height="305" alt="image" src="https://github.com/user-attachments/assets/2440887b-c888-43fe-a5cc-c4b2b8dc8701" />

### Top 10 Customers by Segment
**Objective:** Identify key customers per segment, their share of segment revenue, and dependence level.  
Sean Miller (Home Office) leads with 25.04K, making him a strategic retention client. Consumer sales are more evenly distributed, but Raymond Buch leads with 15.12K. In Corporate, Tamara Chand generates 19.05K, making her a critical revenue source.

<img width="199" height="285" alt="image" src="https://github.com/user-attachments/assets/ad61d68d-30f4-4bad-8c85-192b191b938c" />

### KPI Cards
- Average Sales per Customer: 2.85K  
- Count of Product ID: 1861  

Average revenue per customer is 2.85K — a baseline for evaluating segment and client performance. The 1,861 unique products reflect a wide range for cross-selling and personalized recommendations.

### ABC Analysis by Product Sub-Category
**Objective:** Identify which product subcategories contribute most to revenue and classify them by ABC.  
Only Phones are in category A (~14.5% of revenue). Category B (Chairs, Storage, Tables) brings 10–14%. Category C contains most items (13 of 17), forming a low-revenue “long tail” despite frequent sales.

<img width="249" height="332" alt="image" src="https://github.com/user-attachments/assets/2bae3168-7240-4f7b-afb2-6a9bb40114af" />

### Sales and Frequency Distribution by Sub-Category
**Objective:** Visualize the relationship between the number of orders and revenue for each subcategory to identify underperforming products or, conversely, overloaded ones with low profitability.

Of all 17 subcategories, Phones hold the leading position, being in the blue zone: this product is characterized by both high revenue and high order frequency — it should remain a key focus for the company as a primary revenue driver. Chairs, Tables, and Machines fall into the green zone — these are high-profit products but with less frequent sales, which opens opportunities for marketing enhancement and growth. In the yellow zone of balanced products are Storage and Accessories — they show stable performance and deserve to be maintained in the assortment.

Binders, Paper, Furnishings, and Art are in the white zone: they are frequently purchased but generate low revenue, signaling the need to assess margins and possibly adjust pricing. Conversely, Copiers, Bookcases, Appliances, Supplies, Envelopes, Labels, and especially Fasteners are in the red zone — these products bring low revenue and have limited demand. They are priority candidates for assortment optimization: either by increasing their value or removing them.

<img width="388" height="268" alt="image" src="https://github.com/user-attachments/assets/58f492ff-d207-401b-8e93-211a43bf31fa" />

### Sales Distribution by Category
**Objective:** Show how total revenue is distributed among the main product categories (Technology, Furniture, Office Supplies) to identify key sales directions and their relative significance.

The Technology category accounts for the largest share of revenue thanks to leaders — Phones, Machines, Accessories, and Copiers. Furniture ranks second, with Chairs and Tables generating most of its revenue, while Office Supplies has a broader but less profitable assortment, including Storage, Binders, and Paper. This structure indicates the need to maintain Technology’s leadership positions and develop high-margin Furniture products while optimizing low-margin items in Office Supplies.

<img width="309" height="272" alt="image" src="https://github.com/user-attachments/assets/5c2d6e6b-8771-4394-8eb1-68a60ead88f4" />

---

## Page 4. Forecast & What-If Analysis

### Page Objective
The purpose of this page is to assess the future sales dynamics and model the impact of growth in specific customer segments on total revenue. This analysis makes it possible to determine the contribution of different segments to the overall result and how strategic changes can affect performance in the short and medium term.

### Key Business Questions
- What growth or decline in revenue is expected in the future?
- What seasonal fluctuations can be forecast?
- How will total revenue change if the sales of a specific segment increase by X%?
- Which segments will deliver the greatest growth when additionally stimulated?

### Sales Forecast for the Next Year
**Objective:** Display the sales forecast for the next 6–12 months based on historical data, considering seasonality and long-term trends.

The forecast line shows a steady upward trend with pronounced seasonality, where peaks occur at the end of the year. The uncertainty range (gray zone) indicates a possible spread of actual values, which is important to consider when planning. The most significant sales spikes are expected in November–December, matching historical data. In the summer months, moderate declines are forecast, reflecting traditional seasonal demand fluctuations.

<img width="1015" height="298" alt="image" src="https://github.com/user-attachments/assets/3314763e-8672-4c09-8689-957087785795" />

### Impact of Segment Growth on Total Sales (What-if Analysis)
**Objective:** Allow the user to model the growth of one or more segments (Consumer, Corporate, Home Office) and assess how this will affect total sales and the percentage delta.

When adjusting the growth parameters of segments using sliders, the chart and Delta % metric instantly reflect the new scenario. This makes it easy to determine which segment delivers the greatest effect when growing and whether to focus marketing efforts on it. The tool is particularly useful for strategic planning as it allows comparison of different scenarios and their impact on the long-term trend.

<img width="1009" height="265" alt="image" src="https://github.com/user-attachments/assets/f67e5e63-8865-47ce-b6b3-b8107d3b985c" />


