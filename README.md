# Titanic: Machine Learning from Disaster

This is the log of my attempts in kaggle's competition on predicting survivors aboard the titanic, which is avaiable [here](https://www.kaggle.com/c/titanic).

That's the first time I'm trying one of these, so don't mind a few mistakes I might make :).

## Objective

The objective of this competition is to predict if a tripulant of the titanic survived the disaster based of his informations (name, gender, age, how much was paid for fare, cabin, and others).

The score of a classifier is given by its accuracy: (tp + tn) / #observations .

## Results

The best results I've achieved so far were 77.99%, using a RandomForestClassifier on features ["Sex","Fare","Pclass","Embarked"].

More details can be seen in the notebook.
