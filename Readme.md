# Corporate Bankruptcy Prediction using Machine Learning

## Project Overview
This project aims to predict corporate bankruptcy using financial ratios. The dataset contains financial information from over 6,800 companies. The main challenge addressed in this project is the severe **Class Imbalance** (only ~3% of companies are bankrupt).

## Key Features
* **Data Preprocessing:** Handled missing values and applied Standard Scaling.
* **Imbalance Handling:** Utilized **SMOTE** (Synthetic Minority Over-sampling Technique) on the training set to balance the classes.
* **Model Comparison:** Evaluated three models:
    * **Logistic Regression:** Best Recall (~80%) for risk detection.
    * **Random Forest:** Best Accuracy (~96%) for overall stability.
    * **K-Nearest Neighbors (KNN)**.

## Results
The analysis shows a trade-off between Accuracy and Recall. While Random Forest provides high accuracy, Logistic Regression is preferred for risk management due to its superior ability to detect actual bankruptcy cases (False Negatives minimization).
