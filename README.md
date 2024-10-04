# Amazon Reviews Sentiment Analysis

This project focuses on performing sentiment analysis on Amazon reviews using multiple techniques, such as VADER, TF-IDF, and Roberta from Huggingface. The project includes exploratory data analysis (EDA), as well as both regression and classification tasks for predicting review scores and helpfulness.

## Key Features

1. **Data Loading & Cleaning**:
   - Reads the dataset and preprocesses the reviews (e.g., removing stopwords, handling missing values).
   
2. **Exploratory Data Analysis (EDA)**:
   - Visualization and insights of review length, helpfulness, score distribution, etc.

3. **Sentiment Analysis Techniques**:
   - **VADER**: A rule-based sentiment analysis tool tuned for social media text.
   - **TF-IDF with Machine Learning Models**: Features extraction and classification using models like Logistic Regression and SVM.
   - **Roberta (Huggingface)**: A transformer-based model to capture contextual sentiment.

4. **Regression & Classification Tasks**:
   - **Predicting Review Score**: Using regression models to predict the review score based on the review text.
   - **Predicting Helpfulness**: A classification task to predict whether a review is helpful based on text features.

## Installation

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Dataset
You can find the overview of the dataset and dataset itself here: https://snap.stanford.edu/data/web-Movies.html

The project uses an Amazon reviews dataset with the following columns:
- **Text**: Review text
- **Score**: Rating given by the reviewer
- **Helpfulness_Numerator**: Number of people who found the review helpful
- **Helpfulness_Denominator**: Total number of people who rated the review's helpfulness

## Results

- Sentiment analysis models are compared based on accuracy and performance metrics.
- Predictive models for review scores and helpfulness are evaluated using cross-validation and performance metrics (e.g., MSE, MAE, F1-score).

## Contributing

Feel free to submit issues or pull requests. Contributions are welcome!