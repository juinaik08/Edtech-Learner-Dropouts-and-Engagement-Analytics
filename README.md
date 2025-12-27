# 📊 Edtech learner dropouts nd performance analytics  
### SQL → Power BI → Business Insights

---

## 📌 Project Overview

This project analyzes **learner dropout behavior** on an **EdTech platform** using **SQL for data preparation & analysis** and **Power BI for visualization and insights**.

The objective is to **identify dropout drivers**, understand **learner engagement patterns**, and recommend **data-driven strategies to reduce churn**.

---

## 🎯 Business Objectives

- Understand **why learners drop out**
- Measure **engagement vs retention**
- Identify **high-risk learners early**
- Analyze impact of **course difficulty**
- Evaluate **subscription type vs retention**
- Provide **actionable recommendations** to control dropouts

---

## 🛠️ Tools & Technologies

- **MySQL** – Data modeling, validation, analysis  
- **Power BI Desktop** – Data modeling, DAX measures, dashboards  
- **GitHub** – Version control & project documentation  

---

## 📂 Dataset Description

The dataset simulates an **EdTech learning platform** and includes:

- Student demographics  
- Course details  
- Platform usage behavior  
- Engagement metrics  
- Performance scores  
- Payment & subscription details  
- Dropout indicator (Target Variable)

📌 **Total Records:** ~10,000 learners  

---

## 🧱 Database Design (SQL)

A **normalized relational database** was designed with the following tables:

- Students  
- Courses  
- Platform Usage  
- Learner Activity  
- Performance  
- Payment  
- Time Behaviour  
- Dropout (Target Table)

A **Master Dataset** was created by joining all tables to support analytics and BI reporting.

---

## 🔍 Data Quality & Validation (SQL)

Before analysis, the following checks were performed:

- Primary key validation  
- Foreign key integrity checks  
- Missing value detection  
- Range & logic validation  
- Target variable distribution analysis  

✔ Ensured **clean and reliable data** before visualization.

---

## 📈 Business Analysis Performed (SQL)

Key analytical areas covered:

- Dropout vs learner engagement  
- Dropout rate by course difficulty  
- Paid vs Free subscription retention  
- Login frequency & inactivity impact  
- Early dropout risk identification  

These analytical outputs were later consumed in **Power BI**.

---

## 📊 Power BI – Data Modeling & Visualization

### Steps Followed:

1. Imported **Master Dataset**  
2. Verified data types and relationships  
3. Created **DAX measures** for KPIs  
4. Designed interactive dashboards  
5. Added **business explanations & insights**

---

## 📌 Dashboard Pages

### 🟦 Page 1: Executive Dashboard  
**Focus:** *What is happening?*

- Total learners & dropout rate  
- Engagement score overview  
- Dropout by course difficulty  
- Subscription type impact  
- High-risk learner percentage  
- Interactive slicers (course, country, difficulty)

---

### 🟩 Page 2: Insights & Conclusions  
**Focus:** *Why it is happening & what to do next*

- Key business questions answered  
- Analytical findings  
- Business conclusions  
- Actionable recommendations to reduce dropouts  

---

## ❓ Key Business Questions Answered

| Question | Insight |
|--------|--------|
| Do inactive learners drop out more? | Yes – low login frequency & long inactivity show much higher dropout rates |
| Does engagement reduce dropout risk? | Yes – higher engagement strongly correlates with retention |
| Which course difficulty has higher dropouts? | Advanced-level courses have the highest dropout rates |
| Does subscription type affect retention? | Paid learners retain significantly better than free users |
| Can we identify high-risk learners early? | Yes – inactivity + low engagement act as early warning signals |

---

## 📌 Final Conclusions (Clear & Actionable)

- High-risk learners account for the **majority of dropouts**
- Engagement score is a **strong predictor of retention**
- Advanced courses need **additional learner support**
- Free users churn **more than paid users**
- Early behavioral signals can **prevent dropouts proactively**

---

## ✅ Recommendations to Control Dropouts

- Introduce **early engagement nudges** (first 7 days)
- Provide **mentorship & guidance** for advanced courses
- Re-engage inactive learners using **automated reminders**
- Improve onboarding experience for **free users**
- Track **high-risk learners in real time** using dashboards

---

## 📎 Project Status

✔ SQL Analysis Completed  
✔ Power BI Dashboard Built  
✔ Business Insights Delivered  

---
