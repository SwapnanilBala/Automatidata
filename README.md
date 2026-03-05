# Automatidata - NYC Cab Generous Tip Predictor

---

### Project Objective

For this project, I worked with the **New York City Taxi & Limousine Commission (TLC)** dataset through a fictional consulting firm called **Automatidata**. The main goal was to build a **machine learning model** that predicts how likely a taxi driver is to receive a generous tip from a passenger.

I went through a full data science workflow here — starting from raw data inspection all the way to training and evaluating ML models. Along the way, I cleaned the data, ran statistical tests, and tried out different modeling approaches to see what works best.

---

### Project Overview

I organized the project into separate folders, each covering a different stage of the analysis. If you want to follow along with my thought process, I'd recommend going through them in this order:

1. **Root Folder — Preliminary Analysis**
   Initial look at the dataset structure, data quality checks, and some basic observations.

2. **Exploratory Data Analysis (EDA)**
   Deeper visual exploration, handling missing data, detecting outliers, and studying correlations between variables.

3. **Statistical Review & A/B Testing**
   Hypothesis testing to validate assumptions about what drives fare and tip amounts.

4. **Multiple Linear Regression Model**
   My first attempt at regression modeling, including checking for multicollinearity.

5. **Machine Learning Model Building**
   More advanced models using ensemble methods and boosting algorithms to improve prediction accuracy.

---

### Tech Stack & Libraries

Here's what I used throughout the project:

**Data Wrangling & Analysis**
- `pandas` — data manipulation and preprocessing
- `numpy` — numerical computation
- `datetime` — working with timestamps

**Data Visualization**
- `matplotlib.pyplot`
- `seaborn`

**Machine Learning & Modeling**
- From `scikit-learn`:
  - `StandardScaler`, `train_test_split`
  - `DecisionTreeClassifier`, `RandomForestClassifier`, `LinearRegression`, `GridSearchCV`
- `XGBoost` — gradient boosting, along with `plot_importance` for feature visualization

**Model Evaluation**
- `f1_score`, `roc_curve`, `accuracy_score`, `recall`, `precision`

---

### Key Findings

- There are strong correlations between trip distance, duration, and fare amount in the dataset.
- I found several outliers and some missing entries during EDA, which I handled before modeling.
- Feature scaling and one-hot encoding made a noticeable difference in model stability.
- Ensemble models like Random Forest and XGBoost performed significantly better than basic regression.
- The final model achieved solid predictive accuracy on the test set.

---

### Outcome

By the end of this project, I had a working ML pipeline that can predict with reasonable accuracy whether a driver will receive a generous tip. The insights from this analysis could be useful for improving fare transparency and understanding tipping behavior in NYC taxis.

---

### Connect With Me

LinkedIn: [Swapnanil Bala](https://www.linkedin.com/in/swapnanil-bala-854b722a7/)
Data Science Student | Machine Learning Enthusiast | Python & SQL Practitioner

---
