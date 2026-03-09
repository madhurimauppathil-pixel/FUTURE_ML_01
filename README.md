# 🔮 InsightFlow — Sales Forecast Dashboard

> ML-powered sales forecasting built with Python on the Superstore dataset.

## 🔗 Live Dashboard
👉 **[https://insightflow-ml.netlify.app](https://insightflow-ml.netlify.app)**

---

## 📊 Project Overview
Predicts monthly sales using 3 ML models trained on 4 years of Superstore retail data (2014–2017) with 13 engineered temporal features. Includes a fully interactive web dashboard.

---

## 🤖 Model Results

| Model | MAE | RMSE | R² | MAPE |
|-------|-----|------|----|------|
| **Linear Regression ⭐** | $12,293 | $15,092 | 0.600 | 16.8% |
| Random Forest | $14,237 | $16,902 | 0.493 | 19.7% |
| Gradient Boosting | $15,586 | $16,591 | 0.511 | 22.9% |

✅ **Best Model: Linear Regression** (lowest MAPE 16.8%)

---

## 📁 Repository Files

| File | Description |
|------|-------------|
| `index.html` | Interactive web dashboard |
| `sales_forecasting_complete.ipynb` | Full ML pipeline notebook |
| `Sample - Superstore.csv` | Raw dataset (9,994 rows) |

---

## 🛠 Tech Stack
`Python` · `Pandas` · `NumPy` · `Scikit-learn` · `Matplotlib` · `Seaborn` · `HTML/CSS/JS` · `Chart.js` · `Netlify`

---

## 💡 Key Findings
- **Lag_12** is the strongest predictor — year-over-year seasonality drives sales
- **Q4 peaks every year** — November 2017 hit $118,448
- **Q1 is weakest** — February 2014 lowest at $4,520
- 6-month forecast total: **$349,126**

---

## 👩‍💻 Author
**Madhurima Mani** · ML Intern · Future Interns
