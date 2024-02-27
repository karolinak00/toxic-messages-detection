# Datasets
In this project, following datasets were used:
- https://www.kaggle.com/datasets/ashwiniyer176/toxic-tweets-dataset?select=FinalBalancedDataset.csv
- https://www.kaggle.com/datasets/akashsuper2000/toxic-comment-classification?select=validation.csv

# About classifiers
In this project 7 classifiers were implemented (Decision Tree Classifier, Random Forest Classifier, SGD Classifier, Multinomial Naive Bayes Classifier, Support Vector Machine Classifier, k-Neighbors Classifier and XGBoost Classifier). Next, three most promising ones were chosen and connected in one Voting Classifier. 

# Accuracy
Accuracy on the test data is about 76%.

# How to start?
To run this code, open Jupyter Notebook. If you are using desktop application (for example Anaconda), download *best_classifier.pkl* and *tokenizer.pkl* files. If you are using Jupyter Notebook in cloud (for example Google Colab), upload these files to your workspace. Then, change the paths in *Constants* section.

Run code in following sections:
- Imports
- Constants
- Mounting with Google Drive
- Loading classifier
- Loading tokenizer
- Predicting.

To predict if message is toxic or not, change the parameter in last cell, i.e. replace text: *"I love you <3"* to any message you want in cell  with code: *predict("I love you <3")*

Have fun with experimenting :)
