## I. Overview

- Student name: Isiah Cruz
- Student pace: Online Part-Time Data Science
- Flatiron project review date: December 2020
- Instructor name: Lindsey Berlin
- Module: Capstone/Final Project
- Dataset: https://data.world/brianray/enron-email-dataset

## II. Problem Statement & Project

- Problem Statement: Categorize and label the Enron email dataset better than humans can.
- Project: Classifying emails based on their content to automate manual processes and to increase the accuracy with which emails are labeled.

## III. Repository Contents
- 1) Importing
- 2) Data Preparation (Examination, Outliers)
- 3) Exploratory Data Analysis (Tokenization & Stopwords, Frequency Distribution, Wordcloud, Labels, Word Count)
- 4) Modeling (Train-Test-Split, TF-IDF Vectorizer, Class Imbalance, Multinomial Naive Bayes, Gradient Boosting, Adaboost, Logistic Regression)
- 5) Conclusion (Evaluation, Recommendations & Future Work)

## IV. Conclusion
- **Big Takeaway:**
Throughout this project, I was able to perform a number of operations that I was able to carry over to a similar dataset for my company NewtonX. For one, the multi-class classification nature of each, means that I was able to select 4 categories from the Enron dataset to mirror the 4 labels present in the NewtonX dataset. In addition, both projects presented outliers when it came to the word length of certain emails that were exorbitantly long (i.e. 37K+ words). Therefore, I was able to use the IQR/outlier-removal tool that I built in the Enron project and directly apply it to the NewtonX one. Finally, both datasets presented a class imbalance, so I was able to use SMOTE to balance things out first on the Enron data and then on the NewtonX data. All in all, I was very intentional about devising the projects in a way that they mirrored each other and that this Enron project allowed me to take useful learnings to the NewtonX one.

- **Next Step #1:**
Use this model to label the 98K or so emails in our original Enron dataset that are unlabeled.

- **Next Step #2:**
Apply learnings from this project to the NewtonX project to be able to build a multi-class classification model that predicts the label of a given email. We can then use this classifier model to label emails automatically and create an auto-response tool that responds to emails according the what label they receive.
