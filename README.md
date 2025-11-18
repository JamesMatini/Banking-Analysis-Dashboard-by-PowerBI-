# Banking-Analysis-Dashboard-by-PowerBI-
A Power BI risk analytics dashboard for banking that evaluates loan repayment likelihood using interconnected client, banking, gender, advisor, and period data. Includes data cleaning, relationship modeling, and an Engagement Timeframe metric to improve lending decisions and reduce financial risk.

# 🏦 Banking Risk Analytics Dashboard

A comprehensive Power BI dashboard for banking risk assessment and client portfolio analysis, enabling data-driven lending decisions and customer relationship management.

## 📊 Project Overview

This banking analytics solution helps financial institutions minimize lending risks by analyzing client profiles, loan portfolios, and deposit patterns. The dashboard provides insights into client behavior, income distribution, and engagement metrics to support strategic decision-making in credit approval and customer management.

## 🎯 Key Performance Indicators (KPIs)

### Client Metrics
- **Total Clients**: Distinct count of banking clients
- **Engagement Days**: Duration of client relationships with the bank
- **Income Band**: Categorized client income levels (Low, Mid, High)

### Loan Portfolio
- **Total Loan**: Combined bank loans, business lending, and credit card balances
- **Bank Loan**: Sum of traditional bank loans
- **Business Lending**: Loans allocated to small businesses
- **Credit Cards Balance**: Outstanding credit card amounts

### Deposit Analysis
- **Total Deposit**: Combined deposits across all account types
- **Bank Deposit**: Core banking deposits
- **Savings Account**: Interest-bearing deposit accounts
- **Checking Accounts**: Daily transactional accounts
- **Foreign Currency Account**: Non-domestic currency holdings

### Revenue Metrics
- **Total Fees**: Processing and maintenance fees calculated as loan percentage
- **Processing Fees**: Variable fees based on client fee structure

## 🔧 Data Transformation & Calculations

### Data Cleaning & Feature Engineering
- **Engagement Timeframe**: Client relationship duration categorization
- **Engagement Days**: Exact days since client joined (using DATEDIFF)
- **Income Band**: Binned categories (<100K: Low, <300K: Mid, else: High)
- **Processing Fees**: Dynamic calculation based on fee structure (High: 0.05)


📈 Dashboard Structure
## Home Dashboard

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/53c9895e-5d3c-4f23-945e-debf9fd9e15b" />

Executive summary of key banking metrics
Client distribution overview
Quick risk assessment indicators

## Loan Analysis Dashboard

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c53e147d-70cd-4d02-b8f6-0cdc1278934b" />

Portfolio Breakdown: Bank loans vs business lending vs credit cards
Risk Assessment: Client income bands vs loan amounts
Fee Analysis: Revenue from processing fees
Client Segmentation: Loan distribution by client demographics

## Deposit Analysis Dashboard

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/72484481-95c4-4134-983f-8b16a3bf8bae" />

Deposit Composition: Breakdown across account types
Client Engagement: Relationship between engagement days and deposit amounts
Account Distribution: Savings, checking, and foreign currency patterns


## Summary Dashboard

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0b432b68-b2ad-4e1f-99e0-0972720f92c1" />

Consolidated view of banking operations
Key risk indicators and performance metrics
Strategic insights for decision-makers

## 🛠️ Technical Implementation
## Data Model
-- **Primary Tables**: Banking Relationship, Client-Banking, Gender, Investment Advisor, Period
Relationships: Properly linked through primary and foreign keys
Data Types: Optimized for financial calculations and date operations

## Power BI Features
**Interactive Slicers**: Filter by time period, client demographics, banking products
**Conditional Formatting**: Visual indicators for risk levels and performance
**Dynamic Calculations**: Real-time metric updates based on filters
**Data Validation**: Ensured accuracy in financial calculations

🚀 Getting Started
Prerequisites
Microsoft Power BI Desktop
Banking dataset with client and transaction information
Basic understanding of financial metrics
Implementation Steps
Download the .pbix file
Connect to your banking data source
Map data fields to the existing data model
Refresh data connections
Validate calculations and relationships
Explore dashboards through interactive filtering

## 💼 Business Applications
Risk Management
Credit Approval: Assess client repayment likelihood based on profile

Portfolio Monitoring: Track loan performance across segments

Risk Mitigation: Identify high-risk clients and concentrations

Customer Relationship Management
Client Segmentation: Categorize clients by engagement and value

Retention Strategies: Focus on high-value, long-term relationships

Product Optimization: Tailor offerings based on client behavior

Operational Efficiency
Revenue Optimization: Maximize fee income while managing risk

Resource Allocation: Focus efforts on profitable client segments

Performance Tracking: Monitor key banking metrics over time

## 🔍 Key Insights Provided
Client Behavior Analysis
Income distribution across client base

Engagement patterns and relationship duration

Account preference and product usage

Risk Assessment
Loan-to-income ratios across client segments

Fee structure impact on client relationships

Deposit stability indicators

Strategic Planning
Client acquisition and retention patterns

Product performance and cross-selling opportunities

Market segment performance analysis

## 🎯 Future Enhancements
Advanced Analytics
Machine learning integration for default prediction

Real-time risk scoring for new applications

Predictive modeling for client churn

Expanded Scope
Geographic analysis of client distribution

Competitor benchmarking integration

Regulatory compliance reporting

Technical Improvements
Automated data refresh pipelines

Mobile-responsive dashboard design

Advanced visualization with custom visuals

Transforming banking data into actionable risk intelligence for smarter lending decisions and enhanced customer relationships.
