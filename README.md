1. Walmart Sales Forecasting
Overview: A comprehensive regression analysis project to predict weekly retail sales using environmental and economic indicators.

Data Preprocessing: Handled categorical store data and time-series elements to prepare the dataset for regression modeling.

Regularized Regression: Implemented Multiple Linear Regression, Ridge, and Lasso models.

Hyperparameter Tuning: Optimized the α (lambda) penalty term for Ridge and Lasso using cross-validation to prevent overfitting.

Comparative Analysis: Evaluated model performance across all three methods to identify the impact of L1 and L2 regularization on retail forecasting accuracy.

Tech Stack: Python, Pandas, Scikit-learn, Statsmodels.

2. Framingham Heart Disease Risk Prediction
Overview: A medical data science project utilizing the Framingham dataset to predict the 10-year risk of Coronary Heart Disease (CHD) using logistic regression.

Feature Selection: Employed Backward Elimination to identify the most statistically significant demographic, behavioral, and medical risk factors.

Model Optimization: Conducted sensitivity analysis on classification thresholds to optimize the balance between sensitivity (recall) and specificity.

Performance Metrics: Evaluated the model using Accuracy, Sensitivity, and Specificity, alongside ROC/AUC curves to determine the optimal decision boundary.

Clinical Insight: Focused on creating an interpretable model that pinpoints key risk drivers like BMI, blood pressure, and smoking habits.

Tech Stack: Python, Scikit-learn, Matplotlib (ROC Analysis).

3. Multi-class BMI Classification
Overview: A classification project focused on estimating Body Mass Index categories while addressing the challenges of a highly imbalanced and small-scale dataset.

Multi-class Strategies: Developed and compared three distinct classification approaches: One-vs-Rest (OvR), One-vs-One (OvO), and Softmax Regression.

Imbalance Handling: Implemented strategies to manage the classification of six distinct weight categories (from Extremely Weak to Extreme Obesity).

Comparative Evaluation: Analyzed the trade-offs between OvR and OvO strategies in terms of computational efficiency and predictive accuracy for imbalanced classes.

Tech Stack: Python, NumPy, Scikit-learn.
