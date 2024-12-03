# Data-Mining-to-Detect-Depression-
Created a project for a Data Mining course to detect depression by implementing various deep learning algorithms, including Random Forest Classifier, Naive Bayes Classifier, K-means Clustering, and Logistic Regression. Evaluated model performance using accuracy metrics such as precision, recall, and F1-score to ensure reliable and accurate predictions.


This project focuses on predicting depression using machine learning algorithms on survey data containing variables such as age, marital status, education, and financial details. It uses different classification models (Logistic Regression, Naive Bayes, and Random Forest) and clustering techniques (K-Means) to classify individuals into "depressed" or "not depressed" categories, based on their responses.

# Key Features and Functionalities:

Data Preprocessing:

The dataset is loaded, and non-numeric variables (like sex and marital status) are encoded into numeric values for machine learning models.
The target variable, "Depressed," is separated for model training.
Classification Models:

Logistic Regression: A simple model used to predict depression and assess the accuracy and performance.
Naive Bayes: A probabilistic classifier used to determine the likelihood of depression based on survey inputs.
Random Forest: A robust ensemble model that aggregates multiple decision trees for better prediction accuracy.
Clustering:

K-Means Clustering: Segments the dataset into clusters to identify patterns in groups that may indicate depression risks.
Model Performance Evaluation:

Confusion Matrix: Evaluates the performance of models by comparing predicted labels with actual labels.
Precision, Recall, and F1-Score: These metrics assess model performance, especially in terms of detecting depressed individuals.
Purity Score: Measures the quality of clustering, indicating how well the clusters represent real groups.
Model Training and Testing:

The dataset is split into training (70%) and testing (30%) sets, and models are trained and evaluated on these sets.
Cross-validation is used to improve the model's generalizability.
Visualization:

Correlation Matrix: Visualizes the relationship between various attributes in the dataset.
Confusion Matrix: Displays true vs. predicted labels for model evaluation.
Advanced Metrics:

Computes Precision, Recall, and F1-Score for each model, providing a detailed understanding of their ability to detect depression accurately.
Final Outputs:

The Random Forest classifier achieves a perfect prediction score, with precision, recall, and F1-score all at 1.0.
# Technologies Used:

Programming Language: Python
Libraries:
Pandas for data manipulation
Scikit-learn for machine learning models and evaluation
Matplotlib for visualizations
Numpy for numerical operations
# Applications:
This project can be used in healthcare to identify individuals at risk for depression based on survey data, enabling early intervention and personalized treatment plans.
