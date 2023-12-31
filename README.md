# Movie Genre Classification

## Introduction

This project is a movie genre classification project. The goal is to predict the genre of a movie based on its plot summary. The dataset is from [Kaggle](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb). This dataset contains movies and their plot descriptions from IMDB.

### Steps to run the project

1. Clone the repository
2. Install the requirements using `pip install -r requirements.txt`
3. Run the `main.ipynb` file using `jupyter notebook`

## Usage

### Data

The dataset is split into train and test sets. The train set is used to train the model and the test set is used to evaluate the model. The train set is further split into train and validation sets. The train set is used to train the model and the validation set is used to evaluate the model.

### Cleaning

The data is cleaned by removing the stopwords and lemmatizing the words. The data is then vectorized using TF-IDF vectorizer.

### Model

The model is a simple Logistic Regression model, trained along with the OneVsRestClassifier.

### Evaluation

The model is evaluated using the accuracy score and the confusion matrix.

## Results

The model achieved an accuracy of 0.58 on the test set and the predictions are shown in the file `Predicted_Genres.csv`.
