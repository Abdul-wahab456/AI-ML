# Titanic Survival Prediction

## Project Description
This project predicts the survival of passengers aboard the Titanic using machine learning techniques. The dataset is sourced from the Kaggle Titanic competition, which is a beginner-friendly challenge in predictive analytics. The goal is to predict whether a passenger survived or not based on features such as age, gender, ticket class, and more.

## Key Features:
1. **Dataset**: Data is taken from Kaggle's Titanic competition, including training (`train.csv`) and test (`test.csv`) datasets.
2. **Objective**: Create a machine learning model to predict passenger survival (binary classification: 1 for survived, 0 for deceased).
3. **Pipeline**:
   - Data preprocessing, including handling missing values, scaling numerical features, and encoding categorical variables.
   - Model training using the Random Forest classifier.
   - Hyperparameter tuning with GridSearchCV for improved accuracy.
4. **Evaluation**: Performance was evaluated using accuracy metrics on the validation set and submission to Kaggle for leaderboard scoring.

## Workflow:
1. **Data Analysis and Visualization**:
   - Explored dataset features and relationships using pandas, Matplotlib, and Seaborn.
   - Visualized key attributes like survival rates by gender, age, and ticket class.
2. **Preprocessing**:
   - Addressed missing values using `SimpleImputer`.
   - Encoded categorical variables with `OneHotEncoder`.
   - Standardized numerical features using `StandardScaler`.
3. **Model Development**:
   - Built pipelines to streamline data preparation and model training.
   - Trained a Random Forest model and optimized hyperparameters using `GridSearchCV`.
4. **Submission**:
   - Generated a CSV file containing `PassengerId` and `Survived` columns for submission to the Kaggle competition.

## Technologies Used:
- **Programming Language**: Python
- **Libraries**: NumPy, pandas, seaborn, matplotlib, scikit-learn
