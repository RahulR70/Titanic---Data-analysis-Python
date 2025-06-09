# Titanic Data Analysis 

This project explores the **Titanic** dataset using Python libraries like `pandas`, `seaborn`, and `matplotlib`. The goal is to perform basic exploratory data analysis (EDA), identify trends, and visualize relationships between features and survival outcomes.

---

## Dataset

- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- File: `train.csv`
- Records: 891 passengers
- Features: Passenger details including class, age, gender, fare, and survival status.

---

## Analysis Tasks

### a. Data Exploration
- Used `.info()`, `.describe()`, and `.value_counts()` for understanding data types and distributions.

### b. Visualizations
- `sns.pairplot()` – Visualize relationships between features.
- `sns.heatmap()` – Correlation matrix.
- Histograms, boxplots, and scatterplots for deeper insight.

### c. Insights Identified
- Higher **fare** correlates with higher survival.
- **Pclass** (Passenger Class) significantly affects survival rate.
- **Age** and **family connections** (SibSp, Parch) also show trends in survival.



