# Pass/Fail Classification

### Problem statement: -
-	Independent variables that are collected form sensors as signals. In these variables, there are some of noisy information, some of irrelevant information and some useful information. as these are signal that are taken from sensors. 
-	If we consider each type of signal as a feature, then feature selection may be applied to identify the most relevant signals. The Process Engineers may then use these signals to determine key factors contributing to yield excursions downstream in the process. This will enable an increase in process throughput, decreased time to learning and reduce the per unit production costs. These signals can be used as features to predict the yield type. And by analysing and trying out different combinations of features, essential signals that are impacting the yield type can be identified.
-	Data contains 592 variables that includes sensors, output and time.


### Feature Engineering : -
- Time columns make it as index.
- NAN values replaced using KNN imputer
- Standardization method used for converting all variables unit into one.
- PCA used to tackle with outliers and diamensionality reduction technique.
- Imbalanced used to make data balanced.

### Languages Used: -
- Python 3.9.0

### Tools and Resources: - 
Tools: Jupyter Notebook

Packages: Pandas, NumPy, sklearn, Matplotlib, scipy, seaborn, imblearn and counter.


### EDA
- This shows how data is im- balanced.
![DOON1](https://user-images.githubusercontent.com/82714026/146671806-ec2ea40a-8c23-4987-b7bb-9b78ec949ae9.png)

-Histplot shows hows variable 3 this distributed along the data.
![Doon2](https://user-images.githubusercontent.com/82714026/146671808-fb9383d6-89e7-4693-96f0-78b20afce867.png)

### Validation method: -
- Stratified KFOLD cross validation method used.

### Model Building
- Lazy predict used to find out best model.
- Random forest

### Hyperparameter Tuning: -
- Hyperparameters were tuned using grid search.
- Optimal model found out using tuning.

### Metric of Evaluation: –
- ROC AUC score
- Precision
- Recall
- F1-Score
- Confusion matrix

### Conclusion & Improvisation: -
- Finally, Classes are predicted accurately
- we can tune model and reduce chances of overfitting.
- we can check with  another models.
