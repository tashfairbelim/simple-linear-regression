# Simple Linear Regression Mini Project

## Project Overview

This project demonstrates the implementation of **Simple Linear Regression** to predict a student's **exam score** based on the number of **hours studied per day**.

It is part of the **Machine Learning Theory coursework** for **M.Sc. Data Science (Semester II)**.

---

## Objective

To:

* Understand the relationship between study hours and exam performance
* Build a predictive model using **Simple Linear Regression**
* Evaluate model performance using standard regression metrics

---

## Concept Used

### Simple Linear Regression

A supervised machine learning algorithm used to model the relationship between:

* **Independent Variable (X):** Hours Studied
* **Dependent Variable (y):** Exam Score

### Mathematical Equation:

[
y = \beta_0 + \beta_1 X + \epsilon
]

---

## Dataset Information

* **Dataset Type:** Synthetic (generated using NumPy)
* **Records:** 100 students
* **Features:**

| Column          | Description                     |
| --------------- | ------------------------------- |
| `hours_studied` | Number of hours studied per day |
| `exam_score`    | Exam score (out of 100)         |

---

## Technologies Used

* Python 
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Workflow

1. **Data Generation**

   * Created a realistic dataset using NumPy

2. **Data Exploration**

   * Checked dataset structure, statistics, and quality
   * Verified no missing or duplicate values

3. **Exploratory Data Analysis (EDA)**

   * Distribution plots
   * Scatter plots (Hours vs Score)
   * Boxplots for outlier detection

4. **Data Preprocessing**

   * Feature-target split
   * Train-test split (80/20)

5. **Model Building**

   * Implemented **LinearRegression** from sklearn
   * Trained model on training data

6. **Model Evaluation**

   * R² Score
   * MAE (Mean Absolute Error)
   * MSE (Mean Squared Error)
   * RMSE (Root Mean Squared Error)

---

## Results & Insights

* Strong positive linear relationship between study hours and exam scores
* Model successfully predicts exam performance with good accuracy
* Increased study hours generally lead to higher scores

---

## Sample Visualization

* Scatter plot showing linear trend
* Regression line fitting the data
* Distribution of study hours and scores

---

## How to Run the Project

1. Clone the repository:

```bash
git clone [https://github.com/your-username/your-repo-name](https://github.com/tashfairbelim/simple-linear-regression).git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the Jupyter Notebook:

```bash
Simple_Linear_Regression_MiniProject (1)
```

---

Conclusion

The project demonstrates that Simple Linear Regression effectively captures the relationship between study hours and exam scores. The model provides reliable predictions, confirming a strong positive correlation between the variables.
