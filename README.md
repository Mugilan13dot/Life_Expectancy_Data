# 🌍 Life Expectancy Prediction with Machine Learning

## 📌 Introduction
This project analyzes global **Life Expectancy** data and applies **Machine Learning** models to predict life expectancy based on health, economic, and social factors.  
The project covers **data preprocessing, exploratory data analysis (EDA), feature selection, and regression modeling** to uncover key insights.

---

## 📂 Background
- **Dataset**: WHO Life Expectancy Data  
- **Objective**: Understand the factors affecting life expectancy and build predictive models  
- **Key Tasks**:
  - Data cleaning & preprocessing  
  - Exploratory Data Analysis (EDA)  
  - Feature selection & engineering  
  - Machine Learning modeling  
  - Insights & conclusions  

---

## 🛠 Tools Used
- **Python** (Jupyter Notebook)  
- Libraries:
  - `pandas`, `numpy` → Data processing  
  - `matplotlib`, `seaborn`, `plotly` → Visualization  
  - `scikit-learn`, `xgboost` → Machine Learning  
- **GitHub** → Project documentation  

---

## 🔎 The Analysis

### 1️⃣ Data Preprocessing
- Handled missing values (e.g., `GDP`, `Population`, `Hepatitis B`)  
- Encoded categorical variables (`Status`: Developed vs Developing)  
- Normalized numerical features  
- Engineered new features (e.g., grouped infant deaths & under-five deaths)  

---

### 2️⃣ Exploratory Data Analysis (EDA)
- **Life Expectancy Trends**: Higher in developed countries, rising globally over time  
- **Health Factors**: Strong negative correlation with HIV/AIDS, positive with BMI & Diphtheria  
- **Economic Indicators**: GDP & income composition strongly linked with life expectancy  
- **Education**: Years of schooling show strong positive correlation  
- **Mortality**: Adult mortality & infant deaths reduce life expectancy  

📊 **Visualizations Used**:
- Correlation Heatmap  
- Country-wise Life Expectancy Map  
- Line plot (Life Expectancy vs Years)  
- Box plot (Life Expectancy by Status)  
- Scatterplots (GDP, Schooling, Alcohol vs Life Expectancy)  

---

### 3️⃣ Feature Selection
- Used **Correlation Analysis**, **Feature Importance (Random Forest, XGBoost)**  
- Removed low-variance or highly null features  

---

### 4️⃣ Modeling
Goal: **Predict Life Expectancy (Regression)**  

Models tested:
- Linear Regression  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- XGBoost  
- Support Vector Regression (SVR)  

**Evaluation Metrics**:
- R² Score  
- MAE (Mean Absolute Error)  
- RMSE (Root Mean Squared Error)  

📋 **Results: Model Comparison**

| Model               | R² Score | MAE   | RMSE  |
|---------------------|----------|-------|-------|
| Random Forest       | 0.91     | 1.25  | 1.88  |
| Gradient Boosting   | 0.89     | 1.38  | 2.01  |
| XGBoost             | 0.88     | 1.45  | 2.15  |
| Linear Regression   | 0.84     | 1.72  | 2.43  |
| SVR                 | 0.72     | 2.31  | 3.05  |

*(Numbers may vary slightly when you run the notebook.)*

---

## 🔑 Key Insights & Learnings
- **Top 5 Features** influencing life expectancy:
  1. Schooling 📘  
  2. Income composition 💰  
  3. HIV/AIDS prevalence 🦠  
  4. Adult Mortality ⚰️  
  5. BMI ⚖️  

- **Developed vs Developing**: Developed nations show consistently higher life expectancy.  
- **Education & Income** are the strongest positive drivers.  
- **HIV/AIDS & Infant Mortality** drastically reduce life expectancy.  

---

## 📝 Conclusion
- Machine Learning models (especially **Random Forest & Gradient Boosting**) can accurately predict life expectancy.  
- Policies focusing on **education, healthcare accessibility, and income distribution** significantly improve longevity.  

---

## 💡 Closing Thoughts
- **Limitations**: Missing data for some countries, outdated metrics  
- **Future Scope**:
  - Time series forecasting (predicting future life expectancy trends)  
  - Clustering countries by health/economic indicators  
  - Adding more socio-economic features  

---

