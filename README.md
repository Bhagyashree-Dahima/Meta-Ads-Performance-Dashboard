# Meta-Ads-Performance-Dashboard
***🧠 Project Overview***

This Power BI project analyzes Meta Ads Performance Data to evaluate campaign effectiveness, optimize ad spend, and uncover insights that drive marketing ROI.
The goal is to create an interactive dashboard that helps marketing teams make data-driven decisions and track key metrics like impressions, reach, clicks, CTR, and conversions.

**Business Objective**

The business needs a performance tracking report for advertising campaigns running on Facebook and Instagram. The report will provide visibility into campaign reach, engagement, conversions, and budget utilization. This will enable the marketing team to:
•Identify the most effective platform (Facebook vs Instagram).
•Track campaign ROI and optimize budget allocation.
•Understand audience engagement patterns.
Scope of the Report
•In Scope:
      o Campaigns running on Facebook and Instagram only.
•Out of Scope:
      o Other platforms (Messenger, Audience Network).
      o Organic engagement (only paid ads will be included). 

<img width="1184" height="684" alt="Screenshot 2025-10-24 092346" src="https://github.com/user-attachments/assets/ea0c8f73-5e35-4fb7-a3a6-040fa897783f" />


<img width="1177" height="679" alt="Screenshot 2025-10-24 092310" src="https://github.com/user-attachments/assets/123fe957-a554-4c28-931d-c6a9e749e152" />




***Charts Requirements:***
**1. Target Gender – Donut Chart**
A donut chart will visualize performance split by target gender (from the ads table).
•The metric displayed (e.g., Impressions, Clicks, Purchases) will change dynamically via the parameter.
•Purpose: Identify which gender segment contributes most to the selected metric.

**2. Target Age Group – Bar Chart**
A bar chart will show engagement across age groups defined in the ads table.

•Each bar will represent one age group.

•The metric displayed will switch dynamically.

•Purpose: Highlight which age group is most responsive to campaigns.

**3. Country – Map**
A map visualization will display performance by country (from the users table).

•Bubble size or color intensity will represent the selected metric.

•Purpose: Provide a geographic view of campaign reach and engagement.

**5. Calendar Month – Calendar Heat Map**
A calendar heat map will plot performance at the monthly level, based on the timestamp field in ad_events.

•Darker shades will indicate higher activity.

•Purpose: Detect seasonal trends, peak ad months, and low-activity periods.

**6. Weekly Trend – Stacked Column by Ad Type**
A stacked column chart will display weekly performance trends.

•X-axis → Week number (from the Date Table linked to ad_events).

•Stacks → Different ad_type values (from the ads table).

•Y-axis → Selected metric.

•Purpose: Compare ad type contributions over weeks.

**7. Hourly Trend – Area Chart**
An area chart will show activity by hour of day (from ad_events[time_of_day]).

•X-axis → Hour of the day (0–23).

•Y-axis → Selected metric.

•Purpose: Understand user activity patterns throughout the day.

**8. Ad Type – Matrix**
A matrix visualization will show the selected metric across ad types and possibly break down further by platform (Facebook vs Instagram).
•Rows → Ad Types.
•Columns → Platforms or other campaign dimensions.
•Values → Selected metric.
•Purpose: Compare performance across ad formats and platforms side by side.

***DASHBOARD INSIGHTS KPI ***

***KPI Metrics***


•Impressions: 216K: Total times the ads were shown. Good reach.

•Clicks: 25.4K: Number of people who clicked on the ads.

•Shares: 1.3K, Comments: 2.6K: Indicators of organic engagement (beyond paid reach).

• Purchases (Conversions): 1.3K: Real customer acquisitions from ads.

• Engagements: 29K: Sum of clicks, likes, shares, comments.

• CTR (Click-Through Rate): 11.76%: Strong performance (above industry average ~1-2%). Ads are very attractive.

• Engagement Rate: 13.56%: Very healthy; content resonates with the audience.

• Conversion Rate: 5.21%: Out of all clicks, 5.21% converted into purchases. Good but could improve with landing page optimization.

• Purchase Rate: 0.61%: Out of impressions, only 0.61% resulted in purchases. Low conversion funnel efficiency (room to optimize).

• Total Budget: 2.5M: Total ad spends.

• Avg Budget per Campaign: 50.7K: Suggests multiple campaigns were run.

Insight: Ads are performing strongly in visibility and engagement, but actual purchase efficiency is weak: need to optimize targeting/landing pages.

• High CTR (11.76%) and Engagement Rate (13.56%) → clearly indicate that the ad creatives, messaging, and targeting at the top of the funnel are very effective. People are interested enough to click, like, share, or comment.

• Low Purchase Rate (0.61%) and only 1.3K conversions out of 216K impressions → shows a sharp drop-off in the lower funnel. This is a classic case of "awareness and interest" being strong but "action (purchase)" being weak.

***Engagement Breakdown***

**• By Gender (Donut Chart)**
o Female: 13K (43%)

o Male: 6K (22%)

o Other/Not Specified: 10K (35%) Females engage more than males; campaigns could be tailored toward female audiences.

• By Target Age (Bar Chart)

o Peak engagement: 20–30 age group (especially early 20s).

o Drops significantly after 35+. Primary audience = Young adults.
Insight: Target ads towards females aged 18–30 for better ROI.
Geographic Distribution

• Top Engaged Countries

o US, India, Brazil, Germany, UK are major contributors..
Insight: Focus campaigns in India & US (high potential, high engagement), and premium campaigns in Germany/UK (better conversion potential due to higher purchasing power). Time-Based Trends

• Weekly Engagement Trend (Stacked Bar)

o Fairly consistent across weeks, with no sharp drop.

o Steady engagement shows ads maintain attention.

• Hourly Engagement Trend (Line Chart)

o Peaks around late afternoon & evening (~15–20 hours).

o Lowest engagement early morning (~0–5 hours).
Insight: Schedule ad delivery during afternoons & evenings for maximum impact.

***Calendar View***
•Engagements are mapped to days in June.

•Certain dates (like 19th–21st, 25th–27th) show higher highlights. Campaign activity peaks on specific days, possibly due to launches/promotions.
Insight: Weekly promotions/events significantly drive engagement.
Analysis by Ad Type (Bottom-Right Table)

Video ads have the highest CTR, CR, ER (best-performing). Stories ads also perform strongly with higher impressions. Images/Carousels have decent performance but slightly lower conversions.
Insight: Focus budget more on Video & Story ads for better ROI.
Final Insights & Recommendations
1.Strong awareness & engagement (high CTR & ER), but low purchase funnel efficiency : need better conversion strategy.

2.Target audience: Females, 18–30, especially in India & Brazil.

3.Best ad formats: Video > Stories > Carousel/Image.

4.Timing: Schedule ads in the afternoon & evening slots.

5.Budget Optimization: Shift more spend to high-performing geographies and ad formats.

6.Action: Improve landing pages, offers, retargeting campaigns to lift purchase rate.


Author- Bhagyashree Dahima
