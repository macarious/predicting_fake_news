# Predicting Fake News Using Logistic Regression (Implementation from Scratch)

## Introduction
The goal of this project is to create a simple logistic regression model that can accurately predict whether a news article is fake or real based on its title. No machine learning packages are used in this project. The logistic regression model is implemented from scratch using only NumPy and Pandas.

## To Run the Project
To predict whether a news article is fake or real, the project will use the following steps:
1. Open the demo notebook in Google Colab [here](https://githubtocolab.com/macarious/predicting_fake_news/blob/main/fake_news_demo.ipynb).

2. Save a copy of the notebook on your Google Drive.

3. Run the notebook by clicking on the "Runtime" tab and selecting "Run all" and the notebook will load the model parameters.

4. Enter the title of the news article you want to predict in the input box and run the cell to get the prediction.

## Dataset
The dataset used in this project is from Kaggle and can be found [here](https://www.kaggle.com/datasets/vikasukani/news-data-set-fake-news-with-python). The dataset contains three columns: `title`, `text`, and `label`. The `title` column contains the title of the news article and the `text` column contains the text of the news article. The `text` column was not used in this project. The goal of this project is to predict whether a news article is fake or real using logistic regression. The `label` column contains the label of the news article, where `FAKE` indicates that the news article is fake and `REAL` indicates that the news article is real. Approximately 50% of the news articles are fake and 50% are real.

## Preprocessing
The dataset was preprocessed by converting the `title` column into a one-hot encoded matrix. The one-hot encoded matrix will be used as input to the logistic regression model. The one-hot encoding was done without using any machine learning packages.

## Model
The logistic regression model was trained using the preprocessed dataset. The model was evaluated using various metrics such as accuracy, precision, recall, and F1 score.

## Evaluation
The following metrics were be used to evaluate the logistic regression model:
- Accuracy: 79.4%
- Precision: 80.8%
- Recall: 77.1%
- F1 Score: 78.9%

## Conclusion
The logistic regression model was able to predict whether a news article is fake or real with an accuracy of 79.4%. The model performed well in terms of precision, recall, and F1 score. The model can be used to predict whether a news article is fake or real based on its title.
