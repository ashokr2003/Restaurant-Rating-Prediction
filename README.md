# 🍽️ Restaurant Rating Prediction – Cognifyz Internship Task 1

This project is part of my internship at **Cognifyz Technologies**, where I built a machine learning model to predict restaurant ratings.

---

## 📊 Overview

- **Dataset**: restaurant data (9,551 records)
- **Goal**: Predict the `Aggregate rating` (0–5) of restaurants
- **Target Variable**: `Aggregate rating`
- **Features Used**:
  - City
  - Longitude, Latitude
  - Cuisines
  - Average Cost for Two
  - Price Range
  - Votes

---

## 🔧 Technologies Used

- Python 🐍
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn (for EDA)
- Jupyter Notebook

---

## 🧹 Data Preprocessing

- Dropped null values (`Cuisines` column had 9 missing values)
- Removed unnecessary columns like Address, Restaurant Name, etc.
- Label encoded categorical features like `City` and `Cuisines`
- Feature Scaling (if needed)
- Train-Test Split (80/20)

---

## 🤖 Models Tried

| Model               | R² Score | MSE   |
|---------------------|----------|-------|
| Linear Regression   | 0.27     | 1.67  |
| Decision Tree       | 0.95     | 0.108 |
| ✅ Random Forest     | **0.96** | **0.091** |

---

## 🎯 Sample Prediction

```python
⭐ Predicted Rating: 3.67
✅ Actual Rating: 4.1
