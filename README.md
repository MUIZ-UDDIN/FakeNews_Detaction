# Fake News Detection Project

## Overview

This project aims to detect fake news using machine learning techniques. It utilizes natural language processing (NLP) and classification algorithms to distinguish between fake and genuine news articles.

## Dataset

Two datasets are used in this project:
- `Fake.csv`: Dataset containing fake news.
- `True.csv`: Dataset containing true news.

## Data Preprocessing

The datasets undergo preprocessing steps to prepare them for model training:
- Combining datasets and labeling fake news as 0 and true news as 1.
- Removing the last ten entries from both datasets for manual testing.
- Text cleaning and normalization using regular expressions.

## Model Training

Various classification algorithms are employed for model training:
- Logistic Regression
- Decision Tree Classifier
- Gradient Boosting Classifier
- Random Forest Classifier

### Model Evaluation

The models are evaluated based on accuracy scores on the testing set.

## Manual Testing

A manual testing function allows users to input a news article and obtain predictions from each classifier. The predictions are then displayed with labels indicating whether the news is classified as fake or not.


Certainly! Here's a template for your GitHub README based on the provided code:

markdown
Copy code
# Fake News Detection Project

## Overview

This project aims to detect fake news using machine learning techniques. It utilizes natural language processing (NLP) and classification algorithms to distinguish between fake and genuine news articles.

## Dataset

Two datasets are used in this project:
- `Fake.csv`: Dataset containing fake news.
- `True.csv`: Dataset containing true news.

## Data Preprocessing

The datasets undergo preprocessing steps to prepare them for model training:
- Combining datasets and labeling fake news as 0 and true news as 1.
- Removing the last ten entries from both datasets for manual testing.
- Text cleaning and normalization using regular expressions.

## Model Training

Various classification algorithms are employed for model training:
- Logistic Regression
- Decision Tree Classifier
- Gradient Boosting Classifier
- Random Forest Classifier

### Model Evaluation

The models are evaluated based on accuracy scores on the testing set.

## Manual Testing

A manual testing function allows users to input a news article and obtain predictions from each classifier. The predictions are then displayed with labels indicating whether the news is classified as fake or not.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/fake-news-detection.git
Navigate to the project directory:

bash
Copy code
cd fake-news-detection
Run the main script:

bash
Copy code
python fake_news_detection.py
Enter a news article when prompted for manual testing.

Requirements
Python 3.x
Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn
License
This project is licensed under the MIT License.

Acknowledgments
The project acknowledges the use of the fake and true news datasets.
