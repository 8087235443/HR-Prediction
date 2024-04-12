# Content
#1. Basic Analysis of data
#2. Data Cleaning 
#3. All models on data
#4. Imbalance treatment Random -SMOTE
#5. Models after class imbalance treatment
#6. Cleaning of Test data
#7. POrediction on Test data
#8 Final Conversion of prediction in dataframe to csv format

The data is belonging to HR domain.We have to predict Employee appraisal  by predictive modelling.
Approach: Data set is with 2 parts train and test separately.First analyze train dataset and taken some meaningful insights like data ditribution, any missing values, data type conversion,significant attributes, correlation.
The target attribute is categorical hence implemented some classification algorithm but it has been observed that after doing all the essntial processing and modelling performance of the model is not satifactory.
Because the data is with class imbalance problem due to which model is not giving good performance.
After handling the class imbalance problem model working good on both the classes.
For all the above model Accuracy is good but only accuracy is not the parameter which decide the model performance hence F1-Score, Precision ,Recall also checked .
Event hough the Accuracy is good but all the other parameter shows poor result.
For XGBOOST accuracy is high ie 94% but class-1 is poorly predicted.
Before the class imbalance treatment XGBOOST is working with high accuracy after treating the class imbalance problem 
Random Forest model is giving highest accuracy with good precision,recall and F1-Score.
After treating class imbalance problem TN are still high so model performance can be visualize by PRC-Curve.
