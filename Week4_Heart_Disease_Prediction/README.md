# Heart Disease Prediction Using Machine Learning

## 1. Project Overview
This project uses machine learning classification algorithms to predict the presence or absence of heart disease based on patient health-related features. The UCI Heart Disease dataset is used to train and compare Logistic Regression and Decision Tree models.

## 2. Project Objectives
- Clean and preprocess the dataset.
- Handle missing values using imputation.
- Encode categorical features and scale numerical features.
- Train Logistic Regression and Decision Tree models.
- Evaluate models using Accuracy, Precision, Recall, F1-score, and ROC-AUC.
- Visualize performance using confusion matrices and ROC curves.

## 3. Dataset
- Dataset: UCI Heart Disease dataset
- File: heart_disease_uci.csv
- Original records: 920
- Original columns: 16
- Target variable: target

The original target column, num, was converted into a binary target:
- 0: No heart disease indicated in the dataset
- 1: Heart disease indicated in the dataset

## 4. Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 5. Data Preprocessing
1. Inspected the dataset and checked missing values and duplicate rows.
2. Removed unnecessary identifier and original target columns.
3. Created a binary target variable.
4. Split the dataset into 80% training data and 20% testing data.
5. Imputed missing numerical values using the median.
6. Imputed missing categorical values using the most frequent value.
7. Scaled numerical features using StandardScaler.
8. Encoded categorical features using OneHotEncoder.

## 6. Machine Learning Models

### Logistic Regression
A supervised classification algorithm used to estimate the probability of a binary outcome.

### Decision Tree
A supervised classification algorithm that makes predictions using feature-based decision rules.

## 7. Model Evaluation Results

| Metric | Logistic Regression | Decision Tree |
|---|---:|---:|
| Accuracy | 84.2% | 75.5% |
| Precision | 84.1% | 77.1% |
| Recall | 88.2% | 79.4% |
| F1-score | 86.1% | 78.3% |
| ROC-AUC | 0.904 | 0.751 |

Logistic Regression performed better across all five evaluation metrics and was selected as the best-performing model in this experiment.

## 8. Visualizations
The notebook includes:
- Distribution of the original target variable
- Confusion matrices for both models
- ROC curve comparison

## 9. How to Run the Project
1. Install Python and Jupyter Notebook.
2. Install the required libraries:

   pip install pandas numpy matplotlib seaborn scikit-learn jupyter

3. Keep heart_disease_uci.csv in the same folder as the notebook.
4. Open Heart_Disease_Prediction_Major_Project.ipynb in Jupyter Notebook.
5. Run the notebook cells from top to bottom.

## 10. Conclusion
This project demonstrates a supervised machine learning workflow for binary classification using heart disease data. Logistic Regression achieved 84.2% accuracy, an 86.1% F1-score, and a ROC-AUC of 0.904, outperforming the Decision Tree model on the test set.

The results are intended for educational purposes only and should not be used as a substitute for professional medical diagnosis.

## 11. Project Files
- Heart_Disease_Prediction_Major_Project.ipynb: Complete project notebook
- heart_disease_uci.csv: Dataset
- README.md: Project documentation

## Author
AI/ML Internship Project - Week 4
