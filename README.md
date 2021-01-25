# ONA-Sentiment-Analysis-and-Topic-Clustering-in-Python
This is an Organizational Network Analysis, Sentiment Analysis, and Topic Clustering project that a team of students completed in Python as part of an NYU course in Fall 2019

The authors of this project are Sammie Kim, Toby Du, and me (Max Needle). As a team, 


we entered the annual machine learning competition run by the Society for Industrial Organizational Psychology (SIOP). For this project, we conducted analyses to predict which half of a test set ("participant_dev.xlsx") would have the highest rate of both retention and job performance while also balancing for unfairness (adverse impact) based on hiring with respect to protected class. We used five-fold cross-validation on multiple machine learning models (Logistic Regression, Naive Bayes, Decision Tree, Random Forest, Support Vector machine, Neural Network, KNN, and XGBoost) and identified the optimal models based on AUC.

# About the supporting data
The supporting data (found in the "train.xlsx" and "participant_dev.xlsx" datasets in the "datasets" folder) contain the screening test results for several thousand job candidates who applied to entry-level roles at Walmart. The "train.xlsx" dataset also includes the outcome measures (retained or not, high performance or not, protected class or not) necessary to train the models.

# Instructions to Run
To run the "Machine Learning Greedy Search.ipynb" script, you will need to install and load several Python packages (pandas, numpy, seaborn, matplotlib, xgboost, scipy, and sklearn). For your ease, the actual greedy search computations (evaluating each model) is commented out and the optimal models can be found in the "models" folder. If you would like to run all of the models in the "cross_validated_models" function, remove the comments from the cells where this function is used. However, this function takes very long to run, so I recommend leaving your computer overnight when you run these cells.
