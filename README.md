# 🧠 Titanic Survival Analysis - Exploratory Data Analysis (EDA)

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns, trends, and relationships that help understand passenger survival outcomes. The goal is to extract actionable insights using visual and statistical techniques.

---

## 📌 Objective

- Conduct in-depth EDA on the Titanic dataset.
- Use statistical summaries and visualizations to understand survival patterns.
- Identify relationships among features (e.g., age, class, fare, family size).
- Highlight outliers and data skewness to guide future preprocessing or modeling.

---

## 🧰 Tools & Libraries Used

- **Python 3**
- **Jupyter Notebook**
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization

---

## 📊 Key Steps Performed

### 1. **Data Exploration**
- Used `.info()`, `.describe()`, and `.value_counts()` to understand:
  - Missing values
  - Data types
  - Distribution of categorical variables

### 2. **Visual Analysis**
- Plotted:
  - **Histograms** to observe feature distributions
  - **Boxplots** to detect outliers
  - **Scatterplots** and **pairplots** to find relationships
  - **Heatmaps** to analyze feature correlation

### 3. **Outlier Detection**
- Identified notable outliers in features like:
  - `Fare`, `Age`, `SibSp`, and `Parch`

### 4. **Summary of Findings**
- First-class passengers had a higher survival rate.
- Females had better survival chances.
- Younger passengers showed slightly better survival odds.
- Fares were highly skewed, with some very high-ticket prices.
- Family size had some impact on survival, especially if traveling alone or in large groups.

---

## 📄 Deliverables

- ✅ Colab Notebook (`Task_5.ipynb`)
- ✅ Markdown Summary (`README.md`)

---

## 🧩 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/titanic-eda-project.git
   cd titanic-eda-project

