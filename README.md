# Credit-Risk-Prediction-Classification
This project involves credit risk prediction using machine learning techniques.The dataset consists of information about loan applicants, including demographic factors, financial details, and loan history.Three primary ML algorithms Logistic Regression, Decision Tree, and Random Forest implemented in predicting loan approval status.


Introduction:
This project aims to predict credit risk using machine learning models. The objective is to develop models that can effectively assess the risk associated with granting loans based on various applicant features.

Setup:
The environment for this project requires Python along with libraries such as pandas, NumPy, scikit-learn, and others. Installation instructions for these libraries can be found in the project's README file.

Dataset:
The dataset used in this project contains information about loan applicants, including features such as gender, marital status, education, income, loan amount, credit history, etc. The target variable is "Loan_Status," indicating whether a loan was approved or not. The dataset consists of 981 entries and 13 columns.

Data Preprocessing:
Missing values in the dataset were handled by filling them with the mean value for numerical features and dropping rows with missing categorical values. Categorical variables were encoded using label encoding.

Model Training and Evaluation:
Three machine learning models were trained and evaluated for credit risk prediction:

Logistic Regression
Decision Tree
Random Forest
Performance metrics such as accuracy, precision, recall, and F1-score were calculated to evaluate the models' performance.
Feature Scaling and Hyperparameter Tuning:
Feature scaling using StandardScaler was applied to improve model performance. Hyperparameter tuning for Decision Tree and Random Forest models was performed using GridSearchCV to optimize their performance.

Ensemble Methods:
AdaBoost and Gradient Boosting ensemble methods were employed to further enhance predictive performance.

Cross-validation:
Cross-validation techniques were implemented to ensure robust evaluation of the models' performance and detect any overfitting issues.

Conclusion:
Random Forest exhibited the highest mean cross-validation accuracy among the evaluated models, followed closely by Decision Tree. Ensemble methods like Random Forest, AdaBoost, and Gradient Boosting outperformed Logistic Regression, highlighting the importance of leveraging ensemble techniques for credit risk prediction. Further fine-tuning and validation of the best-performing model (Random Forest) are recommended before deployment.
