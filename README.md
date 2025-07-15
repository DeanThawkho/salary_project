# Salary Prediction Based on Years of Experience

This is a beginner-friendly data analysis project that explores how **years of experience** affects **Salary**. The project uses a real-world-style dataset containing employee information such as age, gender, education level, job title, years of experience, and salary.

The goal is to perform **Exploratory Data Analysis (EDA)**, create visualizations, and build a **Linear Regression Model** to predict salary based on years of experience.

---

## Dataset

The dataset includes the following columns:

- `Age` : Employee's age
- `Gender` : Male / Female
- `Education Level` : High School, Bachelor's Degree, Master's Degree, PhD
- `Job Title` : Software Engineer, Data Scientist, Manager, etc.
- `Years of Experience` : Number of years of experience in the current job
- `Salary` : Salary of the employee

> **Note**: This dataset is used for educational purposes only and may be synthetic.

---

## Project Steps

1. **Data Loading & Cleaning**
    - Handled missing values
    - Verified data types and ranges

2. **Exploratory Data Analysis (EDA)**
    - Analyzed distributions of salary and experience
    - Visualized correlations using scatter plots and heatmaps

3. **Model Building**
    - Built a simple Linear Regression model to predict salary using only years of experience
    - Trained the model using 80% of the data and tested on the remaining 20%

4. **Model Evaluation**
    - Achieved an **R² score of 0.65**, showing strong correlation
    - Calculated RMSE to estimate prediction error (~$31,000)

---

## Example visualizations

- **Scatter Plot**: Salary vs. Years of Experience
- **Histogram**: Distribution of Salary
- **Heatmap**: Correlation Matrix

---

## Key Insights

- There is a strong **positive correlation** between years of experience and salary
- On average, **each additional year of experience increases the salary by ~$7,000**
- The model explains ~65% of salary variance using experience alone.