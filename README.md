# 📊 CREDIT PORTFOLIO ANALYSIS
### Monthly & Branch-Level Analysis (Trends, Collection & Risk Exposure)

---

## 🧩 I. Project Context

This project consists of a Power BI dashboard developed to analyze the performance of a credit portfolio during 2020.

The main objective was to evaluate:

- Monthly loan placement (growth)
- Capital recovery performance
- Portfolio exposure (outstanding balance risk)
- Branch-level financial behavior

The analysis aims to answer a key business question:

Is the company growing sustainably, or is it increasing financial risk?

![caratula](https://github.com/user-attachments/assets/5cd679ea-5f32-450e-b870-d877b58576b0)


---

## 🗂️ II. Dataset Structure

The dataset was previously aggregated at monthly and branch level.  
Each record contains summarized information about credits originated on specific dates.

### Main Variables:

- 📅 **Credit Start Date:** Exact date when the credit was initiated.
- 🗓️ **B_Month:** Representative monthly date (monthly cutoff used for aggregated time analysis).
- 🏢 **Branch:** Branch where the credit was placed.
- ⚠️ **Debt Status (With Debt / Without Debt):** Indicates whether the client still has an outstanding balance.
- 💰 **Total Sales (Total Loan Placement):** Total amount of capital granted.
- 👥 **Number of Clients:** Total clients who acquired credits.
- 📉 **Outstanding Balance (Current Debt):** Capital that has not yet been recovered.
- 💳 **Total Payments:** Total amount paid by clients.
- 📄 **Number of Credits:** Total number of credits issued.

The data is aggregated (not at individual client level), which allows efficient performance analysis at monthly and branch dimensions.

![Modelo de datos](https://github.com/user-attachments/assets/6f851bd1-4fa4-43b2-a713-9077fd6d9d7e)

---

## 🎯 III. Dashboard Objective

The dashboard was designed to answer three strategic questions:

1️⃣ How much capital is being placed monthly?  
2️⃣ What percentage of the capital has been recovered?  
3️⃣ What is the portfolio exposure level?

---

## 📐 IV. DAX Metrics

The following key measures were developed:

### 🔹 Recovery Rate  
Total Payments / Total Placement  
Measures whether the portfolio is generating profitability.

![Porcentaje de Pagos](https://github.com/user-attachments/assets/fef59fce-7b35-463b-89f4-a71999a91144)

---

### 🔹 Exposure Rate  
Outstanding Balance / Total Placement  
Indicates what proportion of placed capital remains at risk.

![Porcentaje Pendiente de Pago](https://github.com/user-attachments/assets/64b708f3-cdcc-42e7-adab-941ed7d9068f)

---

### 🔹 Clients with Debt %  
Percentage of clients who still maintain outstanding balance.


![Porcentaje Cliente Pendiente Pago](https://github.com/user-attachments/assets/6f530b48-9e6a-41a7-bad8-5f228d3b6700)

---

Filter context was carefully managed using slicers (Month & Branch), allowing dynamic KPI interaction while preserving global historical trend visuals for strategic analysis.

---

## 📊 V. Key Insights

- 📈 December had the highest loan placement (284M).
- ⚠️ March showed the highest relative exposure (6.03%).
- 💰 Total payments exceed total placement, indicating portfolio profitability.
- 🏢 Branch exposure levels remain stable (4% average).
- 📊 No critical risk concentration was detected across branches.

---

## 🧠 VI. Conclusion

The analysis shows that the company is increasing its loan placement while maintaining controlled risk levels.

Recovered capital exceeds placed capital, demonstrating financial profitability.

Outstanding balance levels remain stable, and no abnormal branch-level risk patterns were identified.

In simple terms:  
The company is growing, and it is doing so responsibly.

This project demonstrates how financial KPIs and data modeling can support sustainable portfolio growth evaluation and strategic decision-making.

---

## 🌐 VII. Interactive Dashboard

👉 **View Live Dashboard in Power BI:**  

https://app.powerbi.com/view?r=eyJrIjoiOGM0Y2ExYmEtN2ZkMi00OTU2LWFiYmYtMDkzZjQ3OGM4YzU4IiwidCI6ImVhNzA5NDAxLTc5MWEtNDBkYS1hYTc5LTk3Y2Y1ZmIwZmU3OCJ9

---

## 🛠️ Tools Used

- 📊 Power BI
- 📐 DAX
- 🔄 Power Query

---

## 📂 VIII. Project Files

- 📁 .pbix file
- 📄 Dataset (CSV)
- 🖼️ Dashboard images

---

👨‍💻 **Author:** Eng. Maximo Silva Parraguez<br>
**Systems Engineer | Business Intelligence | Data Analytics.**

