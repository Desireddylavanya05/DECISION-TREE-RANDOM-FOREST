# DECISION-TREE-RANDOM-FOREST

🌳 Decision Tree & Random Forest Classifier Workshop
This repository is a practical guide to understanding and implementing two powerful machine learning algorithms — Decision Trees and Random Forests — using the classic Iris dataset. It walks through model building, training, evaluation, and optimization using scikit-learn.

📘 What’s Inside?
✅ Understanding how decision trees split data

✅ Using Random Forests to improve accuracy and reduce overfitting

✅ Hyperparameter tuning using GridSearchCV

✅ Comparing model performance using classification metrics

🧠 Learning Objectives
By the end of this notebook, you’ll be able to:

Build classification models using decision trees and random forests

Understand entropy, Gini impurity, and information gain

Apply model evaluation metrics like accuracy, precision, recall, and F1-score

Optimize models using grid search with cross-validation

📊 Dataset Used
Iris Dataset

3 classes: Setosa, Versicolor, Virginica

4 features: sepal length, sepal width, petal length, petal width

Multiclass classification task

🔧 Tools & Technologies
Python 3

Jupyter Notebook

scikit-learn

pandas

numpy

matplotlib / seaborn (optional for visualizations)

🚀 Highlights
🔹 Decision Tree Classifier
Simple and interpretable

Trained on 80% of the Iris data

Evaluated using accuracy score and classification report

🔹 Random Forest Classifier
Uses an ensemble of multiple decision trees

More robust and less prone to overfitting

Grid search used to tune n_estimators, max_depth, etc.

🔹 Model Evaluation
Metrics: accuracy_score, classification_report

Insights into precision, recall, and F1-score for each class

🧪 Sample Results
Model	Accuracy	Notes
Decision Tree	~93%	Good performance
Random Forest (Tuned)	~96–98%	Improved stability & accuracy

🗂️ Folder Structure
bash
Copy
Edit
decision-tree-random-forest/
├── task 1&2.ipynb           # Notebook with both regression and classification tasks
├── README.md                # Project documentation
├── requirements.txt         # (Optional) Python dependencies
└── outputs/                 # (Optional) Saved graphs or reports
💡 Ideal For
Beginners in ML

Data science students

Bootcamp projects or academic demos

👣 Next Steps (Suggestions for Extension)
Visualize decision trees using plot_tree()

Feature importance plots from Random Forest

Try on different datasets (e.g., Wine, Breast Cancer)

