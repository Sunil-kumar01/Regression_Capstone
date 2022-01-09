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
We used many Algorithms ( Random Forest , XGBoost and CatBoost ) We used RandomSearchCV for HyperParameter Tuning Comparing both R2 Score , we can see that Random Forrest and XGBoost model performs the best

Technical Insights from exploring the Data :
● For the ML Pipeline , the XGBoost Model performed the best ● For the NLP Pipeline , the Random Forest Model performed the Best ● Feature Engineering and Feature Extraction helped in increasing the model performance

Conclusions : Insights from exploring the Data :
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
