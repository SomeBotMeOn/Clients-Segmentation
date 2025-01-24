<center><strong><h1>Выбор моделей для ансамблирования</h1></strong></center>

---

### По итогам обучения моделей, были получены следующие результаты:

#### CatBoost - 0.9936
#### XGBoost -  0.6613
#### LightGBM - 0.6613
#### LogisticRegression - 0.9909
#### RandomForest - 0.9939
#### DecisionTree - 0.9888
#### KNN - 0.9882
#### SVM - 0.9774
#### GradientBoosting - 0.9937 
#### AdaBoost - 0.9680
#### NaiveBayes - 0.9823
#### LinearDiscriminantAnalysis - 0.9886
#### ExtraTreesClassifier - 0.9936

Выберем в качестве базовых моделей для ансамблирования модели, у которых точность выше 0.990:
- CatBoost
- LogisticRegression
- RandomForest
- ExtraTreesClassifier
- GradientBoosting