# 🛒 E-commerce Checkout & Cart Abandonment Improvement
An end-to-end Business Analysis project focused on identifying cart abandonment patterns and designing an improved checkout process.

---

## 📝 Project Overview
* **Business Problem:** High cart abandonment was resulting in incomplete purchases and potential revenue loss.
* **Objective:** Identify abandonment patterns, understand potential causes and propose an improved checkout flow.
* **My Role:** Business Analyst (BA)
* **Tools Used:** Excel | Power BI | Draw.io | Jira
* **Dataset Details:** Public Kaggle e-commerce dataset (25,000 sessions | 8,442 unique customers | 2024 data)

---

## ⚙️ Business Analysis (BA) Process
```text
Business Problem ➔ Stakeholder Analysis ➔ Requirements ➔ As-Is Process ➔ Data Analysis ➔ Root Cause Analysis ➔ To-Be Process ➔ User Stories (Task) ➔ KPI Dashboard ➔ Recommendations
```

---

## 📸 Project Screenshots & Visuals

### 📑 BRD Cover & Stakeholders
<p align="center">
  <img src="BRD Cover.png" width="45%" alt="BRD Cover" />
  <img src="Stakeholder Table.png" width="45%" alt="Stakeholder Table" />
</p>

### 🔄 Process Diagrams (As-Is vs To-Be)
<p align="center">
  <img src="As-Is Process.png" width="45%" alt="As-Is Process" />
  <img src="To-Be Process.png" width="45%" alt="To-Be Process" />
</p>

### 📊 Data Analysis & Dashboard
<p align="center">
  <img src="Excel Pivot Analysis.png" width="45%" alt="Excel Pivot Analysis" />
  <img src="Power BI Dashboard.png" width="45%" alt="Power BI Dashboard" />
</p>

### 🎯 Root Cause & Project Management
<p align="center">
  <img src="Route Cause Analysis.png" width="45%" alt="Root Cause Analysis" />
  <img src="Jira User Stories.png" width="45%" alt="Jira User Stories" />
</p>

---

## 🔍 Key Findings (Actual Data Insights)
* **Highest Drop-off Point:** 64% of users abandon the cart during the mandatory "Login/Registration" step.
* **Device Insights:** Mobile users have a 15% higher abandonment rate compared to Desktop users due to responsive layout friction.
* **Payment Failures:** 8% of transactions fail at the gateway, with zero recovery mechanisms in place (no retry option).
* **Cart Value Effect:** High delivery fees discovered late in the summary step cause a 22% drop-off in orders under ₹1,000.

---

## 💡 Recommendations & Actions
1. **Implement Guest Checkout:** Introduce a frictionless guest checkout to eliminate mandatory registration and reduce drop-offs by an estimated 30%.
2. **Combine Steps:** Merge Customer Details and Address into a single intuitive screen to shorten the funnel.
3. **Add Payment Retry Loop:** Implement an automatic "Retry Payment" option keeping the cart active to recover failed transactions.
4. **Upfront Pricing Transparency:** Display shipping fees and dynamic discounts early in the checkout process rather than hiding them until the final screen.

---

## 📂 Project Documents & Attachments
* 📄 [Download Business Requirement Document (BRD)](https://github.com/stutihingu/ecommerce-checkout-abandonment-project/blob/main/Ecommerce_Checkout_Cart_Abandonment_BRD.pdf) 
* 📊 [View Interactive Power BI Dashboard](https://github.com/stutihingu/ecommerce-checkout-abandonment-project/blob/main/BA%20Project.pbix) 
