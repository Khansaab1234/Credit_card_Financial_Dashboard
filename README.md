💳 Credit Card Financial & Customer Analytics Dashboard

An end-to-end Financial Data Analytics project that processes credit card transaction logs and customer demographic profiles using SQL and transforms them into interactive business intelligence reports (Power BI / Tableau).

This project provides real-time visibility into revenue streams, transaction volumes, delinquency risks, and customer acquisition/spending trends to help financial institutions make data-backed strategic decisions.

📌 Table of Contents

Project Overview

Key Metrics & KPIs

Tech Stack

Repository Structure

Data Architecture & Pipeline

Key Business Insights

Actionable Recommendations

How to Use & Explore

Author & Connect

🎯 Project Overview

Financial institutions require continuous monitoring of portfolio health, customer credit limits, and usage patterns to mitigate risk and increase profitability.

Objectives:

Data Ingestion & Transformation: Ingest raw customer records and card transaction records using structured SQL pipelines.

Portfolio Health Monitoring: Track overall revenue, interest earned, total transaction volume, and delinquency rates.

Customer Segmentation: Understand customer behavior categorized by age group, income tier, education, gender, and job domain.

Actionable Business Intelligence: Deliver actionable executive dashboards for both Customer Demographics and Transaction Performance.

📊 Key Metrics & KPIs

Overall Revenue: Total fee charges, interest earned, and transaction commissions.

Total Transaction Amount (Total Volume): Cumulative value transacted across merchant categories.

Total Transaction Count: Frequency of card usage.

Delinquency Rate: Percentage of customers defaulting or overdue on monthly dues.

Card Type Contribution: Performance breakdown across Blue, Silver, Gold, and Platinum tiers.

🛠️ Tech Stack

Database & Querying: SQL (PostgreSQL / MySQL / SQL Server)

Data cleaning, JOIN operations, aggregations, conditional metrics, and CTEs.

Business Intelligence & Reporting: Power BI / Tableau

Interactive KPI cards, donut charts, bar plots, trend charts, and matrix tables.

Data Sources: Structured CSV datasets (credit_card2.csv, customer.csv).

📁 Repository Structure

├── credit_card2.csv                          # Credit card transactional logs & metrics
├── customer.csv                              # Customer demographic profile records
├── SQL Query - Financial Dashboard Data.sql   # SQL scripts for staging, aggregation & KPIs
├── credit_card_Customer_report.pdf           # Exported visual dashboard (Customer focus)
├── credit_card_Transaction_report.pdf        # Exported visual dashboard (Transaction focus)
└── README.md                                 # Project documentation


🔄 Data Architecture & Pipeline

[Raw CSV Datasets] ──> [SQL Database Staging] ──> [Transformation & Aggregations] ──> [BI Dashboard Reports]


Extraction & Loading: Raw transaction and customer tables imported into SQL database tables.

Transformation:

Handled null/missing attributes.

Calculated customer age groups and salary brackets.

Aggregated quarterly trends, total spending amounts, and delinquency indicators.

Visualization: Built dynamic dashboards focusing on:

Transaction Report: Quarterly growth, expenditure types (bills, grocery, travel, entertainment), and card-type distribution.

Customer Report: Revenue by income segments, education level, gender ratio, and top contributing regions.

💡 Key Business Insights

Customer Spending Demographics:

High-income segment and prime working age group (30–50 years) account for the highest transactional value.

Blue Card holders constitute the majority of active accounts, while Gold and Platinum cards yield higher average transaction sizes.

Transaction Behavior:

Major spends are concentrated around Bill Payments, Groceries, and Travel bookings.

Swipe and Chip-and-PIN transactions lead over online card-not-present (CNP) channels in sheer volume.

Risk & Delinquency:

Delinquency is closely clustered around specific income thresholds and lower-utilization groups, suggesting targeted credit limit revisions.

🚀 Actionable Recommendations

Card Upgrade Incentives: Target active Blue Card users showing consistent spending growth with automated upgrades to Silver/Gold to capture higher merchant interchange fees.

Delinquency Control: Implement automated alerts for payment delays among early-risk cohorts identified in the customer dashboard.

Category Promotions: Partner with travel and grocery aggregators to introduce targeted cashback campaigns, driving higher frequency during off-peak quarters.

⚙️ How to Use & Explore

1. Database Setup & Queries

Open your SQL editor (e.g., pgAdmin, MySQL Workbench, or SSMS).

Run the script:

-- Run the SQL query file
SOURCE SQL Query - Financial Dashboard Data.sql;


2. View Visual Reports

Open credit_card_Customer_report.pdf to examine customer segment distributions and demographic insights.

Open credit_card_Transaction_report.pdf to view revenue benchmarks, quarterly trend lines, and channel performance.

👤 Author & Connect

Author: Farhan Khan

LinkedIn: https://www.linkedin.com/in/khansaab047/

GitHub: https://github.com/Khansaab1234

Email: fk0864995@gmail.com
