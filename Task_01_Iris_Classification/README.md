# Multi-Class Benchmark Classification Pipeline

## Project Overview
This project implements a multi-class classification pipeline using the Iris dataset. Two machine learning algorithms are trained and evaluated to classify Iris flowers into three species.

## Dataset
- Dataset: Iris Dataset
- Total Records: 150
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- Target: Species
- Classes: Setosa, Versicolor, Virginica

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Load and explore the Iris dataset.
2. Check missing values and dataset distribution.
3. Visualize the data using a pairplot.
4. Split the dataset into 80% training data and 20% testing data.
5. Apply StandardScaler for feature scaling.
6. Train Logistic Regression and Decision Tree models.
7. Evaluate both models using accuracy, precision, recall, and F1-score.
8. Generate classification reports and confusion matrices.
9. Visualize decision boundaries.

## Model Performance

| Metric | Logistic Regression | Decision Tree |
|---|---:|---:|
| Accuracy | 93.33% | 93.33% |
| Precision | 93.33% | 93.33% |
| Recall | 93.33% | 93.33% |
| F1-score | 93.33% | 93.33% |

## Conclusion
Both models achieved 93.33% accuracy on the test dataset. The project demonstrates a complete multi-class classification workflow, from data exploration and preprocessing to model evaluation and visualization.

## Project Files
- `iris.csv` – Dataset used for classification.
- `iris_classification.ipynb` – Notebook containing the complete implementation.
