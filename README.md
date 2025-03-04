# Fake News Detection

## Overview
This project aims to build a machine learning model that classifies news articles as **true** or **fake** based on their content. The model uses **Logistic Regression** and is trained on a dataset of labeled news articles.

## Key Features:
- **Data Preprocessing**: Cleaned the text data using **CountVectorizer**, removed stopwords, and tokenized the text.
- **Model**: Built using **Logistic Regression** and evaluated using **cross-validation**.
- **Hyperparameter Tuning**: Optimized using **GridSearchCV** to improve model performance.

## Results:
- **Test Accuracy**: 92.98%
- **Confusion Matrix**: Shows a high level of precision and recall.
- **Visualizations**: Includes ROC curve and Confusion Matrix plot for model evaluation.

## Files:
- `fake_news_detection.ipynb`: The main Jupyter notebook with code, results, and analysis.
- `README.md`: This file.

## Installation:
1. Clone the repository:  
   `git clone https://github.com/Biruk34/fake-news.git`
   
2. Install necessary libraries:  
   `pip install -r requirements.txt`

## License:
MIT License
