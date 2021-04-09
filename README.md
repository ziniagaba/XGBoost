# XGBoost
Machine Learning Hackathon -
Supervised learning classification problem of predicting the overall experience of Shinkansen ( Bullet Train) of Japan using XGBoost algorithm.

Approach
1. Missing value imputation with multivariate imputation by chained equations (MICE) iterative imputer
2. One hot encoding for categorical variables
3. Splitting the data into train and test
4. Standard Scaling(Optional)
5. Feature engineering.
6. Multiple algorithms- Bagging, Gradient Boosting and XGBoosting
7. Hyperparameter Tuning
8. Parameters - scale_pos_weight=1, learning_rate=0.1, colsample_bytree = 0.8,subsample = 1,objective='binary:logistic', n_estimators=3000, reg_alpha = 0.3,max_depth=12, gamma=5)
9. Train Accuracy - 97.48 % , Test accuracy - 95.82 %, Hackathon data accuracy - 95.53 %

