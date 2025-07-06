# capstone-project
# 🚗 Dynamic Pricing for Urban Parking Lots — Summer Analytics 2025 Capstone

## 📌 Overview

This project is part of the Summer Analytics 2025 program hosted by the Consulting and Analytics Club, IIT Guwahati. The aim is to develop a **dynamic pricing model** for urban parking lots based on historical occupancy data, competition, time, and real-world constraints.

The solution includes:

- Predicting demand for parking lots
- Dynamic price adjustment using temporal factors
- Competitive pricing using spatial proximity and KDTree optimization

---

## 🛠️ Tech Stack

- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Bokeh** – Interactive visualizations
- **Scikit-learn** – Modeling
- **SciPy (KDTree)** – Efficient spatial queries
- **Jupyter Notebooks**

---

## 🧱 Architecture Diagram

```mermaid
flowchart TD
    A[Raw Data (CSV)] --> B[Data Preprocessing]
    B --> C1[Model 1: Demand Score Calculation]
    C1 --> C2[Model 2: Time-based Price Adjustment]
    C2 --> C3[Model 3: Competition-aware Pricing using KDTree]
    C3 --> D[Final Price Recommendations]
