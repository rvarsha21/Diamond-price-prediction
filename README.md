# 💎 Diamond Price Prediction Model

*A Data-Driven Approach to Price Accuracy*

## 📌 Project Overview

This project focuses on predicting the price of round-cut diamonds using machine learning. By analyzing **53,940 diamonds** with physical, qualitative, and engineered features, the goal is to improve pricing transparency for buyers, jewelers, and online marketplaces.

The system compares multiple models, identifies key price drivers, and demonstrates how data-driven modeling can outperform intuition in valuing diamonds.

---
## 🎯 Objectives

* Predict diamond prices using physical and qualitative attributes
* Compare the performance of linear vs. ensemble models
* Identify the most influential features driving diamond pricing
* Provide interpretable insights useful to consumers and sellers

---

## 📂 Dataset

**Diamonds Dataset (53,940 samples)**
Includes the following features:

* Carat
* Cut (Fair → Ideal)
* Color (D → J)
* Clarity (I1 → IF)
* Depth %
* Table %
* Dimensions (x, y, z)
* Price
---

## 🧪 Feature Engineering

* Converted cut, color, clarity into **numeric rankings**
* Created **volume**: `x × y × z` to represent full diamond size
* Removed outliers for improved stability
* Identified strongest correlations:

  * **Volume** and **Carat** = top predictors
  * Clarity and color follow
  * Depth/table have lower influence

---

## 🤖 Modeling Approach

* **Multiple Linear Regression**
* **Grow–Prune Decision Tree**
* **Bagging Regressor**
* **Random Forest**
* **Boosting Models**

---

## 🏆 Results & Insights

* **Random Forest performed best**:

  * RMSE ≈ **$535**
  * R² ≈ **0.98**

* **Most important features**:

  1. Volume
  2. Carat
  3. Clarity
  4. Color

* Ensemble models handled noise and nonlinear interactions better than linear models.

---

## 📌 Conclusion

**Consumers:**

* Can identify overpriced diamonds and make more informed buying decisions

**Jewelers:**

* Gain a data-backed tool for competitive, consistent pricing

**Online Marketplaces:**

* Can integrate real-time recommended pricing engines based on diamond attributes


