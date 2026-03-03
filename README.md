
Categorized into:

- Alone  
- Small Family (2–4 members)  
- Large Family (>4 members)  

---

### ✅ Cabin Indicator

Created a binary feature:

- `HasCabin` (1 if cabin present, 0 otherwise)

Used as a proxy for wealth.

---

### ✅ Embarked Encoding

Encoded port of embarkation for structured analysis.

---

## 📊 Final Conclusion and Summary of Insights

This end-to-end EDA has provided a deep understanding of the Titanic dataset. The analysis confirms the historical **"women and children first"** narrative and highlights stark social inequalities of the time.

Through feature engineering, we have created stronger predictors for future machine learning modeling.

---

## 🔑 Key Findings

### 1️⃣ Strongest Predictors of Survival

- **Title & Sex**
  - Being female (`Mrs`, `Miss`) was the single most significant advantage.
  - The engineered `Title` feature captured nuance better than `Sex` alone.
  - Young boys (`Master`) had much higher survival rates than adult men (`Mr`).

- **Passenger Class**
  - Clear survival hierarchy:
  
    1st Class > 2nd Class > 3rd Class

- **Age**
  - Children and infants had higher survival probability.

---

### 2️⃣ Other Influential Factors

- **Family Size**
  - Small families (2–4 members) had higher survival rates.
  - Traveling alone or in very large families reduced survival probability.

- **Fare & Cabin**
  - Higher fare strongly correlated with survival.
  - Having a cabin acted as a proxy for wealth and class.

- **Port of Embarkation**
  - Passengers from Cherbourg (`C`) had higher survival rates.
  - Likely due to higher concentration of 1st class passengers.

---

## 📁 Project Structure

```
titanic-eda-feature-engineering/
│
├── data/
│   └── train.csv # Original Titanic dataset
│
├── titanic_eda_feature_engineering.ipynb  # Complete EDA & Feature Engineering
├── images/
│   ├── correlation_matrix_numerical_features.png
│   ├── bivariate_analysis.png
│   ├── age_by_survival.png
│   └── survival_by_family_size.png
│
└── README.md             # Project documentation
```

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 🎯 What This Project Demonstrates

✔ Strong data cleaning skills  
✔ Structured exploratory data analysis  
✔ Feature engineering capability  
✔ Insight extraction from real-world dataset  
✔ Analytical storytelling with data  

This project builds a solid foundation for future predictive modeling work.

---

## 👨‍💻 Author

**Ashutosh Agrawal**  
B.Tech – Electronics & Communication  
Aspiring Data Scientist
