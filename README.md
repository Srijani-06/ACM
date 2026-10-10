# ACM
analyze_data.py

# Task 1: Know Your Dataset

## About
This project performs Exploratory Data Analysis (EDA) on the Iris flower dataset.

## Features
- Loads data using Pandas.
- Checks missing values and duplicates.
- Calculates descriptive statistics.
- Creates three visualizations.
- Prints seven initial observations.

## Technologies
Python, Pandas, Matplotlib, Scikit-learn.

## How to Run
Install the required libraries and run:

`python analyze_data.py`

## Output
The program generates histograms, a scatter plot, and a box plot.

## Learning Outcome
I explored how to inspect a dataset, calculate statistics, and visualize numerical data.

## Note
The dataset is provided by Scikit-learn.


# Task 2: Student Performance Predictor

## About
This project uses Linear Regression to predict a sample student's final score.

## Features
- Creates a sample dataset.
- Checks for missing values.
- Splits data into training and testing sets.
- Trains a regression model.
- Evaluates the model using Mean Absolute Error.
- Displays model coefficients.

## Technologies
Python, Pandas, Scikit-learn.

## How to Run
`python student_predictor.py`

## Learning Outcome
I learned the basics of regression, train/test splitting, model evaluation, and feature coefficients.

## Limitation
The dataset is small and illustrative. Predictions are for learning purposes only and are not validated for real students.


# Task 3: Spam Detector

## About
This project classifies messages as spam or ham (not spam) using machine learning.

## Features
- Processes text messages.
- Converts text into numerical features using CountVectorizer.
- Trains Naive Bayes and Logistic Regression models.
- Compares accuracy, precision, and recall.
- Tests five custom messages.

## Technologies
Python, Pandas, Scikit-learn.

## How to Run
`python spam_detector.py`

## Learning Outcome
I learned the basics of text classification and how to compare two machine-learning models.

## Limitation
This small sample dataset is for demonstration only. Its metrics are not reliable estimates of real-world spam detection.


# Task 4: Data Cleaning Automation

## About
This project cleans a CSV file containing missing values, invalid ages, and duplicate rows.

## Features
- Loads CSV data using Pandas.
- Removes duplicate rows.
- Converts invalid age values into missing values.
- Fills missing ages using the median.
- Handles missing names and cities.
- Saves the cleaned dataset.

## Files
- `raw_data.csv`: Original sample data.
- `clean_data.py`: Cleaning script.
- `cleaned_data.csv`: Generated output.

## How to Run
`python clean_data.py`

## Technologies
Python and Pandas.

## Learning Outcome
I learned how to automate basic data cleaning and handle common CSV data problems.


# Task 5: Exploratory Data Analysis

## About
This project explores a sample dataset containing study hours, attendance, and marks.

## Features
- Displays descriptive statistics.
- Calculates correlations.
- Creates two scatter plots.
- Creates a correlation heatmap.

## Technologies
Python, Pandas, Matplotlib.

## How to Run
`python eda.py`

## Learning Outcome
I learned how to summarize numerical data and visualize relationships between variables.

## Note
The dataset is illustrative sample data. Correlation alone does not prove that one variable causes another.


# Task 6: Web Scraping for Datasets

## About
This project collects quotations from the public practice website Quotes to Scrape and converts them into a structured CSV dataset.

## Features
- Sends an HTTP request to a practice website.
- Parses HTML using BeautifulSoup.
- Extracts quotation text, author, and tags.
- Stores the collected information in a Pandas DataFrame.
- Exports the results to `quotes.csv`.

## Technologies
Python, Requests, BeautifulSoup, Pandas.

## Installation
`pip install requests beautifulsoup4 pandas`

## How to Run
`python scraper.py`

## Learning Outcome
I learned the basics of HTML parsing, web scraping, and converting unstructured website content into structured data.

## Note
An internet connection is required. The website or its HTML structure may change, and requests can fail.


# Task 7: Linear Regression from Scratch

## About
This project implements a simple linear regression model using NumPy and gradient descent.

## Features
- Uses sample study hours and marks.
- Calculates Mean Squared Error.
- Updates weight and bias using gradient descent.
- Predicts marks for five study hours.
- Plots the loss during training.

## Technologies
Python, NumPy, Matplotlib.

## Installation
`pip install numpy matplotlib`

## How to Run
`python linear_regression.py`

## Learning Outcome
I learned the basic concepts of linear regression, loss functions, weight, bias, and gradient descent.

## Note
The sample data is illustrative and does not represent real student performance.


Task 8: Basic Classification

## About
This project uses Logistic Regression to classify Iris flowers into three species.

## Features
- Loads the Iris dataset.
- Splits the data into training and testing sets.
- Trains a Logistic Regression model.
- Calculates test accuracy.
- Displays a confusion matrix.
- Predicts the species of an example flower.

## Technologies
Python, Scikit-learn.

## Installation
`pip install scikit-learn`

## How to Run
`python classification.py`

## Learning Outcome
I learned the basics of classification, training and testing a model, and evaluating predictions using accuracy and a confusion matrix.

## Note
This project uses the Iris dataset provided by Scikit-learn. Results depend on the chosen model and data split.


