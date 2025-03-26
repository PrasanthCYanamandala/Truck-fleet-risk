# Truck Fleet Risk Analytics and Driver Safety Solutions

This repository contains the project for **Big Data** course, focused on leveraging data analytics to identify and mitigate driver-related risks in commercial trucking operations.

## 🚛 Project Overview

**Az National Trucking (ANT)** faces elevated insurance risks due to unsafe driving behaviors across its fleet. This project uses telematics, GPS data, and driver behavior analytics to uncover insights, support risk mitigation strategies, and propose actionable improvements.

## 🎯 Objectives

- Monitor driver behavior using telematics and GPS tracking
- Identify key unsafe behaviors such as:
  - Speeding
  - Unsafe following distance
  - Lane departures
- Highlight geographic trends in risky driving
- Categorize drivers by safety levels and risk scores
- Propose training or policy improvements based on data patterns

## ❓ Business Questions Answered

- Which cities report the highest number of unsafe events?
- What are the most uncommon (but critical) unsafe behaviors?
- What proportion of drivers are risky vs. safe?
- Which drivers have the highest and lowest risk scores?
- Among risky drivers, what events are most frequent?

## 📊 Key Insights

- **Top Risky Cities:** Santa Rosa, Willits, and Apple Valley
- **Most Common Unsafe Behavior:** Unsafe following distance
- **Truck A97** has the highest average risk factor (31.7)
- **Risky Truck Models:** Ford, Oshkosh, Peterbilt
- **Recommended Truck Models:** Hino and Western Star

## 📈 Methodology

- Developed dashboards to visualize population and risk trends
- Analyzed incident frequency by city, driver, and truck model
- Performed regression analysis to examine mileage vs. risk factor
- Identified high-risk drivers for potential intervention and training

## 🛠️ Tools & Technologies

- SQL/Impala for data querying
- Tableau / Power BI for dashboards
- R / Python for statistical analysis (planned but constrained)
- Excel for data wrangling and summaries

## 🚧 Challenges

- Technical issues with Impala and data folders
- Slow regression tool performance
- Limited dataset (one state only)
- No KPIs defined beyond the risk factor

## 💡 Suggestions

- Integrate more datasets (e.g., driver profiles, city infrastructure)
- Build predictive ML models for proactive driver risk identification
- Expand the analysis to a national level
- Implement additional training for high-risk drivers

---

📌 *This project showcases a real-world application of risk analytics in the transportation industry, offering both strategic insights and practical recommendations for improving driver safety and reducing insurance liabilities.*
