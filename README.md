# Dry_Bean_Project
Comparison of Machine Learning Models on Dry Bean Classification
**_Project Overview**_
The Dry Bean Dataset Machine Learning Project aims to classify different types of dry beans based on various morphological features. The dataset contains 13,611 instances of 7 registered categories of dry beans consisting of 16 features. This project involves exploratory data analysis, data preprocessing, model training, and model evaluation to achieve accurate classification of the dry bean types. Feature importance using the permutation importance method was carried out on the models to identify the featues of the dataset that significantly impacted the performance of each model. The models developed are Random Forest (RF), eXtreme Gradient Boosting (XGB), Support Vector Classifier (SVC) and Multi-Layer Perceptron (MLP) using Keras Sequential Framework.
**_Dataset Description**_
The dataset used in this project is the Dry Bean Dataset, which can be downloaded from the UCI Machine Learning Repository. Link is https://archive.ics.uci.edu/dataset/602/dry+bean+dataset
**_Project Notebooks**_
The notebooks directory is Google colab for detailed data exploration, preprocessing, and model training and evaluation. You can run these notebooks to get an in-depth understanding of each step in the project pipeline.
**_Methodology**_
GridSearchCV was used for the hyperparameter tuning of RF, XGB and SVC models. The addition of Dropout layer, Early stopping, L2 regularizer and increasing the epoch to 100 was used to fine tune the MLP model. The performance metrics used for the assessment of the models were accuracy, precision, recall, F1 score and confusion matrix. The permutation importance function from sklearn was used to evaluate the feature importance of the models.
**_Results**_
All the models achieved good results. The SVC model was the best 93.7% accuracy. The accuracy of MLP, XGB and RF models were 93.2%, 93.1% and 92.8% respectively. The important features contributing to models’ performance are roundness, compactness, shape_factor_4 and shape_factor_1.
