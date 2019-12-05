# Sparkify project - DSND Capstone Project

### Table of Contents

1. [Installation](#installation)
2. [Project details](#details)
3. [Files Description](#files)
4. [Result](#Result)

## Installation <a name="installation"></a>

This project uses the following software and Python libraries:

1. Python
2. Spark
3. Pyspark (Both SQL and ML)
4. pandas
5. Matplotlib
6. Seaborn


## Project details <a name="details"></a>

This is udacity's capstone project, using **Apache Spark** to analyze user behavior data from music app Sparkify.
The dataset contains user behavior log. 
Churn of a user can be identified through the **Cancellation** of the account

## Files Description<a name="files"></a>

**Sprakify_DSND.ipynb** Main file of the project, it demonstrates the process of using pyspark to explore the data and build the model.

## Result
- Logistic Regression can predict the likelyhood, if a user will churn or not, with an accuracy of: 0.8115 , and F1 score of:0.7949
- The top 5 features that help to determine the likelyhood are:
    - Number of distinct artists a user listens to
    - Overall time spent listening on the app
    - Number of times the user has voted 'positively'
    - The overall number of friends invited to share the same app
    - The number of songs added to a playlist


The blog can be read[here]

