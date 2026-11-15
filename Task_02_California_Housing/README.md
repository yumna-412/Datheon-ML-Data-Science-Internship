# Task 2: California Housing Price Prediction

## Objective
To develop a Machine Learning model using Linear Regression to predict house prices based on California housing data.

## Dataset
California Housing Dataset (`housing.csv`)

- Total Records: 20,640
- Features: Housing location, age, rooms, bedrooms, population, households, median income, and ocean proximity.
- Target Variable: `median_house_value`

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- VS Code

## Project Workflow
1. Imported required libraries.
2. Loaded and explored the dataset.
3. Checked and handled missing and duplicate values.
4. Performed Exploratory Data Analysis.
5. Visualized house price distribution and feature correlations.
6. Encoded categorical variables.
7. Split the dataset into training and testing sets.
8. Built and trained a Linear Regression model.
9. Generated house price predictions.
10. Evaluated model performance.

## Model Performance

| Metric | Result |
|---|---:|
| MAE | 50413.43 |
| RMSE | 69297.72 |
| R² Score | 0.6488 |

## Conclusion
The Linear Regression model achieved an R² score of 0.6488, explaining approximately 64.88% of the variation in house prices. This project provided practical experience in data preprocessing, visualization, regression modelling, and model evaluation.

## Files
- `housing.csv` – Dataset
- `california_housing_prediction.ipynb` – Jupyter Notebook containing the complete implementation
- `README.md` – Project documentation
