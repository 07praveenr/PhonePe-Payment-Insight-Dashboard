# PhonePe Payment Insights Dashboard

## 📊 Overview
An interactive Power BI dashboard built to analyze digital payment transactions on the 
PhonePe platform. The dashboard provides a 360° view of transaction volume, value, user 
behavior, and payment success rates to support data-driven decision-making.

## 🎯 Key Features
- **Transaction Overview**: Total transactions, transaction value, unique users, and success rate with MoM growth tracking
- **Trend Analysis**: Monthly transaction volume and value trends (Jan–Dec)
- **User Segmentation**: Age-group-wise contribution (Gen Z, Millennials, 90's, Boomers)
- **Service-wise Breakdown**: Transaction value across Loans, Insurance, Money Transfer, and Recharge/Bills
- **Top Users**: Ranking of top 5 users by transaction value
- **Usage Patterns**: Weekday vs. weekend transaction split
- **Payment Status Filters**: Drill down by Failed, Pending, or Successful transactions
- **Dynamic Insights Panel**: Auto-generated insight callouts (e.g., peak weekday activity)

## 📈 Key Metrics
| Metric | Value |
|---|---|
| Total Transactions | 300K |
| Total Value | ₹3.47Bn |
| Unique Users | 108K |
| Success Rate | 96% |

## 🛠️ Tools Used
- Power BI Desktop
- DAX (measures & calculated columns)
- Data modeling (star schema with Date Table)

## 📂 Files
- `phonepe_payment_insights.pbix` – Power BI report file
- `/screenshots` – Dashboard preview images

## 🔍 Insights
- Weekdays account for ~72% of total transactions vs. ~28% on weekends
- The 90's age segment drives the largest share of transactions (37.4%)
- Loan transactions dominate service-wise value at ₹2.5Bn
