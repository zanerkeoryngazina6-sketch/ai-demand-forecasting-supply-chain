# AI-Powered Demand Forecasting and Inventory Intelligence System

## 📌 Project Overview
This project delivers an end-to-end predictive analytics and business intelligence framework tailored for local retailers to transform supply chain management. By merging automated Machine Learning architectures with dynamic executive dashboards, the system transitions corporate logistics from traditional reactive tracking to a structured, data-driven framework.

The primary objective is to minimize holding expenditures, eliminate inventory stockouts, mitigate fulfillment bottlenecks, and evaluate upstream supplier volatility.

---

## 🛠 Tech Stack & Frameworks
* **Data Processing & Analytics:** Python, Pandas, NumPy
* **Machine Learning Pipelines:** Scikit-Learn (Random Forest Regressor, Random Forest Classifier, K-Means Clustering, StandardScaler)
* **Data Visualization:** Matplotlib, Seaborn
* **Business Intelligence (BI):** Power BI Desktop (DAX Modeling, AI Visualizers)

---

## 📂 Repository Structure
* `SmartStock_AI_Notebook.ipynb` — Comprehensive Python script containing features engineering and ML models.
* `final_supply_chain_analytics.csv` — Transformed and engineered operational dataset containing ML clustering and ABC outputs.
* `SmartStock_AI_Dashboard.pbix` — An interactive 8-page Power BI dashboard designed for executive resource planning.

---

## 🚀 Part 1: Predictive Analytics & Machine Learning (Python)

### Task 1 & 2: Explanatory Data Analysis & Feature Engineering
Conducted deep statistical verification to analyze structural distributions across core supply chain cost drivers, addressing missing attributes and executing standard feature generation.

### Task 3: Demand Forecasting Module (Regression)
* **Framework:** Random Forest Regression
* **Target Variable:** `Number of products sold` (Demand Volume)
* **Predictors:** `Price`, `Manufacturing costs`, `Shipping costs`
* **Impact:** Enables procurement departments to shift toward proactive capacity planning, directly compressing warehouse overhead costs.

### Task 4: Delivery Delay Prediction Module (Classification)
* **Framework:** Random Forest Classifier
* **Target Variable:** `Delay_Status` (Binary threshold mapped at > 4 days execution time)
* **Impact:** Provides early-warning risk management to isolate transit bottlenecks before they affect customer fulfillment metrics.

### Task 5: Inventory Optimization Module (Clustering & Stratification)
* **Unsupervised Modeling:** 3-Cluster K-Means algorithm parsing `Stock levels` vs. `Number of products sold` to isolate high-velocity items from obsolete stock positions.
* **Financial Stratification:** Integrated ABC Analysis leveraging the `Revenue generated` matrix (Class A: 80% revenue, Class B: 15%, Class C: 5%).

### Task 6: Supplier & Transportation Risk Indexing
Aggregated a custom 50/50 weighted `Supplier_Risk_Score` balancing structural procurement velocity against average defect rates to deliver quantitative vendor rankings.

---

## 📊 Part 2: Business Intelligence Architecture (Power BI)

The analytical engine populates an interactive, 8-page enterprise application configured to deliver strategic clarity:
1. **Executive Summary:** Macro-level visibility tracking `Total Revenue`, sales performance, and high-level regional distributions.
2. **Demand Forecasting:** Trend tracking integrated with native Power BI AI time-series forecasting.
3. **Logistics & Transportation:** Regional maps charting fulfillment performance, coupled with a cross-functional Carrier Efficiency Matrix.
4. **Inventory Intelligence:** Scatter charts plotting K-Means clusters alongside automated conditional formatting alert triggers.
5. **Supplier Analytics:** Vendor risk indexing and average defect rate analytics.
6. **AI Insights & Evaluation:** Dedicated model validation layout exposing Python evaluation metrics ($R^2$, MAE, Accuracy, F1-Score) and NLP-powered Q&A interfaces.
7. **Financial Metrics & Margin Analysis:** Advanced financial drill-downs isolating baseline operational margins.
8. **Order Drill-down:** Granular operational registry for data auditing and Excel extraction.
