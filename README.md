# Data_Analytics-Capstone-Project
# 📊 Bank Loan Report Project

## 📌 Overview
The **Bank Loan Report Project** is designed to monitor, analyze, and assess the performance of a bank's lending activities.  
By providing comprehensive insights into **key loan-related metrics**, this project empowers stakeholders to make **data-driven decisions**, evaluate the **health of the loan portfolio**, and identify **trends** that inform lending strategies.

This project includes **interactive dashboards** for tracking KPIs, visualizing trends, and diving into detailed loan data.

---

## 🎯 Objectives
- Track and analyze **loan portfolio performance**.
- Monitor **key metrics** like loan applications, funded amounts, repayments, interest rates, and borrower DTI.
- Identify trends using **time-series analysis** and uncover **regional, term-based, and demographic patterns**.
- Evaluate **loan quality** through Good Loan vs Bad Loan classification.
- Provide a **grid view** and a **detailed dashboard** for granular insights.

---

## 📊 Key Performance Indicators (KPIs)

### 🔑 General KPIs
1. **Total Loan Applications**
   - Total count of applications received.
   - Month-to-Date (MTD) Loan Applications.
   - Month-over-Month (MoM) changes.

2. **Total Funded Amount**
   - Total principal disbursed.
   - MTD Funded Amount & MoM trend.

3. **Total Amount Received**
   - Total repayments received.
   - MTD Received Amount & MoM trend.

4. **Average Interest Rate**
   - Average rate across all loans.
   - MTD & MoM tracking for trends.

5. **Average Debt-to-Income (DTI) Ratio**
   - Average borrower DTI across loans.
   - MTD & MoM variation monitoring.

---

### ✅ Good Loan KPIs
- **Good Loan Application Percentage** (Loans with `Fully Paid` or `Current` status)
- **Good Loan Applications** (Total count)
- **Good Loan Funded Amount**
- **Good Loan Total Received Amount**

### ❌ Bad Loan KPIs
- **Bad Loan Application Percentage** (Loans with `Charged Off` status)
- **Bad Loan Applications** (Total count)
- **Bad Loan Funded Amount**
- **Bad Loan Total Received Amount**

---

## 🗂️ Loan Status Grid View
A grid-based report categorized by **Loan Status**, displaying:
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- MTD Funded Amount & Received Amount
- Average Interest Rate
- Average DTI

This view helps in monitoring portfolio health and understanding performance by loan status.

---

## 📈 Dashboards

### 📊 Dashboard 2: **Overview**
A visually interactive dashboard showcasing high-level insights with multiple chart types:

1. **Monthly Trends by Issue Date (Line Chart)**  
   Tracks Total Loan Applications, Funded Amount, and Amount Received month-over-month.

2. **Regional Analysis by State (Filled Map)**  
   Displays geographical distribution of applications, funded amounts, and repayments.

3. **Loan Term Analysis (Donut Chart)**  
   Highlights loan metrics distribution by term length (e.g., 36, 60 months).

4. **Employment Length Analysis (Bar Chart)**  
   Shows loan metrics by borrowers’ employment length.

5. **Loan Purpose Breakdown (Bar Chart)**  
   Visualizes the distribution of loan applications and amounts by loan purpose.

6. **Home Ownership Analysis (Tree Map)**  
   Provides hierarchical view of loan metrics based on home ownership status.

---

### 📝 Dashboard 3: **Details**
A consolidated view that includes:
- Individual loan records
- Borrower profiles
- Detailed loan performance metrics  
This serves as a **single point of reference** for deep-dive analysis and operational decisions.

---

## 🛠️ Tech Stack
- **Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)** – Data analysis & visualization
- **Power BI / Tableau (Optional)** – Interactive dashboard creation
- **Jupyter Notebook** – Data cleaning, exploration, and KPI calculation
- **Excel / CSV** – Input and export of datasets

---

## 📌 Key Insights You Can Derive
- **Portfolio Growth Trends:** See how applications and disbursements are changing month-to-month.
- **Repayment Patterns:** Track total received amounts and identify repayment health.
- **Risk Assessment:** Monitor Good vs Bad loan distribution to control risk exposure.
- **Demographic & Regional Patterns:** Identify which states, purposes, and borrower profiles contribute most to loan volume.

---

## 🚀 How to Use
1. **Load the dataset** into your Jupyter Notebook or BI tool.
2. **Run the data processing scripts** to calculate KPIs.
3. **Generate the visualizations** for trend and distribution analysis.
4. **View dashboards** for high-level insights and deep-dive into details for granular analysis.

---

## 📢 Conclusion
This project provides a **360° view** of bank lending operations through comprehensive KPIs, Good/Bad loan analysis, trend tracking, and interactive dashboards.  
It is an essential tool for **lending strategy, risk management, and performance evaluation**.
