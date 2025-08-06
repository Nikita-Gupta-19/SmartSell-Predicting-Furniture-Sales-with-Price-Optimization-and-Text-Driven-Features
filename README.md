# 🪑 SmartSell Predicting Furniture Sales using Data Science Analysis

A full-scale data science and business intelligence project analyzing the sales trends, pricing dynamics, and shipping behavior of e-commerce furniture products. This project leverages Python, machine learning, SHAP, and Power BI dashboards to derive actionable insights from raw sales data.

---

## 📌 Objective

To clean, analyze, and visualize an e-commerce furniture dataset with the aim of:
- Understanding pricing buckets and shipping impacts
- Predicting sales performance using ML models
- Creating insightful dashboards using Power BI

---

## 🧰 Tools & Technologies Used

- **Python** – Data Cleaning, Feature Engineering, ML Modeling  
- **Google Colab** – Development Environment  
- **Power BI** – Interactive Dashboard Creation  
- **Pandas, NumPy** – Data Manipulation  
- **Matplotlib, Seaborn** – Visual Exploration  
- **Scikit-learn** – ML Regression Models  
- **SHAP** – Model Interpretability  
- **XGBoost** – Advanced Modeling  

---

## 📁 Dataset

The dataset includes:
- Product details: `originalPrice`, `price`, `sold`, `shipping`, `discount_rate`  
- NLP Features: `title_sentiment`, `has_wood`, `has_modern`, `tagText`  
- Engineered columns: `price_bucket`, `price_bins`, `shipping_type`  
- Final feature-rich CSV: `furniture_data_final.csv`

---

## 📊 Exploratory Data Analysis (EDA)

- Price and discount distributions  
- Shipping type frequency  
- Tag sentiment vs sales patterns  
- Correlation heatmaps of all numerical features  
- Keyword-based feature extraction (e.g., modern, wood, adjustable)  

---

## 🤖 ML Modeling & Evaluation

Applied multiple regression models to predict `sold` units:
- **Linear Regression**
- **Ridge Regression**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **XGBoost Regressor**

**Metrics Evaluated**:
- R² Score  
- RMSE  
- Cross-validation with 5 folds (visualized using barplots)

### 🧠 SHAP Interpretation
SHAP values were used to explain:
- Which features most impacted sales  
- How discount rates, wood/modern tags, and shipping type affected predictions  

---

## 📊 Power BI Dashboard Highlights

1. **Pie Chart** – Distribution of Products by Price Range (Low, Medium, Premium)  
2. **Bar Chart** – Average `sold` by Shipping Type  
3. **Line Chart** – Sales Trend across `price_bins`  
4. **KPI** – Total Items Sold  
5. **Scatter Plot** – Sales vs Price with discount overlay  
6. **Data Table** – View of final dataset inside Power BI  

> ✨ All visuals are dynamic, filterable, and connected for better exploration

---

## 🔍 Key Insights

- **Free Shipping** items had the highest average sales  
- Discount rate correlates positively with sales beyond a certain threshold  
- Most products fall in the **Low to Medium price category**  
- Modern or adjustable features didn’t guarantee higher sales but contributed positively when paired with discounting  
- **Random Forest** provided the best ML performance in terms of R²  

---

## 📦 Power BI Report

- Open the `Furniture_Analysis.pbix` file in Power BI Desktop  
- Interact with filters like **Price Range**, **Shipping Type**, and **Product Features**  
- Use KPI cards and charts to answer specific business questions  

---

## 🧠 Future Scope

- Integrate **time-series forecasting** if temporal data becomes available  
- Add **category segmentation** if product types are provided  
- Extend dashboard with **customer segmentation**  
- Host dashboard on **Power BI Online or Streamlit Web App**  

---

## 🙌 Acknowledgements

- **Dataset**: Intern project dataset – "E-commerce Furniture Dataset 2024"  
- **Mentorship**: Data Science Internship Stipend-based Project  
- **Tools**: Google Colab, Power BI Desktop, Python  

---

## 📬 Contact

**Nikita Gupta**  
📧 [Email](mailto:nikitagpt06@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/nikita-gupta-790a54284/)  
💻 [GitHub](https://github.com/Nikita-Gupta-19)

