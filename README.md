# Credit_Risk_Analysis


<h1>Project Overview</h1>
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, I employed different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.
<h1>Resources</h1>

- Data Sources: credit_risk_resampling_starter_code.ipynb, credit_risk_ensemble_starter_code.ipynb, LoanStats_2019Q1.csv

- Software: Sklearn

- Dependencies: Pandas, Numpy, Pathlab, Collections, Imblearn
<body>
<h1>Summary</h1>

<h3> Use Resampling Models to Predict Credit Risk</h3>
<p>Using your knowledge of the imbalanced-learn and scikit-learn libraries, you’ll evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, you’ll use the oversampling RandomOverSampler and SMOTE algorithms, and then you’ll use the undersampling ClusterCentroids algorithm. Using these algorithms, you’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.</p>

Split the Data into Training and Testing:
  
<img src="https://github.com/kellynichols99/Credit_Risk_Analysis/blob/main/Resources/Split%20the%20Data%20into%20Training%20and%20Testing%20-%20D1.png">

Naive Random Oversampling:
  
<img src="https://github.com/kellynichols99/Credit_Risk_Analysis/blob/main/Resources/Naive%20Random%20Oversampling%20-D1.png">
  
<h3>Use the SMOTEENN algorithm to Predict Credit Risk</h3>
  
<p>Using your knowledge of the imbalanced-learn and scikit-learn libraries, you’ll use a combinatorial approach of over- and undersampling with the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms from Deliverable 1. Using the SMOTEENN algorithm, you’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.</p>

SMOTE Oversampling:
  
<img src="https://github.com/kellynichols99/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20Oversampling%20-%20D1.png">
  

<h3>Use Ensemble Classifiers to Predict Credit Risk</h3>
  
<p>Using your knowledge of the imblearn.ensemble library, you’ll train and compare two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model. Using both algorithms, you’ll resample the dataset, view the count of the target classes, train the ensemble classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.</p>

Split the Data into Training and Testing:

<img src="https://github.com/kellynichols99/Credit_Risk_Analysis/blob/main/Resources/Split%20the%20Data%20into%20Training%20and%20Testing-D2.png">
  
Balanced Random Forest Classifier:
  
<img src="https://github.com/kellynichols99/Credit_Risk_Analysis/blob/main/Resources/Balanced%20Random%20Forest%20Classifier-D2.png">
  
<h1>Challange Summary</h1>
After using machine learning models and found that the accuravy scores increaed at each step. We Started at 66% and ended at 93% accuracy. We can see that when we worked with the Easy Ensemble Classifier we saw a large jump in the model accuracy, with the next highest score being with the balanced accuracy score at 78%. 


