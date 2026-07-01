# Campaign Performance Analysis | Power BI Dashboard

End-to-End Marketing Campaign Performance Analysis using Power BI, Power Query, DAX, SQL, and Excel.

---

# Table of Contents

- [Project Overview](#project-overview)
- [Business Objectives](#business-objectives)
- [Business Questions Answered](#business-questions-answered)
- [Dataset Description](#dataset-description)
- [Data Model](#data-model)
- [Technology Stack](#technology-stack)
- [Dashboard Pages](#dashboard-pages)
  - [1. Lead Source Performance](#1-lead-source-performance)
  - [2. Source5 Deep Dive](#2-source5-deep-dive)
  - [3. Campaign Analysis](#3-campaign-analysis)
- [Key Business Insights](#key-business-insights)
- [Business Recommendations](#business-recommendations)
- [Reporting Automation Strategy](#reporting-automation-strategy)
- [Project Highlights](#project-highlights)
- [Repository Structure](#repository-structure)
- [Author](#author)

---

# Project Overview

This project presents an end-to-end Marketing Campaign Performance Analysis solution built in Power BI to evaluate the effectiveness of lead acquisition sources across multiple marketing campaigns.

The organization acquires leads from multiple external lead providers. These leads are contacted using AI-powered voice bots and are subsequently classified into outcomes such as Qualified, Intent Qualified, Follow-up, Disqualified, and other campaign statuses based on customer conversations.

The primary objective of this project is to transform raw campaign data into actionable business insights that enable stakeholders to identify high-performing lead sources, compare campaign performance, understand customer qualification patterns, and make data-driven marketing decisions.

The solution demonstrates the complete Business Intelligence workflow, including data cleaning, transformation, data modeling, DAX development, interactive dashboard design, and business insight generation.

---

# Business Objectives

The dashboard was developed to answer the following business objectives:

- Identify the best-performing lead sources based on qualification rate and overall performance.
- Compare lead source performance across different marketing campaigns.
- Perform a detailed analysis of Source5 to understand customer attributes associated with higher qualification rates.
- Evaluate a specific campaign to identify successful lead sources and opportunities for improvement.
- Recommend an automation strategy for recurring business reporting.

---

# Business Questions Answered

### Lead Source Analysis

- Which lead source generates the highest conversion rate?
- Which sources consistently deliver high-quality leads?
- How does each source perform across different campaigns?

### Campaign Analysis

- Which campaign performed best overall?
- Which lead sources contributed most to campaign success?
- What is the distribution of lead statuses within each campaign?

### Source5 Analysis

- Which cities have the highest conversion rates?
- How are credit scores distributed among Source5 leads?
- Which customer age groups demonstrate higher credit utilization?
- What customer characteristics are associated with qualified leads?

---

# Dataset Description

The project uses multiple datasets that are connected through a relational Power BI data model.

| Dataset | Description |
|----------|-------------|
| **Campaign_Data** | Contains all campaign leads along with their final lead status. |
| **Campaign_Source** | Maps each lead to its originating lead source. |
| **Campaign_to_Source5** | Contains additional customer metadata for Source5 leads. |
| **QL_Data** | Includes only Qualified and Intent Qualified leads. |
| **QL_to_Source** | Maps qualified leads to their respective source and category. |
| **QL_to_Source5** | Contains detailed customer attributes for qualified Source5 leads. |

---

# Data Model

The Power BI solution follows a relational data model designed to ensure efficient reporting and optimized performance.

The model includes:

- One-to-many table relationships
- Fact and lookup tables
- Power Query transformations
- Optimized DAX measures
- Clean and scalable semantic model

---

# Technology Stack

| Tool | Purpose |
|-------|----------|
| **Power BI** | Dashboard Development and Data Visualization |
| **Power Query** | Data Cleaning and Transformation |
| **DAX** | KPI Calculations and Business Measures |
| **SQL** | Data Extraction and Validation |
| **Microsoft Excel** | Initial Data Preparation |

---

# Dashboard Pages

---

# 1. Lead Source Performance

![Lead Source Performance](https://github.com/Renuka-1122/Campaign_Performance_Analysis-PowerBI/blob/5faba98cd0325df40b007a7955a4d55945aea61f/Performance%20Breakdown.png)

## Overview

This dashboard evaluates the overall performance of every lead source across all marketing campaigns.

### Dashboard Features

- Conversion Rate by Lead Source
- Campaign-wise Performance Matrix
- Interactive Source Filter
- Campaign Filter
- Lead Status Filter

### Business Purpose

This dashboard enables stakeholders to:

- Identify the highest-performing lead sources.
- Compare source performance across campaigns.
- Evaluate campaign effectiveness.
- Analyze qualification trends using interactive filtering.

### Key Finding

Source2 achieved the highest conversion rate, indicating that it consistently delivered the highest-quality leads among all available lead sources.

---

# 2. Source5 Deep Dive

![Source5 Deep Analysis](https://github.com/Renuka-1122/Campaign_Performance_Analysis-PowerBI/blob/a84e96ceb759b1464f71f7a4fb1799d48fbaab35/Source%205%20Deep%20Analysis.png)

## Overview

This dashboard provides a detailed analysis of Source5 by exploring customer demographics and financial characteristics associated with lead qualification.

### Key Performance Indicators

- Total Leads
- Qualified Leads
- Conversion Rate

### Analysis Included

#### Geographic Performance

- Conversion Rate across the Top 10 Cities

#### Credit Profile Analysis

- Credit Score Distribution
- Customer Credit Profile

#### Customer Analysis

- Average Credit Utilization by Age Group

### Business Purpose

This dashboard helps stakeholders understand:

- Which cities generate higher-quality leads.
- Whether stronger credit profiles improve qualification.
- Which customer age groups represent the most valuable audience.

### Key Findings

- Tumakuru recorded the highest conversion rate among the Top 10 cities.
- Bengaluru recorded the lowest conversion rate within the Top 10 cities.
- Most Source5 leads belong to credit score bands above 700.
- Customers aged 50–54 years demonstrated the highest average credit utilization.

---

# 3. Campaign Analysis

![Campaign Analysis](https://github.com/Renuka-1122/Campaign_Performance_Analysis-PowerBI/blob/d217e3579bb4107b5df4cbe1f1297a5f5c4a77be/Specific%20Campaign%20Analysis.png)

## Overview

This dashboard analyzes the Dean campaign to evaluate its performance and identify the lead sources that contributed most effectively.

### Dashboard Features

- Total Leads by Source
- Conversion Rate by Source
- Lead Status Distribution
- Campaign Performance KPIs

### Business Purpose

This page enables stakeholders to:

- Identify the highest lead-generating sources.
- Compare conversion rates across sources.
- Understand campaign health through lead status analysis.
- Identify follow-up opportunities.

### Key Findings

- Source2 generated the highest number of leads.
- Source2 achieved the highest conversion rate.
- Follow-up represents the largest share of lead statuses, indicating opportunities for additional customer engagement.

---

# Key Business Insights

The analysis generated several actionable business insights.

## Lead Source Performance

- Source2 consistently achieved the highest conversion rate.
- Higher lead volume does not necessarily indicate higher lead quality.
- Certain lead sources consistently outperformed others across multiple campaigns.

## Campaign Performance

- The Dean campaign delivered the strongest overall business performance.
- Successful campaigns were supported by high-performing lead sources.

## Customer Analysis

- Most Source5 leads belonged to credit score bands above 700.
- Customers aged 50–54 years exhibited the highest average credit utilization.
- Geographic location had a measurable impact on conversion performance, with Tumakuru outperforming other major cities.

---

# Business Recommendations

Based on the analysis, the following recommendations are proposed.

## Prioritize High-Performing Lead Sources

Increase investment in Source2, as it consistently delivers the highest-quality leads and strongest conversion performance.

## Optimize Low-Performing Sources

Review lead quality, acquisition strategies, and vendor performance for lower-converting sources to improve overall campaign effectiveness.

## Improve Geographic Targeting

Expand marketing efforts in high-performing cities while investigating opportunities to improve performance in lower-converting regions.

## Focus on High-Quality Customer Segments

Develop campaigns targeting customer profiles with stronger credit characteristics, as these segments demonstrate higher qualification potential.

## Reduce Follow-Up Backlog

Implement automated follow-up workflows to improve conversion from pending leads and reduce manual effort.

---

# Reporting Automation Strategy

To improve reporting efficiency and reduce manual intervention, the following automation strategy is recommended:

- Store campaign data in a centralized SQL database.
- Automate data refresh using the Power BI Service.
- Configure Incremental Refresh for large datasets.
- Publish dashboards through dedicated Power BI Workspaces.
- Implement Row-Level Security (RLS) for secure stakeholder access.
- Schedule automated email subscriptions for recurring reports.
- Configure KPI alerts to notify stakeholders of significant performance changes.

This approach provides near real-time reporting while minimizing manual reporting effort and improving decision-making.

---

# Project Highlights

This project demonstrates practical Business Intelligence skills across the complete analytics lifecycle.

### Data Preparation

- Data Cleaning
- Data Transformation
- Data Validation

### Data Modeling

- Relational Data Model
- Optimized Relationships
- Fact and Lookup Tables

### DAX Development

- Conversion Rate Calculation
- Qualified Lead Metrics
- Campaign KPIs
- Dynamic Measures

### Dashboard Development

- Interactive Visualizations
- Drill-Down Analysis
- Cross-Filtering
- KPI Cards
- Matrix Reports
- Slicers

### Business Analysis

- Lead Source Evaluation
- Campaign Performance Analysis
- Customer Segmentation
- Geographic Analysis
- Business Recommendations

---

# Repository Structure

```
Campaign_Performance_Analysis-PowerBI
│
├── Dataset/
│   ├── Campaign_Data
│   ├── Campaign_Source
│   ├── Campaign_to_Source5
│   ├── QL_Data
│   ├── QL_to_Source
│   └── QL_to_Source5
│
├── Dashboard Screenshots/
│   ├── Lead Source Performance.png
│   ├── Source5 Deep Analysis.png
│   └── Campaign Analysis.png
│
├── Power BI File/
│   └── Campaign Performance Analysis.pbix
│
└── README.md
```

---

# Author

**Renuka**

Power BI Developer | Data Analyst

## Skills

- Power BI
- Power Query
- DAX
- SQL
- Excel
- Data Visualization
- Business Intelligence
- Data Modeling

---

This project demonstrates how Power BI can be used to transform raw marketing campaign data into actionable business insights through effective data modeling, interactive visualizations, and analytical reporting. The dashboard enables stakeholders to monitor campaign performance, optimize lead acquisition strategies, and make informed business decisions using data-driven insights.
