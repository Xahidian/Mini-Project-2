# Mini Project 2 – Twitter Sentiment Analysis using Machine Learning
## Author: Md Hasibul Haque Zahid
## Student ID: 2302302

## Introduction
This project focuses on sentiment analysis of Twitter data, aiming to classify tweets from the Sentiment140 dataset into different sentiment categories[^3^][3]. The challenge lies in processing tweets with special characters, URLs, and mentions to ensure model effectiveness

## Data Processing Method
- **Loading the Data**: Utilized pandas to load TSV data into a DataFrame.
- **Splitting the Data**: Employed train_test_split from sklearn.model_selection, with 80% for training and 20% for testing.
- **Text Transformation**: Applied TF-IDF and BoW techniques to transform text data into numerical vectors for machine learning models
## Modeling
Two machine learning models were explored:
- **Logistic Regression**: Achieved ~78.6% accuracy using TF-IDF vectors
- **Naive Bayes**: Reached ~76.6% accuracy with BoW vectors.

## Challenges and Solutions
- **High-Dimensional Feature Space**: Implemented regularization techniques to avoid overfitting.
- **Imbalanced Classes**: Explored oversampling and class weights to balance training.
- **Model Selection and Hyperparameter Tuning**: Tested various models and tuning methods for optimization.
- **Convergence Warning**: Increased iterations and scaled data to address logistic regression warnings.
- **Understanding Model Predictions**: Conducted feature importance analysis for insights.
- **Applicability to Real-World Scenarios**: Used cross-validation and external validation to ensure generalization.

## Technologies Used
- Python
- Jupyter Notebook

## Report
I have also written a detailed report based on these Project. The report provides a comprehensive overview of the Project.For more information, please refer to the report.

## Conclusion
The project tackled scientific challenges in sentiment analysis, offering solutions and improvements for future work.

## Contact
If you have any questions or would like to discuss the project further, feel free to reach out to me.
Thank you for visiting my Project!


