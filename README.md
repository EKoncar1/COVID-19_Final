Project Overview	
The goal of this machine learning project was to learn how to create a machine learning model that will predict whether a patient with COVID-19 will be admitted into the ICU based on their patient characteristics. The dataset, "COVID-19 - Clinical Data to Assess Diagnosis," came from the Hospital Sirio-Labanes in Brazil. The dataset contained 385 unique patients, each having 5 specific time frames (0-2. 2-4, 4-6, 6-12, above 12). Patient characteristics included patient demographics, blood levels, vital signs, and previous disease groupings. 


One main problem with the data is that there is an abundance of missing data. For this project, I used neighboring values to fill the missing values(per the author's insight). Another issue with the dataset is that there were multiple duplicate patient characteristics based on value, so those columns were deleted. 


The initial machine learning models used were LogisticRegression, DecisionTreeClassifier, RandomForestClassifier, and KNeighborsClassifier. After the first run, I narrowed the models down to LogisticRegression and RandomForestClassifier. Some of the techniques used to improve model performance were tuning hyperparameters, increasing number of trees and balancing the data. 


The final f1 score of my LogisticRegression was 0.84 (95% CI, 0.76-0.90). 
