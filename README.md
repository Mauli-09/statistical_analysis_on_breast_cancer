# 🧬 Statistical Analysis on Breast Cancer Dataset

This project involves a detailed **statistical analysis** of a breast cancer dataset to uncover meaningful patterns, understand variable distributions, and evaluate relationships using various **descriptive and inferential statistics techniques**. The analysis includes **measures of central tendency, dispersion, skewness, kurtosis**, and multiple **hypothesis tests** like t-test, z-test, ANOVA, chi-square, and F-test.

---

## 📁 Dataset Overview

- **File:** `Cancer_dataset2.csv.xlsx`
- **Context:** The dataset represents patient data related to breast cancer including age, tumor size, lymph nodes examined, and survival months.
- **Key Variables Used:**
  - `Age` – Age of the patient
  - `Tumor Size` – Size of the tumor in mm
  - `Regional Node Examined` – Number of lymph nodes examined
  - `Reginol Node Positive` – Number of positive lymph nodes
  - `Survival Months` – Total months survived after diagnosis

---

## 📌 Project Objectives

1. Perform **exploratory data analysis (EDA)** on key numerical variables
2. Calculate **statistical measures** to understand distribution and variability
3. Use **hypothesis testing** to compare assumptions about population parameters
4. Interpret results to gain insights into patterns related to breast cancer features

---

## 📊 Descriptive Statistical Analysis

### ✅ Central Tendency
- **Mean:** The average value of each variable
- **Median:** The middle value separating the higher and lower halves
- **Mode:** The most frequently occurring value

### ✅ Measures of Dispersion
- **Range:** Difference between max and min values
- **Quartiles & Percentiles:** Data spread into 4 and 100 parts
- **Variance & Standard Deviation:** Spread of data around the mean
- **Standard Error:** Measure of the accuracy of the mean
- **Mean Deviation:** Average of absolute deviations from the mean
- **Coefficient of Variation (CV):** Ratio of std. deviation to the mean (used for comparing variability)

### ✅ Distribution Shape
- **Skewness:** Degree of asymmetry in the distribution
- **Kurtosis:** Tailedness or peakedness of the distribution

---

## 🧪 Hypothesis Testing

Several tests were applied to verify assumptions or relationships among variables:

### 📄 Test Summary:
T-Test (Age = 50) ~ 15.743 ~ 3.06e-51 ~ Reject H₀

T-Test (Tumor Size = 30) ~ 0.964 ~ 0.335 ~ Fail to Reject H₀

Z-Test (Age = 50) ~ 15.743 ~ ~0.0 ~ Reject H₀

F-Test (Var[Age] vs Var[Tumor Size]) ~ 0.164 ~ 1.0 ~ Fail to Reject H₀

Chi-square (Age vs Survival) ~ 7.051 ~ 0.632 ~ Fail to Reject H₀

ANOVA (Tumor Size ~ Age Group) ~ 4.077 ~ 0.0068 ~ Reject H₀

# 🛠 Tools and Libraries Used

- **Language:** Python 3  
- **Notebook:** Jupyter / Google Colab  
- **Libraries:**
  - `pandas`, `numpy` – for data manipulation
  - `scipy.stats` – for statistical tests
  - `statsmodels` – for ANOVA
  - `matplotlib`, `seaborn` – (optional for visualization)

---

## 🧪 How to Run the Project

1. Clone this repository or upload the notebook to Colab
2. Install the required packages:
   ```bash
   pip install pandas numpy scipy statsmodels
Run the notebook statistical_analysis_project.ipynb

The output cells contain all analysis results and interpretations

💡 Future Enhancements
Add interactive visualizations (Plotly, Seaborn)

Build an automatic statistical report generator

Expand analysis to include categorical variables (e.g., diagnosis, stages)

Create a Streamlit dashboard for dynamic exploration

👤 Author
MAULI
Machine Learning and Data Science Student
