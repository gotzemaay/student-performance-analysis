# student Performance Analysis

This project analyzes student data to understand what factors affect academic performance and predicts students' final grades using machine learning models.

## Objective
- Explore how different features (study time, absences, etc.) influence final grades (`G3`)
- Compare performance of:
  - Linear Regression
  - Decision Tree Regressor

## Dataset
- Source: [UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/student+performance)
- File used: `student-mat.csv` (Math grades)

## Tools Used
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Jupyter / VS Code

## Key Insights
- `G2` (previous period grade) is the **strongest predictor** of final grade
- `Absences` negatively impact performance
- Choosing school for being "close to home" (`reason_home`) shows a subtle effect

## Model Results

| Model               | R² Score | Mean Squared Error |
|--------------------|----------|---------------------|
| Linear Regression  | ~0.72    | 5.66                |
| Decision Tree      | (Your R² here) | (Your MSE here)      |

## Visualizations
- Correlation heatmaps
- Study time vs grade boxplots
- Prediction vs actual scatter plots
- Feature importance bar chart

## How to Run
1. Clone this repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open `notebooks/eda.ipynb` and follow the steps

---


