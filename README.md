# Chaiiwala -- Customer Experience Business Intelligence Platform & Feedback Integrity Platform 

### Introduction

Chaiiwala is a UK-based Indian/Pakistani street food café chain (Coffee Shop), established in Leicester in 2015. Known for its signature Karak Chaii, it serves authentic Indian drinks, street food, and fusion meals in a relaxed, community-focused atmosphere. The brand has expanded to over 140 locations worldwide and have 114 stores in UK alone.

---

### An End-to-End Business Intelligence Solution for Retail/café Customer Experience, Operational Performance & Data Quality Assurance

---

## Executive Summary

Customer experience is one of the most important drivers of success within the Quick Service Restaurant (QSR) industry. Every interaction—from food quality and customer service to restaurant cleanliness and promotion awareness—influences customer loyalty, brand reputation and long-term profitability.

This project presents an end-to-end Business Intelligence solution designed to measure customer experience while ensuring that management decisions are based on reliable and trustworthy customer feedback.

Unlike traditional customer satisfaction dashboards, this solution introduces two complementary analytical frameworks:

**Customer Experience Intelligence**, which measures operational performance using a weighted Customer Experience Index (CXI).
**Customer Feedback Integrity**, which evaluates the quality, completeness and authenticity of customer feedback before it is used for decision-making.

The solution enables management to identify operational issues, benchmark store performance, understand regional trends, detect potentially unreliable survey responses and prioritise improvement initiatives using data-driven insights.

---

## Why Customer Feedback Matters

Customer feedback is one of the most valuable strategic assets available to any retail business. It provides direct insight into customer expectations, operational performance and overall brand perception.

When analysed correctly, customer feedback enables organisations to:

* Improve customer satisfaction and loyalty.
* Protect and strengthen brand reputation.
* Identify operational weaknesses before they impact sales.
* Measure the effectiveness of promotions and customer engagement.
* Improve service consistency across multiple locations.
* Support evidence-based decision making.
* Maintain a competitive advantage through continuous improvement.

However, customer feedback is only valuable if it is accurate, authentic and trustworthy. Poor-quality or manipulated feedback can result in misleading insights and ineffective business decisions. For this reason, this project treats **Data Quality & Feedback Integrity** as an equally important business objective alongside customer experience measurement.

---

## Business Challenge

Multi-site retail organisations / café chain often receive thousands of customer feedback responses across different locations. While valuable, this information is frequently fragmented and difficult to analyse consistently.

Key business challenges include:

### Customer Experience

* Which stores consistently deliver the best customer experience?
* Which stores require operational improvement?
* Which customer experience factors most influence customer satisfaction?
* How does customer experience affect revenue performance?
* Which regions consistently outperform others?

### Customer Behaviour

* How do customers interact with the feedback process?
* Are customers aware of current promotions?
* Which survey questions receive the lowest ratings?
* Are customers abandoning surveys?

### Data Quality & Integrity

* Is customer feedback reliable enough to support business decisions?
* Can suspicious survey responses be identified?
* Which stores have the highest proportion of skipped or timed-out surveys?
* How can management improve confidence in customer feedback data?

---

## Project Objectives

The primary objective of this project is to develop a Business Intelligence platform capable of transforming customer feedback into actionable business intelligence while maintaining confidence in the quality of the underlying data.

The solution was designed to:

* Measure customer experience consistently across all stores.
* Develop a weighted Customer Experience Index (CXI).
* Benchmark store and regional performance.
* Identify operational strengths and weaknesses.
* Analyse the relationship between customer experience and revenue.
* Monitor customer behaviour throughout the survey process.
* Measure customer feedback quality and integrity.
* Detect potentially unreliable or manipulated survey responses.
* Support proactive operational decision making.

---

## Solution Overview

The solution consists of two integrated analytical frameworks.

### 1. Customer Experience Intelligence

Measures operational performance across six key customer experience categories:

* Customer Service
* Product Quality
* Stock Availability
* Cleanliness
* Seating Capacity
* Promotion Awareness

These measures are combined into a weighted **Customer Experience Index (CXI)** to provide a standardised performance score for every store.

---

### 2. Customer Feedback Integrity

To improve confidence in management reporting, the platform evaluates customer feedback quality using several integrity indicators:

* Survey Completion Rate
* Skip Rate
* Timeout Rate
* Data Trust Score
* Potential Survey Manipulation Indicators

These measures help distinguish reliable customer feedback from responses that may require further investigation before influencing operational decisions.

---

## Technology Stack

| Layer                  | Technology                   |
| ---------------------- | ---------------------------- |
| Database               | SQL Server                   |
| Data Warehouse         | Star Schema                  |
| ETL & Data Preparation | Power Query                  |
| Data Modelling         | Power BI                     |
| Business Logic         | DAX                          |
| Reporting              | Power BI Executive Dashboard |

---

## Data Model

The solution follows a Star Schema design consisting of:

### Dimension Tables

* DimDate
* DimStore
* DimQuestions

### Fact Tables

* FactCustomerFeedback
* FactSales

This model provides a scalable analytical structure capable of supporting operational, financial and customer experience reporting.

---

## Dashboard Overview

The solution consists of seven interactive dashboard pages:

| Page                          | Business Purpose                                 |
| ----------------------------- | ------------------------------------------------ |
| Executive Overview            | Executive KPI monitoring                         |
| Regional Intelligence         | Regional performance comparison                  |
| Store Performance             | Individual store benchmarking                    |
| Root Cause Analysis           | Identify operational drivers of poor performance |
| Revenue & Customer Experience | Relationship between CXI and revenue             |
| Customer Behaviour            | Customer interaction and survey analysis         |
| Executive Action Centre       | Prioritised management actions                   |

---

## Key Performance Indicators

### Customer Experience KPIs

* Customer Experience Index (CXI)
* Customer Service Score
* Product Quality Score
* Stock Availability Score
* Cleanliness Score
* Seating Score
* Promotion Awareness Score
* Customer Satisfaction Score
* Store Ranking
* Revenue at Risk

---

### Data Quality & Integrity KPIs

* Data Trust Score
* Survey Completion Rate
* Skip Rate
* Timeout Rate
* Potential Survey Manipulation Indicator

---

## Business Value

The platform enables management to:

* Benchmark customer experience across all stores.
* Identify operational issues requiring immediate intervention.
* Prioritise improvement activities using data-driven insights.
* Measure the financial impact of customer experience.
* Improve consistency across regional operations.
* Increase confidence in customer feedback through data quality monitoring.
* Support continuous operational improvement.
* Strengthen customer loyalty and brand reputation.

---

## Future Enhancements

Potential future developments include:

* Live customer feedback integration.
* QR code survey collection.
* AI-powered sentiment analysis.
* Predictive customer satisfaction modelling.
* Real-time executive alerts.
* Franchise performance benchmarking.
* Mobile executive dashboard.
* Integration with POS and CRM systems.

---

## Skills Demonstrated

This project demonstrates practical experience in:

* Data Warehouse Design
* Star Schema Modelling
* SQL Server
* Power Query (ETL)
* Data Cleaning & Transformation
* Advanced DAX
* Power BI Dashboard Development
* KPI Design
* Executive Reporting
* Data Storytelling
* Customer Experience Analytics
* Data Quality & Integrity Monitoring
* Business Intelligence Solution Design
* Prompt Engnieering using AI

---

## Author

**Ahsan ul Haq**

**Project:** Chaiiwala Customer Experience Business Intelligence & Feedback Integrity Platform

**Purpose:** Independent Business Intelligence Portfolio Project

**Technology:** SQL Server • Power Query • Power BI • DAX

**Status:** Portfolio Demonstration Project

---

## License
- This project is intended for educational and portfolio purposes.

---

### Disclaimer

> **This is an independent portfolio project created for demonstration purposes only.** The dashboard, data model, analytics solution and documentation were independently designed and developed by **Ahsan ul Haq**. The dataset used throughout this project is **synthetically generated** to simulate realistic retail operations and customer feedback and does **not** contain proprietary, confidential or internal business data from Chaiiwala. Chaiiwala has not commissioned, endorsed or reviewed this project.

---

