Fake News Detection Project

Introduction
This project focuses on detecting fake news using machine learning techniques. It leverages natural language processing (NLP) and classification algorithms to distinguish between fake and genuine news articles.

Dataset
The project utilizes two datasets - one containing fake news (Fake.csv) and another containing true news (True.csv). Both datasets are loaded into Pandas DataFrames for further processing.

Data Preprocessing
The datasets undergo several preprocessing steps to prepare them for model training. These steps include:

Combining datasets and labeling fake news as 0 and true news as 1.
Removing the last ten entries from both datasets for manual testing.
Performing text cleaning and normalization using regular expressions to optimize the text data.

Model Training
The project employs various classification algorithms for model training, including Logistic Regression, Decision Tree Classifier, Gradient Boosting Classifier, and Random Forest Classifier.

The training process involves the following steps:

Splitting the dataset into training and testing sets.
Applying TF-IDF vectorization to convert text data into numerical features.
Training each classifier using the TF-IDF-transformed training data.

Model Evaluation
The trained models are evaluated based on their accuracy scores on the testing set. The following classifiers are used:

Logistic Regression
Decision Tree Classifier
Gradient Boosting Classifier
Random Forest Classifier

Manual Testing
The project includes a manual testing function that allows users to input a news article and obtain predictions from each classifier. The predictions are then displayed with labels indicating whether the news is classified as fake or not.

Requirements
Python 3.x
Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn

License
This project is licensed under the MIT License.

Acknowledgments
The project acknowledges the use of the fake and true news datasets.
