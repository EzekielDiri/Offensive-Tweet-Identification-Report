# Offensive-Tweet-Identification-Report

This report is aimed to classify offensive tweets using natural language processing (NLP) and machine learning techniques. The dataset used is the OLID dataset (olid-training-v1.0.tsv), containing over 13,000 tweets labeled into various categories related to offensiveness.

## Data Preprocessing
To begin the process, series of preprocessing steps wehre applied on the tweet text to ensure the data was ready for machine learning models. These steps included:

1. Tokenizing the tweet text.
2. Converting all text to lowercase for consistency.
3. Removing punctuation and stopwords to focus on meaningful words.

## Model Training
Several machine learning models were used to classify the tweets as offensive or not offensive. The models included:

1. Logistic Regression
2. Random Forest
3. Bernoulli Naive Bayes
4. Gradient Descent

The features were scaled, and each model was trained using k-fold cross-validation to ensure robust evaluation.

## Model Evaluation
To evaluate the performance of the models, confusion matrices, accuracy scores, and classification reports were used. Below is a confusion matrix that visualizes the performance of one of the machine learning models in predicting offensive tweets:

<img src="https://github.com/user-attachments/assets/c714e8c6-c14a-49b1-9c2a-f0d3e751c325" width="500" height="400">

## Accuracy Comparison of Models
A bar chart was generated to compare the accuracy of the different models used in this project.

+ Random Forest achieved the highest accuracy at 86%.
+ Bernoulli Naive Bayes followed with 75% accuracy.
+ Gradient Descent with 72% and
+ Regression Logistic had accuracies of 71%, respectively.


The bar chart below visualizes the accuracy of each model:

<img src="https://github.com/user-attachments/assets/fae3d83c-cd78-4485-9084-af2e58cf847c" width="500" height="400">

## Conclusion
From the evaluations, it is evident that the Random Forest model performed best, achieving the highest accuracy in identifying offensive tweets. The preprocessing steps and evaluation techniques used ensured that the models were well-suited for the classification task.

