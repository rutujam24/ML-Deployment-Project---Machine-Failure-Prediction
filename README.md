# ML-Deploment-Project---Machine-Failure-Prediction
End-to-end Machine Failure Prediction project using classification models (Logistic Regression, Decision Tree, Random Forest) with deployment on Flak & Streamlit.

On flask:- 
https://obscure-sniffle-pjvw9wj5xr7qfr55r-5000.app.github.dev/

On streamlit:-
https://obscure-sniffle-pjvw9wj5xr7qfr55r-5000.app.github.dev/

This project focuses on predicting machine failure using sensor readings and operational parameters to enable preventive maintenance and reduce downtime and maintenance costs. The dataset was sourced from Kaggle and includes features such as air temperature, process temperature, rotational speed, torque, tool wear, and failure indicators.

The workflow includes data cleaning, exploratory data analysis, feature engineering (creating temperature difference), encoding the categorical “Type” feature, and scaling numerical features. After preprocessing, classification models were built using Logistic Regression , Decision Tree and Random Forest.

Both models were evaluated using accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC to compare performance. Random Forest achieved better predictive performance and helped identify key factors influencing machine failure, such as torque, tool wear, and temperature differences.

This project demonstrates how machine learning can be used for predictive maintenance to improve equipment reliability and optimize industrial operations.
