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
5.  OrdinalEncoder (for encoding ordinal categorical column)<br>
6.  OneHotEncoder (for encoding nominal categorical column)
7.  StandardScaler (for scaling)<br>
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
32. datetime
</details>
<details>
    <summary>EDA:</summary>
1. Null value Analysis<br>
2. Outlier Analysis<br>
3. Plotting data to get insight
 </details> 
 <details>
    <summary>Feature Engineering:</summary>
1. Feature Selection (correlation and IV analysis)<br>
 </details> 
 
<details>
    <summary>Preprocessing:</summary>
  1. Scaling the dataset for some specific model linke knn<br>
  2. Ordinal encoding and One hot encoding<br>
  3. Using oversampling technique as data is imbalanced
 </details>
<details>
    <summary>Model Building:</summary>
  1. Logistic regression <br>
  2. Random forest classifier<br>
  3. KNN classifier<br>
  4. Voting classifier<br>
  5. Bagging classifier<br>
  6. SVM<br>
  7. Gradient boosting<br>
  8. Stacking
 </details>
  <details>
    <summary>Hyper parameter tuning:</summary>
  1. Logistic regression -Polynomial regression (with degree 2, 3, 4), l1,l2, and elasticnet with different values using Randomized and Gridsearch CV <br>
  2. Random forest regression - different hyper parameters using randomized search CV and grid search CV
  3. KNN - testing at different n_neighbours
  4. SVM - testing at different kernel like rbf and polynomial of different degrees
 </details>
  <details>
    <summary>Conclusion:</summary>
  1. Random forest  gives highest accuracy (89%) and highest precision (60%) for minority class<br>
  2. Logistic regression gives highest recall (85%) for minority class<br>
 </details>
 
