# Meta-Ads-Performance-Dashboard
🧠 Project Overview

This Power BI project analyzes Meta Ads Performance Data to evaluate campaign effectiveness, optimize ad spend, and uncover insights that drive marketing ROI.
The goal is to create an interactive dashboard that helps marketing teams make data-driven decisions and track key metrics like impressions, reach, clicks, CTR, and conversions.

Business Objective
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




Charts Requirements:
1. Target Gender – Donut Chart
A donut chart will visualize performance split by target gender (from the ads table).
•The metric displayed (e.g., Impressions, Clicks, Purchases) will change dynamically via the parameter.
•Purpose: Identify which gender segment contributes most to the selected metric.

2. Target Age Group – Bar Chart
A bar chart will show engagement across age groups defined in the ads table.
•Each bar will represent one age group.
•The metric displayed will switch dynamically.
•Purpose: Highlight which age group is most responsive to campaigns.

3. Country – Map
A map visualization will display performance by country (from the users table).
•Bubble size or color intensity will represent the selected metric.
•Purpose: Provide a geographic view of campaign reach and engagement.

5. Calendar Month – Calendar Heat Map
A calendar heat map will plot performance at the monthly level, based on the timestamp field in ad_events.
•Darker shades will indicate higher activity.
•Purpose: Detect seasonal trends, peak ad months, and low-activity periods.

6. Weekly Trend – Stacked Column by Ad Type
A stacked column chart will display weekly performance trends.
•X-axis → Week number (from the Date Table linked to ad_events).
•Stacks → Different ad_type values (from the ads table).
•Y-axis → Selected metric.
•Purpose: Compare ad type contributions over weeks.

7. Hourly Trend – Area Chart
An area chart will show activity by hour of day (from ad_events[time_of_day]).
•X-axis → Hour of the day (0–23).
•Y-axis → Selected metric.
•Purpose: Understand user activity patterns throughout the day.

8. Ad Type – Matrix
A matrix visualization will show the selected metric across ad types and possibly break down further by platform (Facebook vs Instagram).
•Rows → Ad Types.
•Columns → Platforms or other campaign dimensions.
•Values → Selected metric.
•Purpose: Compare performance across ad formats and platforms side by side.



