# Yahoo-Troll-Question-Detection

Problem Statement
* As a last-ditch attempt to give Yahoo Answers some legitimacy in the era of Quora and Reddit, Yahoo's CEO Merissa Meyer has tasked us with creating a machine learning model to detect spam and troll questions so that they can be removed.

This project focuses on binary classification by developing a machine learning model to determine whether a given statement is a troll or not. The dataset utilized for training and testing is sourced from Kaggle, specifically tailored for Yahoo troll question detection. To enhance the data processing pipeline, the Natural Language Toolkit (nltk) and pickle were employed in combination with various machine learning algorithms. The end-to-end solution includes data preprocessing, feature engineering, and the implementation of classification models to accurately detect troll statements, contributing to a more trustworthy and reliable content environment.

Key Steps and Accomplishments:

1. Data Preprocessing:
  * Conducted comprehensive data preprocessing on the hand-labeled dataset to ensure it was ready for modeling.
  * Separately preprocessed both the training and test datasets.
  * Employed techniques to handle text data, such as tokenization, removal of special characters, and lowercasing.
  * Pickled the preprocessed data to preserve the preprocessing steps and facilitate future use.

2.Feature Engineering:
  * Utilized TF-IDF and CountVectorizer for effective word vectorization.
  * Limited the features to 4000 unique words to reduce dimensionality and improve computational efficiency.

3.Model Selection and Hyperparameter Tuning:
  * Explored multiple machine learning models to find the best fit for the problem.
  * Performed hyperparameter tuning to optimize the model's performance.
  * Compared and evaluated the models based on accuracy metrics.

4.Result Improvement:
  * Initially faced challenges with accuracy despite extensive preprocessing.
  * Conducted experiments without preprocessing and observed improved results.
  * Implemented a logistic regression model with the removal of URLs, which further improved performance.

5.Model Evaluation:
  * Assessed the performance of various models on the test dataset to gauge their effectiveness.
  * Analyzed and documented the results of each model iteration.


Team Name : Gryffindor

Team Members : 
    * Akanksha Shukla - https://github.com/imshukla12
    * Aakanksha Rani - https://github.com/Srivastava-Rani-Aakanksha

