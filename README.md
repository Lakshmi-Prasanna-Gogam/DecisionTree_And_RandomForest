# DecisionTree_And_RandomForest

This project demonstrates how to use **Decision Trees** and **Random Forests** to classify heart disease using a real-world dataset.

# Objective

Learn how to build and evaluate **tree-based models** for **classification and regression** using the `heart.csv` dataset.

## ⚙ Tools & Libraries

- Python
- Scikit-learn
- Pandas
- Matplotlib
- Graphviz (for visualization, optional)


##  Data Preprocessing

- Checked for missing values with `dropna()`
- No categorical variables needed encoding
- Features (`X`) and labels (`y`) split for training and testing
- Used `train_test_split()` for an 80/20 data split


##  Decision Tree Classifier

A **Decision Tree** was trained using `DecisionTreeClassifier()`:


Evaluated Accuracy

# Visualization
The tree structure was plotted using plot_tree() to visualize splits.

# Overfitting & Depth Control
The full-depth tree shows high accuracy on both train and test sets.

To reduce potential overfitting, tree depth can be tuned using max_depth.

# Random Forest Classifier

Trained a Random Forest using RandomForestClassifier() to reduce variance and improve accuracy

# Feature Importance

Feature importances from the Random Forest were extracted to understand key predictors

# Cross-Validation

Performed 5-fold cross-validation for both models
