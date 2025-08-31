# 🧪 Cancer Data Analysis (2015–2024)

## 📌 Project Overview  
This project analyzes a synthetic dataset of **50,000 cancer patients** across **10 countries (2015–2024)**.  
The aim was to uncover **patterns in demographics, cancer types, risk factors, survival years, and treatment costs**, along with applying **statistical tests and machine learning models** to identify key predictors of cancer severity.  

---

## 📊 Objectives  
- Perform **Exploratory Data Analysis (EDA)** to understand patient demographics, cancer stages, and risk factors.  
- Analyze **early-stage detection rates** across different cancer types.  
- Study the **economic burden** of cancer treatment across demographics and countries.  
- Identify **key predictors** of cancer severity and survival years using **statistical tests** and **Random Forest** models.  
- Evaluate whether higher costs or later stages impact **survival rates**.  

---

## 🔑 Key Insights  
- **Demographics**: Patients represented **10 countries & 8 cancer types** → enabled cross-country & type-wise comparisons.  
- **Risk Factors**: Smoking (23%) & Genetic Risk (22%) emerged as the strongest predictors of cancer severity.  
- **Early Detection**: ~38–41% of cancers were diagnosed at **Stage 0–I**, with **Liver Cancer** showing the highest early-diagnosis rate.  
- **Economic Burden**: Treatment costs were highest in **USA, Australia, and China**; lower in India & Pakistan.  
- **Survival Years**: No significant correlation between treatment cost and survival years.  
- **Feature Importance (Random Forest)**: Smoking, Genetic Risk, and Air Pollution were the **top drivers** of cancer severity.  

---

## 🛠️ Tools & Libraries Used  
- **Programming**: Python  
- **Data Handling**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Statistics**: Scipy (Hypothesis Testing, Correlation, Kruskal-Wallis Test)  
- **Machine Learning**: Scikit-learn (Random Forest, Feature Importance)  

---

## 📂 Project Workflow  
1. **Data Loading & Cleaning**  
   - Checked for missing/duplicate values  
   - Encoded categorical variables  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of age, gender, and cancer types  
   - Treatment cost and risk factor analysis  

3. **Statistical Analysis**  
   - Correlation tests (Pearson, Spearman)  
   - Hypothesis testing for cost vs. survival & cancer stages  

4. **Predictive Modeling**  
   - Random Forest for severity prediction  
   - Feature importance analysis  

5. **Key Insights & Visualization**  
   - Charts for demographics, risk factors, costs, survival  

---

## 📈 Visuals & Insights  
- Distribution plots for **Age, Gender, Cancer Stages**  
- Risk factor vs. severity (regression plots)  
- Country-wise **treatment cost heatmaps**  
- Random Forest **feature importance bar charts**  

---

## 🚀 Future Work  
- Apply **advanced ML models (XGBoost, Neural Networks)** for better survival prediction.  
- Include **time-series analysis** to evaluate trends in cancer incidence & survival.  
- Explore **interaction effects** between multiple risk factors.  

---

## 📎 How to Run  
1. Clone this repository  
```bash
git clone https://github.com/yourusername/cancer-data-analysis.git
```
2. Install dependencies  
```bash
pip install -r requirements.txt
```
3. Run the Jupyter Notebook  
```bash
jupyter notebook Cancer_Data_Analysis.ipynb
```

---

## 📌 Author  
👨‍💻 **Parth Sharma**  
- Data Analyst | Python | SQL | Power BI | Machine Learning  
- [LinkedIn](https://www.linkedin.com/in/parthsh0772) | [GitHub](https://github.com/parthsh0772)  
