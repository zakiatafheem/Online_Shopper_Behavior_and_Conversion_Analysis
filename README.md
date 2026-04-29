# Online_Shopper_Behavior_and_Conversion_Analysis

## 🧠 Project Overview

This project analyzes user behavior on an e-commerce platform to understand why some users convert into buyers while most do not.
The goal is to identify key behavioral factors that influence purchase decisions and provide data-driven insights to improve conversion rates and business performance.

---
## 🎯 Problem Statement
 
E-commerce businesses often face low conversion rates, where a majority of users browse but do not make purchases. Understanding the factors that influence user conversion is challenging.
This project aims to identify the key behavioral and session-level factors that differentiate buyers from non-buyers.

---
## 🎯 Objective

To analyze online shopper session data and uncover patterns, user behaviors, and key features that significantly impact conversion (Revenue), and to derive actionable insights that can improve conversion rates.

---
## 💼 Business Objective

To support data-driven decision-making by identifying high-impact factors such as user engagement, page value, and visitor type, enabling businesses to optimize user experience and increase overall revenue.

---
## 📂 Dataset

* Source: Online Shoppers Intention Dataset

Each row represents a user session

* Key Features:

Page interaction metrics (Administrative, Informational, ProductRelated)

Time spent on pages

Bounce Rate & Exit Rate

Visitor Type (New / Returning)

Page Value

* Target variable: Revenue (True/False)

---
## ⚙️ Tools & Technologies

* Python (Pandas, NumPy, Seaborn, Matplotlib)
* Power BI (Dashboard & Visualization)
* Scikit-learn (Random Forest for Feature Importance)

---
## 🧹 Data Preprocessing

* Checked and handled missing values
* Removed 125 duplicate records
* Converted data types and encoded categorical variables
* Analyzed and handled outliers without losing critical behavioral insights

---
## 📊 Exploratory Data Analysis

* Calculated overall conversion rate (~15%)
* Compared buyer vs non-buyer behavior
* Analyzed engagement patterns and distributions
* Used visualizations (bar charts, heatmaps, scatter plots) to uncover relationships

---
## 🔥 Key Insights

* Low Conversion Rate: Only ~15% users convert, indicating a major opportunity for optimization
* Engagement Drives Conversion: Buyers spend significantly more time, especially on product pages
* Page Value is the Strongest Indicator: High page values strongly correlate with purchase behavior
* Bounce Rate Impact: Higher bounce rates significantly reduce conversion likelihood
* Returning Users Convert More: Repeat visitors show stronger purchase intent

---
## 📈 Feature Importance

A Random Forest model was used to identify the most influential features driving conversion.

* Top Drivers:
PageValues,
ProductRelated_Duration,
BounceRates,
ExitRates,
VisitorType.

---
## 📊 Dashboard

* KPI metrics (Conversion Rate, Engagement, Bounce Rate)
* User behavior insights
* Conversion trends
* Key drivers of purchase

---
## 💡 Business Recommendations
* Improve product page experience to increase engagement
* Reduce bounce rates through better UI/UX optimization
* Target high-engagement users with personalized offers
* Focus marketing efforts on returning visitors
* Optimize high page-value pages for better conversion

---
## 🚀 Project Outcome

This project enables businesses to:

* Understand customer behavior
* Identify key conversion drivers
* Take data-driven actions to improve revenue and user experience

---
## 🎤 Key Learnings

* Data cleaning and preprocessing
* Behavioral data analysis
* Data visualization and storytelling
* Translating insights into actionable business strategies

---
## ⭐ Final Note

This project demonstrates how data analysis can directly impact business decisions by identifying key factors influencing customer behavior and conversion.

---

📸 Dashboard Preview

(Add your Power BI dashboard screenshot here)
