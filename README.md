# Starbuck Capstone Challenge
Udacity MLND capstone project

## Overview
Starbucks Capstone Challege addresses a classification challenge to predict the influence of customers demographics on the acceptance of Starbucks mobile app reward offers. Dataset that is in JSON format, is aquired from Starbucks reward program. Dataset is devided in to three subset for offer details, customer details, and events.

Dataset then goes under a curation process to create training and testing dataset. These datasets are used to train couple of models to predict if an offer will be accepted for a given customer details and offer details. The prediction result of both models are then compared and checked.

## Project Contents
- data: Directory containing dataset
  - portfolio.json
  - profile.json
  - transcript.json
- Project_Proposal.pdf
- Starbucks_Caspstone_notebook.ipynb: Implementation of reading, cleaning, and preparing test data; training and testing model; benchmarking result
- Project_Report.pdf: Process details that was taken for this challenge
- pic1.png: Instruction image used in notebook
- pic2.png: Instruction image used in notebook
- README.md: Project readme file

## Software and Installation
This project is dependent on below libraries:
- Python 3.+
- Pandas
- Numpy
- Matplotlib
- scikit-learn

## Note
This project details is published on [Medium](https://medium.com/@dipan.cs/starbucks-capstone-challenge-fe039e1ae782). A special thanks to Starbucks and Udacity for providing the dataset for this project. 

## Reference
- [Decision Tree Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)
- [SVC](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)
- [Unpack Dictionary from Pandas Column](https://stackoverflow.com/questions/50512188/unpack-dictionary-from-pandas-column)
- [Why One-Hot Encode Data in Machine Learning?](https://machinelearningmastery.com/why-one-hot-encode-data-in-machine-learning/)
- [Report Example](https://github.com/udacity/machine-learning/blob/master/projects/capstone/report-example-1.pdf)
- [Pandas Dataframe Merge](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.merge.html)
