# 🌍 Global Supply Chain Risk Analysis

A data analysis project that explores logistics performance, shipment risks, and operational efficiency in global supply chains using Python.

This project uses the dataset **`global_supply_chain_risk_2026.csv`** to perform exploratory data analysis, risk assessment, and predictive modeling to understand the factors affecting shipment disruptions and lead times.

---

# 📑 Table of Contents

* Introduction
* Problem Statement
* Project Objectives
* Methodology
* Technologies Used
* Recommendations
* Future Improvements
* Author

---

# Introduction

Global supply chains involve complex logistics networks connecting manufacturers, suppliers, carriers, and markets across different regions. These networks are influenced by several operational and external factors such as transportation modes, weather conditions, geopolitical instability, fuel prices, and carrier reliability.

Analyzing supply chain data allows organizations to identify inefficiencies, predict disruptions, and optimize logistics operations. This project explores shipment-level data to understand patterns in transportation modes, delivery times, and risk factors affecting global logistics performance.

---

# Problem Statement

Supply chain operations are increasingly exposed to risks caused by external disruptions, unpredictable weather conditions, and geopolitical tensions. Without proper analysis, organizations struggle to identify operational bottlenecks or predict shipment delays.

This project aims to analyze shipment data to answer key operational questions, including:

* What factors influence shipment delays?
* Which transport modes are most reliable?
* How do weather and geopolitical risks affect disruptions?
* Can shipment disruptions be predicted using historical data?

By applying data analysis and visualization techniques, the project provides insights that can improve logistics planning and risk management.

---

# Project Objectives

The analysis tasks in this project are divided into **three levels of complexity**.

## Level 1 – Beginner: Data Cleaning and Descriptive Statistics

These tasks focus on understanding the dataset and performing basic statistical analysis.

Objectives include:

* Calculate **summary statistics** such as mean, median, and standard deviation for `Distance_km` and `Weight_MT`.
* Identify the **most frequently used transport mode** in the dataset.
* Filter shipments where **Weather_Condition = Hurricane** to analyze extreme weather events.
* Count the number of **unique origin and destination ports**.
* Detect and handle **missing values** in the dataset.

These insights help operations managers understand the general characteristics of shipment activities. 

---

## Level 2 – Intermediate: Data Manipulation and Visualization

This stage focuses on identifying relationships and trends within the data.

Objectives include:

* Create a **scatter plot** showing the relationship between **Distance_km and Lead_Time_Days**.
* Calculate the **disruption rate for each transport mode**.
* Analyze **monthly shipment trends** to identify peak shipping periods.
* Evaluate the **impact of weather conditions on carrier reliability**.
* Rank the **top 5 routes with the highest geopolitical risk scores**.

These analyses provide valuable insights for logistics planners, insurance analysts, and vendor managers. 

---

## Level 3 – Advanced: Predictive Analytics and Feature Engineering

Advanced tasks prepare the dataset for machine learning and predictive modeling.

Objectives include:

* Generate a **correlation heatmap** for numerical variables.
* Build a **regression model** to predict `Lead_Time_Days`.
* Perform **anomaly detection** to identify shipments with unusually long lead times.
* Build a **classification model** to predict whether a shipment will experience a disruption.
* Analyze whether **fuel price fluctuations influence transport mode selection**.

These techniques help organizations develop data-driven strategies and early-warning systems for supply chain disruptions. 

---

# Methodology

The project follows a structured data analysis workflow:

### 1. Data Collection

The dataset is imported into a Python environment using the **Pandas** library.

### 2. Data Cleaning

Data preparation includes:

* Handling missing values
* Converting date columns to **datetime format**
* Removing duplicates
* Validating data consistency

### 3. Exploratory Data Analysis (EDA)

Descriptive statistics and visualizations are used to identify trends, patterns, and anomalies.

### 4. Data Visualization

Visual tools such as **scatter plots, bar charts, and heatmaps** are used to interpret relationships between variables.

### 5. Predictive Modeling

Machine learning models are applied to predict shipment delays and disruptions using historical data.

---

# Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---


# Recommendations

Based on insights obtained from the analysis:

* Implement **real-time monitoring systems** for shipment tracking.
* Diversify **transportation routes and carriers** to reduce dependency risks.
* Use **predictive analytics** to anticipate shipment disruptions.
* Strengthen **risk assessment strategies** for high-risk geographic routes.

These improvements can help organizations increase supply chain resilience and operational efficiency.

---

# Future Improvements

Possible extensions of this project include:

* Building **interactive dashboards** using Power BI or Tableau
* Implementing **advanced machine learning models**
* Integrating **real-time logistics data**
* Developing a **supply chain disruption prediction system**

---

# Author

Destiny Kevin
Candace Chijoke-Mba
Data Analyst | Supply Chain Analytics | Python Enthusiast
