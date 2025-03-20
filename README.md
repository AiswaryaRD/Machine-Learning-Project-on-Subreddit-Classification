# AI-Powered Moral Judgment Dilemmas of Reddit

## Academic Project:
Course        : DATA245
Group Number  : 1

 ## Project Overview:
 The project applies Machine Learning (ML) and Natural Language Processing (NLP) techniques to automate moral judgment classification in the r/AmItheJerk subreddit. Users in this community post narratives seeking feedback on whether their actions were justified, with responses classified using the labels:

    - YTJ (Yes, The Jerk)
    - NTJ (Not, The Jerk)
Traditionally, classification relies on human responses, which can be subjective and time-consuming. The text classification models are leveraged to efficiently and accurately predict judgments based on top-level comments.

## Project Objectives:
  - To develop an automated text classification system to determine YTJ/NTJ labels.
  - To experiment multiple ML models to select the most effective classifier.
  - To optimize the model performances through feature engineering and hyperparameter tuning.
  - To deploy a Streamlit-based application for real-time predictions.

## Dataset Information:
  - Sourced from Pushshift.io, a large-scale Reddit archive repository, providing historical submission and comment data.
  - Focused on r/AmITheJerk subreddit data from December 2023 – April 2024.
  - Choice of Categories Submissions (Posts) of 125GB (approx.) and Comments of 250GB (approx.)
  - Downloaded in `.zst` blocks and converted to `.zst` files leading as a part of processing.
  - Extracted necessary fields and merged to a single CSV file of Posts 235.2MB and Comments 4.5GB as the final dataset

Further the final dataset used for preprocessing, text classification, and model training.


## Tools/Technologies:
 - Programming: Python
 - ML Models: Random Forest, XGBoost, SVM, Logistic Regression, Decision Trees
 - NLP Processing: NLTK, TF-IDF
 - Optimization: Grid Search Cross-Validation
 - Deployment: Streamlit

## Methodologies:
  - Data Preprocessing: Tokenization, lemmatization, stopword removal.
  - Feature Extraction: TF-IDF Vectorization.
  - Model Training: Multiple ML models with hyperparameter tuning.
  - Evaluation Metrics: Accuracy, Precision, Recall, F1-score.
  - Deployment: Interactive Streamlit app for real-time predictions.

## Conclusion:
Of all the other models inferred Random Forest as the best performing model with Accuracy (72%)  and Precision (74%).

## Future Enhancements:
- Accuracy improvements using Deep Learning Models using Transformers
- Cloud Deployments for Real-time predictions
- Dataset expansion for achieving better generalizations
Youtube Video Link :https://youtu.be/aXJtnJFKUwM?si=YmOMGugPJQXzH4tg

## Contributors:
Aiswarya Raghavadesikan | 
Aafrin Shehnaz Mohamed Sulaiman | 
Shivram Sriramulu | 
Shreenithi Sivakumar | 
Yogavarshni Ramachandran |
