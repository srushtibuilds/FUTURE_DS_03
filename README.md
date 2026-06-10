# FUTURE_DS_03
Power BI dashboard analyzing marketing funnel performance, conversion rates, customer segments, and campaign effectiveness using the Bank Marketing dataset.
# 📊 Marketing Funnel Analysis Dashboard | Power BI

## 📌 Project Overview

This project focuses on analyzing marketing funnel performance to understand how users move through different stages of the customer journey and identify opportunities to improve conversions.

The dashboard was developed as part of an internship task to simulate real-world marketing analytics scenarios commonly encountered in startups, SaaS companies, and digital marketing teams.

The analysis aims to answer key business questions such as:

- Where are customers dropping off in the funnel?
- Which communication channels generate the best results?
- Which customer segments are most likely to convert?
- How does campaign intensity impact conversion rates?
- What strategies can improve overall marketing performance?

---

## 🎯 Objectives

- Analyze customer conversion behavior.
- Identify major funnel drop-off points.
- Evaluate the effectiveness of different contact channels.
- Discover high-performing customer segments.
- Assess campaign performance based on contact frequency.
- Provide actionable recommendations to improve conversions.

---

## 🛠 Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **CSV Dataset**
- **Data Visualization**

---

## 📂 Dataset

The analysis uses the **Bank Marketing Dataset**, which contains customer information collected from direct marketing campaigns conducted by a banking institution.

### Key Variables:

- Age
- Job
- Marital Status
- Education
- Contact Type
- Campaign Contacts
- Previous Campaign Outcome
- Subscription Status (Target Variable)

Target Variable:

```text
y = yes → Converted Customer
y = no → Not Converted
```

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Verified and corrected data types.
- Replaced `"unknown"` values with `"Not Specified"`.
- Retained meaningful business values such as:
  - Negative balances
  - `pdays = -1` (Never contacted previously)
- Created calculated columns and measures for analysis.
- Grouped campaign contacts into meaningful categories.
- Generated custom sorting columns for time-based analysis.

---

## 📈 Dashboard Components

### KPI Cards

- Total Contacts
- Converted Customers
- Conversion Rate
- Qualified Leads

### Funnel Analysis

- Total Contacts
- Qualified Leads
- Converted Customers

### Channel Performance

- Total Customers by Contact Method
- Channel Conversion Rate

### Customer Segmentation

- Conversions by Job Role
- Conversions by Education Level

### Time-Based Analysis

- Monthly Conversion Trends

### Campaign Analysis

- Conversion Rate by Campaign Group:
  - 1–5 Contacts
  - 6–10 Contacts
  - 11+ Contacts

---

## 🔍 Key Insights

- The largest drop-off occurs between qualified leads and converted customers.
- Cellular communication channels outperform telephone campaigns.
- Customers in Management, Technician, and Blue-Collar occupations generate the highest number of conversions.
- Secondary and Tertiary education segments contribute significantly to successful conversions.
- Conversion rates decline as the number of campaign contacts increases.
- Marketing performance varies across different months, indicating seasonal trends.

---

## 💡 Recommendations

- Prioritize cellular communication channels.
- Improve lead nurturing processes to reduce funnel drop-offs.
- Focus marketing efforts on high-converting customer segments.
- Limit excessive customer follow-ups.
- Increase investments during high-performing periods.

---

## 📊 Dashboard Preview

> Add screenshots of your dashboard here.

### Main Dashboard

![Dashboard Screenshot](images/dashboard.png)

---

## 📁 Repository Structure

```
marketing-funnel-analysis-powerbi/
│
├── Dataset/
│   └── bank-full.csv
│
├── Dashboard/
│   └── Marketing Funnel Dashboard.pbix
│
├── Images/
│   └── dashboard.png
│
└── README.md
```

---

## 🚀 Skills Demonstrated

- Marketing Analytics
- Funnel Analysis
- KPI Development
- Power BI Dashboard Design
- DAX Calculations
- Data Cleaning & Transformation
- Business Insight Generation
- Data Storytelling

---

## 👨‍💻 Author

**Nilesh Gujarathi**

Aspiring Data Analyst passionate about transforming raw data into actionable business insights using Power BI and analytics techniques.

---

⭐ If you found this project interesting, feel free to explore the dashboard and share your feedback.
