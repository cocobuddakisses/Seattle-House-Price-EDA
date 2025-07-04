# 🏡 Seattle Housing Price Analysis

This project explores and models housing prices in Seattle using **Python (pandas, scikit-learn)** and a **Power BI dashboard** to present clear, actionable insights.

---

## 📊 **Project Overview**

- ✅ **Goal:** Analyze Seattle house prices, understand price distributions, and build a basic regression model to predict log-transformed prices.
- ✅ **Tools Used:** Python (pandas, matplotlib, seaborn, scikit-learn), Power BI for interactive dashboarding.
- ✅ **Key Outputs:** Jupyter notebooks for EDA & modeling + Power BI dashboard showing raw vs. log-transformed distributions and model insights.

---

## 🧹 **Steps Taken**

1. **Load & Inspect Data:** Cleaned dataset, removed duplicates, handled outliers, adjusted types for modeling.
2. **Exploratory Data Analysis:** Calculated mean, median, mode, skewness, kurtosis; plotted raw price distributions.
3. **Normality Check:** Identified right-skewed raw prices; discussed why normality matters for regression.
4. **Log Transformation:** Applied log transform to prices to reduce skewness & kurtosis.
5. **Post-Transform EDA:** Confirmed distribution is now approximately normal.
6. **Feature Selection:** Picked features with clear linear correlation (bedrooms, bathrooms, house sqft, lot sqft).
7. **Modeling:** Trained linear regression using scikit-learn; evaluated using MAE, MSE, and R².
8. **Power BI Dashboard:** Visualized raw & transformed price distributions, summary stats, and key model findings.

---

## 📈 **Results**

| Metric | Value |
|--------|-------|
| MAE    | ~0.22 |
| MSE    | ~0.08 |
| R²     | ~0.59 |

✅ The model explains a fair portion of the price variation with a few key features.  
✅ The log transform improved normality and made linear regression more valid.

---

## 🗂️ **Files**

- `notebooks/` — Jupyter notebooks for EDA and modeling
- `PowerBI/dashboard.pbix` — Power BI file showing raw & log price distributions
- `requirements.txt` — Python packages to run the notebooks
- `data/` — *[Dataset not included due to size/privacy — please add your own version]*

---

## 🗒️ **Next Steps**

- Add more predictive features (zip code, year built, renovations, etc.)
- Try other models (ridge, lasso, decision trees)
- Tune hyperparameters
- Deploy a simple web app or share results in an interactive dashboard

---

## ⚙️ **Setup**

```bash
# Install Python dependencies
pip install -r requirements.txt
