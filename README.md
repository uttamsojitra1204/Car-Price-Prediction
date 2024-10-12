# Car-Price-Prediction

=> This project focuses on predicting the selling price of used cars using machine learning models. It leverages three algorithms: Linear Regression, Lasso Regression, and XGBoost. The dataset contains important features such as the car's manufacturing year, kilometers driven, fuel type, ownership history, seller type, and transmission.

1. Data Preprocessing:
- Cleaned the dataset, ensuring no missing values.
- Encoded categorical variables like fuel type, seller type, and owner into numerical formats for model compatibility.
- Dropped irrelevant columns (such as car name) to focus on essential features for price prediction.

2. Model Implementation:
- Trained three different models: Linear Regression, Lasso Regression, and XGBoost.
- Evaluated the models based on R² scores, comparing their ability to predict both the training and test datasets.

3.Model Evaluation:
Linear Regression and Lasso Regression performed similarly with moderate accuracy.
XGBoost delivered the best performance, with significantly higher R² scores on the training set, though it was slightly overfitting compared to other models.

4. Visualization:
- Created scatter plots comparing actual prices with predicted prices to visually assess model performance.

=> Conclusion
- This project aimed to predict used car prices using machine learning models. Linear Regression, Lasso Regression, and XGBoost were implemented. While Linear and Lasso Regression showed moderate accuracy, XGBoost performed the best, though it slightly overfitted on training data. The project highlighted the effectiveness of ensemble models like XGBoost for accurate price prediction and the potential for further model tuning to improve generalization.
