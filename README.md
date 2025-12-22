# American-Media-Hub-Performance-Dashboard-
This project focuses on transforming raw media campaign data into a structured, interactive dashboard that supports performance monitoring and decision-making. The dashboard helps stakeholders quickly understand how media spend translates into impressions, clicks, and conversions across platforms, regions, devices, and campaign objectives. 

Project Overview
This project focuses on transforming raw media campaign data into a structured, interactive dashboard that supports performance monitoring and decision-making. The dashboard helps stakeholders quickly understand how media spend translates into impressions, clicks, and conversions across platforms, regions, devices, and campaign objectives.
The goal was not just to visualize data, but to use analytics to identify inefficiencies, performance gaps, and optimization opportunities.

Objective
To monitor and analyze media campaign performance across platforms, regions, devices, and campaign objectives using key marketing KPIs. The dashboard enables fast identification of trends, underperforming areas, and cost inefficiencies that affect overall campaign effectiveness.
Key Performance Indicators (KPIs)
Total Spend
Total Impressions
Total Clicks
Total Conversions
These KPIs provide a high-level summary of campaign activity and outcomes.
Dashboard Structure

Page 1 – Home (Overview)
This page answers the question: “What is happening across our media campaigns?”
Visuals included:
Spend by Platform
Impressions & Clicks by Month
Conversions by Region
Spend and Conversions by Campaign Objective
This page is designed for quick performance checks and high-level trend monitoring.

Page 2 – Deep Dive Insights
This page answers the question: “Where are the problems and why?”
Visuals and metrics included:
Spend by Region
Platform Performance by CPA
Clicks by Region
Campaign-level and Total CTR
Total CPA
Total Spend
This page focuses on identifying inefficiencies and performance gaps.

Problems Addressed Using the Dashboard
1. Identifying Wasted Spend
By comparing Total Spend with Conversions across platforms, regions, and campaign objectives, the dashboard highlights areas where high spend does not translate into meaningful results.
Solved with:
Spend vs Conversions visuals
Platform performance by CPA
2. Understanding Engagement Quality
High impressions alone do not guarantee performance. By analyzing Impressions vs Clicks and CTR, the dashboard reveals where audience engagement is weak despite high visibility.
Solved with:
Impressions & Clicks by Month
Campaign-level and Total CTR
3. Regional Performance Gaps
The dashboard shows how different regions contribute differently to clicks and conversions, helping identify markets that are underperforming or over-consuming budget.
Solved with:
Conversions by Region
Spend by Region
Clicks by Region
4. Campaign Objective Effectiveness
Campaign objectives should align with expected outcomes. The dashboard compares spend and conversions across objectives to reveal mismatches between intent and performance.
Solved with:
Spend and Conversions by Campaign Objective
5. Cost Efficiency Analysis
Using CPA, CPC, and CPM calculations, the dashboard evaluates how efficiently budget is being spent across platforms and campaigns.
Solved with:
Platform performance by CPA
Total CPA KPI

Data Model
Fact Table: Media campaign dataset containing Date, Platform, Region, Device, Campaign Objective, Impressions, Clicks, Spend, Conversions, CTR, CPC, CPM, CPA, and Months.
Dimension Tables: Platform, Region, Device, and Campaign Objective, each with index columns to support a star-schema model.

Key Features
Clean star-schema data model for accurate filtering and performance
Interactive KPI cards for instant performance checks
Visuals designed to expose trends and inefficiencies
Page navigator for smooth movement between overview and insights
Glossary text box explaining key marketing metrics and formulas

Assumptions and Calculations
Data was cleaned to remove duplicates, missing values, and invalid records.
Metrics were calculated using standard marketing formulas:
CTR = Total Clicks ÷ Total Impressions
CPC = Total Spend ÷ Total Clicks
CPM = (Total Spend × 1000) ÷ Total Impressions
CPA = Total Spend ÷ Total Conversions

![1002196750](https://github.com/user-attachments/assets/4f843099-ad18-4b00-b9b6-08d351b91322)
![1002196749](https://github.com/user-attachments/assets/34a6df2b-aaee-40a1-a114-a699614f9707)

Conclusion
This dashboard demonstrates how structured data modeling and thoughtful visual design can turn raw media data into actionable insights. It provides decision-makers with clarity on performance, highlights inefficiencies, and supports data-driven media optimization.
