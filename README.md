 # Regression_Capstone
This space contains regression model for prediction of Ted talk reviews submitted as a part of Almabetter flexi program.
Target Variable :

views: Contains Count of views of every talk
Approach taken :
The task was divided into 2 main parts :

Statistical Analysis over the dataset to discover relationships between each feature and the target variable . So that this relationship information can be used by the management in making better Business decisions
Creating a Machine Learning Pipeline , that can take in the data of any new video and predict how many views it will generate on a daily basis .It was required to kepp this pipeline modular , such that it can be retrained often when new data is collected
Project Work flow
Importing Libraries

Loading the dataset

Data Cleaning

EDA on features

Feature selection

Fitting the regression models

HyperParameter Tuning

Evaluation Metrices of the model

Final selection of the model

# Conclusion

Technical Details for ML :
_ Started with loading the data so far I have done EDA ,feature engineering , data cleaning, target encoding and one hot encoding of categorical columns, feature selection and then model building and hyperparameter tunning.

 Results for models seems fair enough and I have been able to correctly predict views 80% of the time. ### After hyper parameter tuning, I have prevented overfitting and decreased errors by reducing learning rate. ### Given that only have 20% errors, my models have performed very well on unseen data due to various factors like feature selection,correct model selection and hyperparameter tunning etc.

I have used four models for the views prediction started inclusing Linear regression, Ramdom forest, XtremeGradientBoost, Random forest and Cat boost.

Out of my 4 models including the hyperparameter also I have seen that Catboost model which is basically meant for catagorical data( catagorical boost) have shown the good Training accuracy of 99.99% and testing accuracy of 81% keeping in mind the score of mean absolute errors and RMSE, since I have use the MAE for the measurement of the good model and not the RMSE because RMSE can heavily be impacted by outlier but MAE is not impacted by outliers also inn term of MAE Random forest and XGBoost has good scores.



I used many Algorithms ( Random Forest , XGBoost and CatBoost ) I have used RandomSearchCV for HyperParameter Tuning Comparing both R2 Score , we can see that Random Forest and XGBoost model performs the best and also catboost.

Technical Insights from exploring the Data :
● For the ML Pipeline , the XGBoost Model performed the best ● For the NLP Pipeline , the Random Forest Model performed the Best ● Feature Engineering and Feature Extraction helped in increasing the model performance

# Conclusions : Insights from exploring the Data :
● Topics like Technology , Science , Education , Biology attract the attention of viewers more than other topics . ● Entrepreneurs and Activists are the most engaging speakers

# Python Libraries used
Datawrangling :

Numpy
Pandas
For Graphing :

Matplotib
Seaborn
Machine learning :

Scikit-Learn
SK-Opt
XGBoost
CatBoost
