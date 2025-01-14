# Text-Analytics-Airline-reviews
This project analyzes Indian airline reviews (2016–2023) from Skytrax for seven airlines. Using text processing, classification, and topic modeling, it identifies key customer sentiments and actionable insights. Python is used for analysis and to  provide business-relevant recommendations, enhancing customer satisfaction and service quality.
# Introduction
Sentiment Analysis is a prominent application of Natural Language Processing (NLP) that enables the classification of textual data based on emotions or opinions. It plays a vital role in understanding customer feedback, identifying issues, and improving services. In this project, we focus on analyzing customer reviews for airlines, categorizing them into positive, negative, and neutral sentiments, and identifying the underlying themes through topic modelling.
Additionally, we employ machine learning classification models to predict sentiments based on review data, thereby streamlining decision-making processes.
# Problem Statement
The objective is to analyze airline reviews to:
•	Classify reviews into positive, negative, or neutral sentiments.
•	Identify actionable themes and patterns in customer feedback using topic modelling.
•	Build and compare classification models to predict sentiments, selecting the best-performing model based on evaluation metrics such as F1-Score.

# Workflow

Dataset Loading and Preprocessing:
Loaded the dataset and inspected its structure.
Handled missing values and cleaned the text data (removal of stop words, lemmatization, and regex cleaning).

Exploratory Data Analysis (EDA):
Created visualizations, including word clouds and frequency plots, to identify key terms and trends.
Analyzed rating distribution, recommendation counts, and average ratings per airline.

Sentiment Analysis:
Computed sentiment polarity and classified reviews as positive, negative, or neutral.
Analyzed sentiment trends over time and by airline.

Topic Modeling:
Applied LDA with TF-IDF to extract key themes from reviews.
Refined topics using bigrams and trigrams for better context.
Performed airline-specific topic modeling.

Classification Modeling:
Built and evaluated multiple classification models (Logistic Regression, Decision Tree, Random Forest, SVM, and Neural Network).
Identified the best-performing model based on accuracy and F1-score.

# Insights and Recommendations:
Derived actionable insights for each airline based on sentiment and topic modeling.
Proposed improvements like addressing flight delays, enhancing customer support, and optimizing cabin comfort.
