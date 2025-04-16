# EDA
# Titanic Survival Data Analysis 🛳️

This project explores the Titanic dataset to identify factors affecting passenger survival. It uses Python libraries such as pandas, seaborn, and matplotlib for data analysis and visualization.

---

## 📦 Dataset

- Dataset used: Titanic dataset (from Kaggle or local source)
- Rows: 891 passengers
- Columns: Passenger details including age, fare, class, sex, etc.

---

## 📊 Exploratory Data Analysis (EDA)

### Descriptive Stats
- `.info()`, `.describe()`, `.value_counts()` used for data inspection

### Visualizations
- **Histograms**: Age, Fare
- **Boxplots**: Age vs. Survived, Fare vs. Survived
- **Heatmap**: Correlation between numerical features
- **Pairplot**: Relationships between key features and survival

### Key Findings
- Passengers in higher classes had higher survival rates
- Females and younger passengers were more likely to survive
- Higher fares correlated with better survival
- Many outliers observed in Fare values

---

## 🛠️ How to Run

1. Clone this repo or open the Jupyter Notebook.
2. Make sure the following Python libraries are installed:
   - pandas
   - matplotlib
   - seaborn
3. Run the notebook cells to perform the analysis and generate visualizations.

---

## 📚 Summary

This analysis highlights the importance of class, fare, age, and gender in determining survival rates on the Titanic. The visualizations provide insights into how these factors contributed to survival outcomes.

---
