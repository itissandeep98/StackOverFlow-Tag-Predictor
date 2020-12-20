# StackOverFlow Tag Predictor - Machine Learning Project

## Authors
- Navya Aggarwal | 2018349
- Nitin Gupta | 2018251
- Sandeep Kumar Singh | 2018363

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

## How to run the project

## Links
- https://www.researchgate.net/publication/338370635_TagStack_Automated_System_for_Predicting_Tags_in_StackOverflow 
- https://github.com/gauravtheP/Stackoverflow-Tag-Prediction
- http://cs229.stanford.edu/proj2013/SchusterZhuCheng-PredictingTagsforStackOverflowQuestions.pdf
- https://ieeexplore.ieee.org/document/8389059
- https://colab.research.google.com/drive/1V9m8QFX2mxcFqkVuF6XFQQd7dD2atOx-
- https://github.com/saicharanarishanapally/stack-overflow-tag-predictor/blob/master/SO%20Tag_Predictor.ipynb
