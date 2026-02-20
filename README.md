# 📊 CREDIT PORTFOLIO ANALYSIS
### Monthly & Branch-Level Analysis (Trends, Collection & Risk)

---

## 🧩 I. Project Context

This project consists of a Power BI dashboard developed to analyze the performance of a credit portfolio during 2020.

The main objective was to evaluate:

- Monthly loan placement
- Capital recovery
- Risk exposure
- Branch-level financial behavior

Key question:

Is the company growing sustainably or increasing financial risk?

(INSERT IMAGE: Full dashboard overview)

---

## 🗂️ II. Dataset Structure

The dataset was aggregated at monthly and branch level.

Each record contains summarized information about originated credits.

### Main Variables:

- 📅 **Credit Start Date**
- 🗓️ **B_Month (Monthly Cutoff Date)**
- 🏢 **Branch**
- ⚠️ **Debt Status (With Debt / Without Debt)**
- 💰 **Total Sales (Loan Placement)**
- 👥 **Number of Clients**
- 📉 **Outstanding Balance**
- 💳 **Total Payments**
- 📄 **Number of Credits**

(INSERT IMAGE: Power BI data model view)

---

## 🎯 III. Dashboard Objective

The dashboard answers three strategic questions:

1️⃣ How much capital is being placed monthly?  
2️⃣ What percentage has been recovered?  
3️⃣ What is the portfolio exposure level?

---

## 📐 IV. DAX Metrics

### 🔹 Recovery Rate  
Total Payments / Total Placement  
Measures portfolio profitability.

(INSERT IMAGE: Recovery KPI Card)

---

### 🔹 Exposure Rate  
Outstanding Balance / Total Placement  
Indicates capital at risk.

(INSERT IMAGE: Exposure KPI Card)

---

### 🔹 Clients with Debt %  
Percentage of clients with outstanding balance.

(INSERT IMAGE: Clients with Debt KPI Card)

---

Filter context was managed so slicers dynamically affect KPIs while historical trend visuals remain globally consistent.

---

## 📊 V. Key Insights

- 📈 December had the highest placement (~284M).
- ⚠️ March showed the highest exposure (~6.03%).
- 💰 Total payments exceed total placement.
- 🏢 Branch exposure levels remain stable (~4% average).

---

## 🧠 VI. Conclusion

The analysis shows controlled growth.

Recovered capital exceeds placed capital, indicating profitability.

No critical risk concentration was identified.

Overall, the portfolio demonstrates sustainable growth with balanced financial risk.

---

## 🌐 VII. Interactive Dashboard

👉 **View Live Dashboard:**  
(PASTE YOUR POWER BI SERVICE LINK HERE)

---

## 🛠️ Tools Used

- 📊 Power BI
- 📐 DAX
- 🔄 Power Query
- 📊 R (data preprocessing)

---

## 📂 VIII. Project Files

- 📁 .pbix file
- 📄 Dataset
- 🖼️ Dashboard images

---

👨‍💻 **Author:** Max  
Systems Engineer | Business Intelligence | Data Analytics
