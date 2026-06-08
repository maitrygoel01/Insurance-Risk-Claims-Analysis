# 🛡️ Insurance Risk & Claims Analysis Dashboard

## 📌 Project Overview

Insurance Risk & Claims Analysis Dashboard is an end-to-end Power BI solution designed to analyze insurance policyholders, claim patterns, risk factors, and demographic trends. The dashboard provides a centralized view of insurance portfolio performance, enabling insurers, risk analysts, and business stakeholders to monitor claim behavior, identify high-risk segments, evaluate customer demographics, and optimize underwriting decisions through interactive visual analytics.

The project analyzes insurance policies and claims across customer demographics, vehicle characteristics, geographic coverage zones, education levels, marital status, and claim frequencies to uncover actionable business insights.

---

# 🎯 Business Problem

Insurance companies face several challenges in managing risk and claim exposure, including:

* Identifying high-risk customer segments
* Understanding claim frequency patterns
* Monitoring claim costs across demographics
* Evaluating geographic risk exposure
* Assessing vehicle-related claim trends
* Improving underwriting strategies
* Optimizing policy pricing and risk management

This dashboard transforms insurance and claims data into actionable insights that support data-driven risk assessment and business decision-making.

---

# 📊 Insurance Performance KPIs

| KPI                     | Value           |
| ----------------------- | --------------- |
| Total Policies          | 37,542          |
| Total Claim Amount      | $187.8M         |
| Average Claim Frequency | 0.5             |
| Male Policyholders      | 18.7K           |
| Female Policyholders    | 18.8K           |
| Coverage Zones          | 5               |
| Vehicle Makes Analyzed  | Multiple Brands |
| Age Groups Analyzed     | 6               |

---

# 🔷 1. Executive Insurance Overview

The Executive Dashboard provides a consolidated view of insurance portfolio performance and claim exposure.

### Key Insights

### Portfolio Overview

* Total Policies: 37,542
* Total Claim Amount: $187.8M
* Average Claim Frequency: 0.5

### Customer Analytics

* Male Policyholders: 18.7K
* Female Policyholders: 18.8K
* Demographic Risk Analysis

### Claim Analytics

* Claim Amount Distribution
* Claim Frequency Trends
* High-Risk Segment Identification

### Coverage Analysis

* Geographic Risk Exposure
* Vehicle Risk Analysis
* Customer Profile Assessment

---

# 🔷 2. Policyholder Demographic Analysis

The Demographics Dashboard focuses on customer characteristics and claim behavior.

### Business Questions Answered

* Which age groups generate the highest claim amounts?
* How does claim exposure vary by gender?
* Which customer segments pose greater insurance risk?
* How do demographic factors influence claim costs?

### Analysis Performed

### Gender Distribution

Policyholders are segmented into:

* Male: 18.7K
* Female: 18.8K

### Age Group Analysis

Age categories include:

* 15–25
* 26–35
* 36–45
* 46–55
* 56–65
* 66–75

### Key Findings

Highest claim amounts are concentrated within:

* 26–35 Age Group
* 36–45 Age Group
* 46–55 Age Group

### Business Value

* Improves risk segmentation.
* Supports targeted policy pricing.
* Enhances underwriting decisions.

---

# 🔷 3. Vehicle Risk Analysis

The Vehicle Dashboard evaluates claim patterns associated with vehicle characteristics.

### Analysis Performed

### Claim Amount by Car Use

Vehicle usage categories include:

* Private Use
* Commercial Use

### Key Findings

* Private vehicles account for the majority of claim amounts.
* Commercial vehicles contribute a smaller but significant share of total claims.

### Claim Amount by Car Make

Vehicle manufacturers analyzed include:

* Ford
* Chevrolet
* Dodge
* Toyota
* GMC
* Mitsubishi
* Mazda
* Pontiac
* Mercedes-Benz
* Volkswagen
* Nissan

### Business Value

* Identifies high-risk vehicle categories.
* Supports premium pricing optimization.
* Enhances vehicle-specific underwriting policies.

---

# 🔷 4. Geographic Risk Analysis

The Geographic Dashboard analyzes claims across coverage zones.

### Business Questions Answered

* Which regions generate the highest claim costs?
* How is risk distributed geographically?
* Which coverage zones require closer monitoring?

### Analysis Performed

### Coverage Zones

Risk exposure is analyzed across:

* Urban
* Highly Urban
* Rural
* Suburban
* Highly Rural

### Geographic Claim Distribution

Measures:

* Total Claim Amount
* Risk Concentration
* Regional Exposure

### Business Value

* Supports geographic pricing strategies.
* Improves regional risk management.
* Identifies high-risk coverage areas.

---

# 🔷 5. Claim Trend Analysis

The Claims Dashboard focuses on historical claim patterns and claim severity.

### Analysis Performed

### Claim Amount by Vehicle Year

Tracks claim amounts across vehicle manufacturing years.

### Trend Analysis

Measures:

* Claim Cost Trends
* Vehicle Age Impact
* Historical Claim Development

### Key Findings

* Certain vehicle years demonstrate higher claim exposure.
* Older vehicles may contribute to elevated claim costs due to maintenance and accident risks.

### Business Value

* Supports vehicle age risk modeling.
* Improves claim forecasting.
* Enhances actuarial analysis.

---

# 🔷 6. Family & Lifestyle Risk Analysis

The Lifestyle Dashboard evaluates household-related risk factors.

### Analysis Performed

### Claim Amount by Kids Driving

Categories analyzed:

* No Young Drivers
* One Young Driver
* Two Young Drivers
* Three Young Drivers

### Key Findings

* Households without young drivers account for the highest total claim amounts due to portfolio concentration.
* Driver composition influences claim exposure.

### Business Value

* Supports household-level risk assessment.
* Improves premium calculation models.
* Enhances underwriting accuracy.

---

# 🔷 7. Education & Marital Status Analysis

The Education Dashboard examines how social and demographic factors relate to insurance claims.

### Analysis Performed

### Education Levels

* High School
* Bachelors
* Masters
* PhD

### Marital Status Categories

* Single
* Married
* Divorced
* Separated

### Claim Analysis

Measures claim amounts across combinations of:

* Education Level
* Marital Status

### Key Findings

* Single policyholders contribute the highest claim amounts across several education categories.
* Married individuals represent a significant share of claim exposure.
* Educational background shows variation in claim behavior.

### Business Value

* Supports advanced customer segmentation.
* Improves pricing strategies.
* Enhances risk prediction models.

---

# 📈 Key Business Insights

## Portfolio Insights

* The insurance portfolio consists of over 37K active policies.
* Total claims exceed $187M, indicating substantial risk exposure.

## Demographic Insights

* Claim amounts are concentrated among middle-aged policyholders.
* Male and female policyholder representation remains balanced.

## Vehicle Insights

* Private-use vehicles account for most claims.
* Certain vehicle brands contribute disproportionately to total claim costs.

## Geographic Insights

* Claim exposure is relatively distributed across coverage zones.
* Urban and suburban regions contribute significantly to total claims.

## Risk Insights

* Demographic, geographic, and vehicle-related factors strongly influence claim severity.
* Multi-dimensional segmentation improves risk assessment accuracy.

---

# 🛠️ Technical Implementation

## Data Modeling

A star schema model was implemented to optimize analytical performance.

### Fact Table

* Fact Insurance Claims

### Dimension Tables

* Dim Policyholder
* Dim Vehicle
* Dim Geography
* Dim Education
* Dim Marital Status
* Dim Date

---

## Power Query Transformations

The ETL process included:

* Data Cleaning
* Missing Value Handling
* Data Type Conversion
* Risk Classification
* Relationship Creation
* Data Validation
* Derived Column Generation

---

## DAX Measures

* Total Policies
* Total Claim Amount
* Average Claim Frequency
* Claim Amount by Age Group
* Claim Amount by Car Make
* Claim Amount by Coverage Zone
* Claim Amount by Vehicle Year
* Claim Amount by Education
* Claim Amount by Marital Status
* Gender Distribution Metrics

---

# 🎨 Dashboard Features

## Interactive Navigation

* Executive Overview
* Demographic Analysis
* Vehicle Risk Analysis
* Geographic Risk Analysis
* Education & Lifestyle Analysis

## Dynamic Filters

* Measure Selection
* Coverage Zone
* Vehicle Make
* Education Level
* Marital Status

## User Experience

* Dynamic KPI Cards
* Interactive Charts
* Cross Filtering
* Drill-Down Analysis
* Responsive Layout

---

# 🧰 Tools & Technologies

| Tool             | Purpose                |
| ---------------- | ---------------------- |
| Power BI Desktop | Dashboard Development  |
| Power Query      | Data Transformation    |
| DAX              | KPI & Measure Creation |
| Excel / CSV      | Data Source            |
| Data Modeling    | Star Schema Design     |

---

# 📷 Dashboard Screenshots

## Insurance Risk & Claims Dashboard

<img width="1257" height="722" alt="image" src="https://github.com/user-attachments/assets/b769d81f-a584-4ef1-97fc-c8ed028f9427" />


---

# 📂 Project Structure

```text
Insurance-Risk-and-Claims-Analysis/
│
├── Dataset/
│   └── insurance_claims_data.csv
│
├── Dashboard/
│   └── Insurance_Risk_Claims_Analysis.pbix
│
├── Images/
│   └── insurance-risk-claims-dashboard.png
│
└── README.md
```

---

# 📌 Conclusion

The Insurance Risk & Claims Analysis Dashboard provides a comprehensive insurance intelligence platform that enables insurers and risk analysts to evaluate claim exposure, understand customer risk profiles, analyze demographic and geographic claim patterns, and optimize underwriting decisions through data-driven insights.

---

# ⭐ Project Summary

An interactive Power BI dashboard that analyzes insurance policies, claim amounts, customer demographics, vehicle characteristics, geographic coverage zones, and risk factors to support smarter underwriting, risk assessment, and claims management strategies.
