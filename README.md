# Telco Customer Churn: Revenue Risk & Predictive Engine

## 🚀 Business Overview
In this project, I developed a predictive analytics engine to address a 26.5% churn rate within a Telecom dataset. Unlike standard churn models, this project focuses on **Revenue Recovery**, identifying a projected **$137,116.80 in annual revenue leakage.**

## 🛠️ The Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib
* **Model:** Random Forest Classifier (Optimized for Recall)
* **Environment:** Google Colab / Jupyter

## 📊 Strategic Insights
* **Revenue at Risk:** Identified $11,426/month in high-probability churn revenue.
* **Key Driver:** Fiber Optic users show significantly higher churn rates compared to DSL, suggesting a service-value mismatch.
* **Retention Lever:** Two-year contracts showed the strongest negative correlation with churn (r ≈ -0.3).

## 📉 Financial Impact
I translated model performance into business value:
1. **High-Risk Segment:** Users with >70% churn probability.
2. **Annual Leakage:** Calculated by multiplying high-risk monthly charges by 12.
3. **Recommendation:** Implementing a "Loyalty Bundle" for Fiber Optic users on month-to-month plans to mitigate $137k in potential losses.

## 🏗️ How to Run
1. Clone the repo: `git clone https://github.com/YOUR_USERNAME/telco-churn-revenue-risk-engine.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook in `/notebooks`.
