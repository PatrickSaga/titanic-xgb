# Titanic-xgb
Tutorial Ipython Notebook for the Kaggle competition [Titanic_ Machine learning from Disaster](https://www.kaggle.com/c/titanic). 
The aim of this repository is to provide an example tutorial of a machine learning workflow from a beginner perspective, and finally submit a competitive result. 
The current version of the code achieves a public score of 0.81818 based on [accuracy](https://en.wikipedia.org/wiki/Accuracy_and_precision#In_binary_classification) metric, leading to a Top 3% result in the leaderboard. 

## Table of contents
1. Exploratory data analysis (EDA)
2. Cleaning of missing data
3. Feature engineering
4. Preparation of data
5. Parameter optimization of the XGB model
6. Final prediction and submit
7. Ad-hoc rules (optional)

### Dependencies
- [IPython](http://ipython.org/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [SciKit-Learn](https://scikit-learn.org/stable/)
- [Seaborn](https://seaborn.pydata.org/#)
- [Matplotlib](https://matplotlib.org/)
- [XGBoost](https://xgboost.readthedocs.io/en/latest/#)

## Kaggle competition description
From the competition [homepage](https://www.kaggle.com/c/titanic):
> The sinking of the Titanic is one of the most infamous shipwrecks in history.
>On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.
>While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.
>In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc). 

## Contributors
Patrick Sánchez Galea ([Kaggle profile](https://www.kaggle.com/saga21))