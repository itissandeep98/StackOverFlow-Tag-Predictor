# StackOverFlow Tag Predictor - Machine Learning Project

## Authors
- [Navya Aggarwal](https://github.com/iamnavya-agg) | 2018349
- [Nitin Gupta](https://github.com/nitin18251) | 2018251
- [Sandeep Kumar Singh](https://github.com/itissandeep98) | 2018363

## Introduction

**Keywords** - Stack Overflow, tags, prediction, SVM, Naive Bayes

Stack Overflow is the largest, most trusted online community for developers, students, and other educationists throughout the world. It is an educational resource available to everybody to clarify doubts, ask questions, answer questions, vote questions, and answers up or down and similarly, post questions and answers like Wiki or Quora.


For each question on StackOverflow, tags are used to relate different questions to categories. Tags are assigned to questions by users only. These tags are very important as they help associating questions to categories. Therefore, a question needs to be given the most approprieate tags.


In this project we aim to develop a predictor that predicts tags for questions. In order to achieve the same, we use a dataset of questions and tags and learn machine learning models like Naive Bayes, Logistic Regression, Decision Trees and SVM to predict tags for new questions.

## Dataset Overview

Train.csv contains 4 columns: Id, Title, Body, Tags
Size of Train.csv - 6.75GB
Number of rows in Train.csv = 6034195

For the purpose of this project we have used a subset of the dataset due to computational limitations.

The dataset is preprocessed using various Natural Language Processing like lemmetization, tokenization, vectorization, removing stop words and many more such techniques. The final datasets are stored and used to train the machine learning models. Further, using these trained models we predict the tags of questions and report accuracy, macro-F1 score and micro-F1 score.

## Prerequisites
You need to have installed following softwares and libraries in your machine before running this project:
1. python 3
2. pandas
3. numpy
4. nltk
5. seaborn
6. matplotliib
7. wordcloud
8. sklearn
9. joblib
10. pickle

## Directory Structure

### model
This contains all the weights of all models which were trained on all specified datset sizes

### code

1. [EDA.ipynb](code/EDA.ipynb): It contains all the code needed to perform the exploratory data analysis on the dataset

2. [datasetGeneration.ipynb](code/datasetGeneration.ipynb): It contains the code for creating the dataset for both preprocessing and vectorizing data and storing them in pickle files

3. [SVM.ipynb](code/SVM.ipynb): It contains the code for running the Support vector machine model on the dataset both with the specified parameter and also using grid search.

4. [Logistic.ipynb](code/Logistic.ipynb): It contains the code for running the Logistic regression model on the dataset both with the specified parameter and also using grid search.

5. [DecisionTree.ipynb](code/DecisionTree.ipynb): It contains the code for running the Decision Tree model on the dataset both with the specified parameter and also using grid search.

6. [Naive Bayes.ipynb](code/Naive%20Bayes.ipynb): It contains the code for running the Bernoulli Naive Bayes model on the dataset both with the specified parameter and also using grid search.

7. [Analysis.ipynb](code/Analysis.ipynb): It contains the code for analysing the various models with various parameter and how they perform on changing various hyperparameters.

8. [MLproject.ipynb](code/MLproject.ipynb)
