# Census-Income-and-population
[Adult Data Set](https://archive.ics.uci.edu/ml/datasets/adult)

<img src="https://th.bing.com/th/id/R.552dedf6558abb339fee0e3761352307?rik=Y7fvnO3L7IE0sg&riu=http%3a%2f%2ffreedomandprosperity.org%2fwp-content%2fuploads%2f2015%2f09%2fCensus-Income-600x390.jpg&ehk=qXkQhqDZdZANcrKBulbhzpVdkcCBN3zUsG%2bq4VGPDcg%3d&risl=&pid=ImgRaw&r=0" />

## Description:
Census Income prediction is part of Supervised learning (binary classification) where target column (salary) contains the values whether someone has annual income $>50K or not. 

In this project I have done EDA, feature selection and applied different machine learning technique to get optimum results which are mentioned in process flowchart.

## Process flowchart:

<details>
    <summary>Imported libraries:</summary>
  
### For EDA and preprocessing
  
1.  numpy (for mathematical calculation)<br>
2.  pandas (for data importing and manipulation in the form of DataFrame)<br>
3.  matplotib.pyplot (for data visualization)<br>
4.  seaborn (for data visualization)<br>
5.  OrdinalEncoder (for encoding categorical column)<br>
6.  StandardScaler (for scaling)<br>
7.  sklearn.pipeline.make_pipeline (to pipeline the model building part in less time)<br>
8.  PolynomialFeatures (for polynomial logistic regression)<br>
9.  ColumnTransformer (to pipeline the preprocessing part)<br>
10. make_pipeline (to pipeline the model building part in less time)<br>
11. RandomOverSampler (to handle imbalanced dataset)
12. train_test_split (for splitting dataset into training and testing)<br>
13. cross_val_score (for cross validation)
  
### For model building
  
14. LogisticRegression<br>
15. KNeighborsClassifier<br>
16. RandomForestClassifier<br> 
17. VotingClassifier<br>
18. BaggingClassifier<br>
19. StackingClassifier<br>
20. GradientBoostingClassifier<br>
21. SVC
  
### For hyperparameter tuning
  
22. RandomizedSearchCV<br>
23. GridSearchCV<br>
  
## For accuracy measurement
  
24. confusion_matrix<br>
25. plot_confusion_matrix<br>
26. classification_report
 
## For time series analysis
27. plot_acf
28. plot_pacf
29. ARIMA
30. SARIMAX
31. auto_arima
</details>
