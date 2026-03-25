**Call Center Performance Dashboard**

**Project Overview**
This Power BI project provides a comprehensive analysis of call center operations, focusing on agent performance, customer satisfaction, and operational efficiency. The dashboard transforms raw interaction logs into actionable insights to help floor managers and stakeholders optimize service levels.
**Data Architecture**
The report is built on a structured dataset containing dimensions for time, agents, and call categories.
**Key Data Entities:**
Call Logs: Fact table containing unique identifiers for every interaction, including timestamps and durations.
Agent Profiles: Metadata regarding agent names and department assignments.
Resolution Tracking: Boolean and categorical data indicating whether issues were resolved during the first contact.
Sentiment/Ratings: Quantitative measures of customer satisfaction (CSAT) scores.
**Technical Features & DAX Measures**
The dashboard utilizes advanced Power BI functionalities and Data Analysis Expressions (DAX) to provide real-time performance tracking:
Total Volume Analysis: Measures to calculate total calls, answered vs. abandoned rates, and peak hour traffic.
**Performance Metrics:**
Average Handling Time (AHT): Measures the mean duration of calls to identify efficiency gaps.
CSAT Score: Weighted average of customer feedback.
Resolution Rate: Percentage of calls marked as "Resolved" to track effectiveness.
Time Intelligence: Comparison of performance across days, weeks, and months to identify seasonal trends.
**Visualization Highlights**
Interactive Slicers: Users can filter the entire report by Agent, Topic (e.g., Billing, Technical), and Date Range.
KPI Scorecards: High-visibility cards displaying critical metrics at a glance.
Trend Charts: Line and area charts visualizing call distribution throughout the day to assist in staffing shifts.
Heat Maps: (Optional/Included) Identifying geographic or departmental hotspots for high call volumes.
**Tools Used:**
Power BI Desktop: Report authoring and visualization.
Power Query (M): Data ETL (Extract, Transform, Load) for cleaning and formatting interaction logs.
DAX: Advanced calculations for performance KPIs.
