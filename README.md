# Machine-Learning-Fundamentals
A comprehensive collection of machine learning exercises implemented in Python, covering everything from binary classification to clustering algorithms. This project demonstrates practical applications of supervised and unsupervised learning techniques using real-world datasets.
<br>
What This Project Does
This repository contains six machine learning exercises that progress from basic classification to advanced clustering techniques. Each exercise is implemented as a Jupyter notebook with complete code, visualizations, and analysis.
The project uses commit log data to explore various machine learning concepts:

Predicting working days vs weekends from commit patterns
Visualizing decision boundaries for different algorithms
Handling multiclass classification with categorical features
Preventing overfitting through proper data splitting
Performing regression analysis on user behavior
Discovering user groups through clustering

<br>
Files Overview
<br>
src/ex00/00_binary_classifier_logreg.ipynb
Implements binary classification using logistic regression to predict whether commits were made on weekdays or weekends. Features engineering extracts commit counts before and after midday as predictive features.
<br>
src/ex01/01_binary_classifier_svm_tree.ipynb
Compares three classification algorithms (logistic regression, SVM, decision trees) with decision boundary visualization. Demonstrates how different algorithms create different separation strategies for the same dataset.
<br>
src/ex02/02_multiclassi_one-hot.ipynb
Extends classification to predict specific weekdays using multiclass algorithms. Implements one-hot encoding for categorical features and includes random forest classification with feature importance analysis.
<br>
src/ex03/03_split_crossval.ipynb
Addresses overfitting through train-test splits and cross-validation techniques. Compares model performance using proper validation methods to ensure generalization to unseen data.
<br>
src/ex04/04_regression.ipynb
Implements regression analysis to predict average time deltas between deadlines and first commits. Uses user behavior data including newsfeed views and commit frequency as predictive features.
<br>
src/ex05/05_clustering.ipynb
Applies unsupervised learning through clustering algorithms to identify user behavior patterns. Groups users based on their activity patterns for potential targeted interventions.
<br>
Key Techniques Used

Feature Engineering: Custom extraction of temporal features from timestamp data
One-Hot Encoding: Converting categorical variables into numerical format for machine learning algorithms
Cross-Validation: K-fold validation for robust model evaluation
Decision Boundary Visualization: 2D plotting of algorithm decision surfaces
Train-Test Splitting: Proper data separation to prevent overfitting
Feature Importance Analysis: Identifying which variables contribute most to predictions

<br>
Technologies and Libraries

| Technology | Purpose |
|------------|---------|
| **[scikit-learn (0.23.1)](https://scikit-learn.org/)** | Primary machine learning library providing classification, regression, and clustering algorithms |
| **[Jupyter Notebook](https://jupyter.org/)** | Interactive development environment for data analysis and visualization |
| **[NumPy](https://numpy.org/)** | Numerical computing library for array operations and mathematical functions |
| **[Pandas](https://pandas.pydata.org/)** | Data manipulation and analysis library for structured data handling |
| **[Matplotlib](https://matplotlib.org/)** | Plotting library for creating static visualizations and decision boundary plots |

<br>
TechnologyPurposescikit-learn (0.23.1)Primary machine learning library providing classification, regression, and clustering algorithmsJupyter NotebookInteractive development environment for data analysis and visualizationNumPyNumerical computing library for array operations and mathematical functionsPandasData manipulation and analysis library for structured data handlingMatplotlibPlotting library for creating static visualizations and decision boundary plots
<br>
Project Structure

```
├── src/
│   ├── ex00/
│   ├── ex01/
│   ├── ex02/
│   ├── ex03/
│   ├── ex04/
│   └── ex05/
└── data/
```
<br>
src/: Contains all exercise notebooks organized by topic, each focusing on specific machine learning concepts
data/: Storage directory for datasets used across exercises, including processed commit logs and user behavior data

<br>

<br>
Each exercise directory (src/ex00/, src/ex01/, etc.) contains a single Jupyter notebook that implements the complete machine learning pipeline for that specific technique, from data preprocessing through model evaluation and visualization.


