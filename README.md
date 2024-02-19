# Scam_Job_Prediction
This repository contains code for analyzing job postings to identify fraudulent ones. The analysis involves preprocessing the textual data, exploring various features, and building machine learning models for classification.
Data Processing: The initial step involves data loading from a CSV file (fake_job_postings.csv). Null values are handled, and unnecessary columns are dropped.
Exploratory Data Analysis (EDA): Several visualizations are generated to gain insights into the data. This includes plots showing the distribution of fraudulent vs. non-fraudulent job postings, the distribution of job postings based on required experience and education, and country-wise distribution of jobs.
Text Processing: The textual data is preprocessed, including cleaning and tokenization using spaCy. Stopwords and punctuation are removed, and lemmatization is applied.
Feature Engineering: TF-IDF vectorization is used to convert text data into numerical features.
Modeling: Two classification models are trained and evaluated: Random Forest Classifier and Support Vector Machine (SVM). Additionally, a Neural Network model is trained using MLPClassifier.
Evaluation: Model performance is evaluated using accuracy scores and confusion matrices. Classification reports are also generated for detailed performance analysis.
