# Predict-the-sentiments-of-Amazon-Customer
### In this model I reached to accuracy 98.6% to predict the sentiments of Amazon Customer and I'll show you how I did it.
1. Read data [Reviews.csv](https://www.kaggle.com/snap/amazon-fine-food-reviews)
2. Clean data.
3. Create Logistic regression model on CountVectorizer.
4. Make DummyClassifier model 
5. Logistic regression model on TFIdata
6. The data is imbalanced so we will use RandomOverSampler to handle it.
7. Finally use GridSearchCV with Logistic regression to make a better model.
8. At the end reach to 98.6% accuracy.
