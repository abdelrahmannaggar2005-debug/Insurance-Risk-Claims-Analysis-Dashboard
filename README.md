# 📊 Insurance Risk & Claims Analysis Dashboard

## 🧠 Project Overview

<img width="1374" height="814" alt="Screenshot 2025-12-29 142136" src="https://github.com/user-attachments/assets/08f152a6-7579-4479-bd74-1cf071f41ef4" />

This repository contains an end-to-end **insurance claims risk analysis project** built to provide actionable insights for insurance companies. The primary goal is to visualize claim patterns, demographic risk factors, and support data-driven decisions related to pricing, claims processing, and risk assessment.

The project combines:
- **Exploratory Data Analysis (EDA)**  
- **Machine Learning risk modeling (optional)**  
- **Interactive dashboard visualization**

Tools used include Power Query and Power BI.

---

## 📂 Dataset Description

The dataset contains structured insurance policy and claim information. Although specific dataset documentation may vary, key fields typically include:

- **PolicyNumber / CustomerID** — Unique identifiers  
- **Age, Gender, BMI, SmokingStatus** — Demographics & health indicators  
- **PolicyType & CoverageAmount** — Policy details  
- **ClaimNumber, ClaimDate, ClaimAmount, ClaimStatus** — Claim records  
- Other risk and descriptive attributes relevant to insurance analytics

> This structure allows analysis of relationships between demographics, policy features, and claim outcomes. :contentReference[oaicite:0]{index=0}

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI** | Creating interactive dashboards, slicers, visuals |
| **Power Query Editor** | Data transformation and preprocessing |

---

## 🧹 Data Cleaning & Processing

Data preparation was executed to ensure reliable and accurate analysis:

- Import dataset into Python for cleaning and transformations
- Handle missing values and inconsistent formats
- Generate derived features such as Age Group, Policy Status
- Validate and aggregate claim totals
- Export cleaned data for dashboard consumption

This step ensures downstream visuals and insights are accurate.

---

## 🔎 Exploratory & Risk Analysis

The Python and SQL analysis phases include:

- Claim frequency and amount distribution by key groups (Age, Gender, SmokingStatus)
- Demographic risk profiling
- Regional claim variations
- Basic risk scoring and segmentation

These analyses form the basis for dashboard visuals and deeper business insight.

---

## 📊 Power BI Dashboard

The core output of this project is an **interactive Power BI dashboard** that delivers:

### 🔹 KPI Overview
- Total Claims Count
- Total Claim Amount
- Average Claim Value
- Breakdown by Claim Status (Settled / Pending / Rejected)

### 🔹 Risk & Demographics Views
- Claim distribution by age groups
- Smoking status comparison
- BMI and other health indicator breakdowns
- Regional claim patterns

### 🔹 Policy Performance
- Policy types vs claim amounts
- Active vs inactive policy insights
- Coverage vs claim risk

### Interactive Features
- Date filters
- Demographic slicers (age, gender, smoking)
- Cross-filtering between visuals

These elements empower stakeholders to explore data from multiple angles and identify risk patterns effectively.

---

## 📈 Key Insights

Typical insights derived from the dashboard may include:

- Certain age groups or health segments exhibit higher claim amounts
- Smokers or specific demographic categories pose higher risk
- Some regions show variance in claim frequency or severity
- Policy types differ in claim outcomes, informing pricing strategy

These insights help optimize underwriting, pricing, and risk mitigation strategies. :contentReference[oaicite:1]{index=1}

---

## 🧠 Business Value

This project supports insurance business goals by:

- Allowing performance monitoring and trend detection
- Supporting pricing strategy adjustments based on risk profiles
- Helping identify high-risk customer segments
- Enabling interactive, data-driven decision making

---

## 📁 Project Structure

Insurance-Risk-Claims-Analysis-Dashboard/
│
├── data/
│ └── insurance_policies_data.xlsx
│
├── dashboard/
│ └── powerbi1.pbix
│
├── docs/
│ └── Dashboard Process.docx
├── README.md


---

## 🚀 How to Run

1. **Load the dataset** into your local directory or SQL database.
2. **Run Python scripts** to perform data cleaning and generate insight files.
3. **Open Power BI (.pbix)** and update data source connections.
4. **Visualize and interact** with the dashboard for insights.

---

## 🧠 Skills Demonstrated

- Data extraction and preprocessing
- EDA with Python & SQL
- Interactive dashboard design
- Business insight generation
- Risk profiling and segmentation

---

## 📬 Contact

For feedback, questions, or collaboration:

**Name:** Abdelrahman Ahmed  
**Role:** Data Analyst  
**LinkedIn:**[Abdelrahman_LinkedIn](https://www.linkedin.com/in/abdelrahman-ahmed-852b69290?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)
**Email:** [abdelrahman.naggar2005@gmail.com]
