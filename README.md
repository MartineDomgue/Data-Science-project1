# Diabetes Data Analysis

This project involves statistical analysis and visualization of a dataset related to diabetes progression. It uses methods from probability, statistics, and data science to explore relationships between health indicators and disease outcomes.

## 📁 Dataset Overview

The dataset contains patient-level measurements including:

- **AGE**: Age of the patient
- **SEX**: Gender (1 = Male, 2 = Female)
- **BMI**: Body Mass Index
- **BP**: Average Blood Pressure
- **S1–S6**: Various blood serum measurements
- **Y**: A quantitative measure of disease progression one year after baseline

The data was provided in `.tsv` format and loaded into a Pandas DataFrame for analysis.

---

## 🧪 Tasks Performed

### ✅ Task 1: Compute Summary Statistics
- Calculated **mean** and **variance** for each variable in the dataset.

### ✅ Task 2: Boxplot Analysis by Gender
- Visualized **BMI**, **Blood Pressure (BP)**, and **Y** (disease progression) using boxplots grouped by gender.

### ✅ Task 3: Distribution Analysis
- Created histograms for **Age**, **Sex**, **BMI**, and **Y** to understand variable distributions.

### ✅ Task 4: Correlation Analysis
- Generated a **correlation matrix** and **heatmap** to assess relationships between variables, especially how strongly they correlate with disease progression (Y).

### ✅ Task 5: Hypothesis Testing
- Performed a **two-sample t-test** to evaluate whether disease progression differs significantly between men and women.

---

## 📊 Key Findings

- Women in the dataset tend to have **higher BMI and BP** than men.
- Disease progression (Y) shows **greater variability in men** and **more consistency in women**.
- Certain variables such as **BMI and S5** appear to have strong correlations with disease progression.
- A t-test revealed a **statistically significant** difference in Y between genders (if p < 0.05).

---

## 🔧 Technologies Used

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- SciPy

---

## 📂 File Structure

📦 diabetes-analysis/
├── diabetes_data.tsv # The dataset
├── analysis.ipynb # Jupyter notebook with all tasks
├── README.md # This file

