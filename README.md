# Spam Detection App 

A machine learning–based spam detection application built using Python, Scikit-learn, and Streamlit.  
The model classifies SMS messages as "Spam" or "Ham (Not Spam)" using Natural Language Processing techniques.


## Features
- Text preprocessing using lemmatization and stopword removal
- Feature extraction using TF-IDF Vectorization
- Classification using Logistic Regression
- Interactive Streamlit web app
- Visual analysis of spam vs ham message distribution
- Real-time spam prediction with confidence score


## Tech Stack
- Python  
- Pandas, NumPy  
- NLTK  
- Scikit-learn  
- Streamlit  
- Matplotlib  


## Dataset
- Name: SMS Spam Collection Dataset  
- Source: Kaggle  
- Link: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset  
- Size: ~5,574 SMS messages  
- Labels: spam, ham  
- Columns:
  - label – Spam or Ham  
  - message – SMS text  

## Preprocessing Steps
- Converted text to lowercase  
- Removed punctuation and special characters  
- Removed stopwords  
- Applied WordNet Lemmatization  
- Converted text into numerical features using TF-IDF Vectorizer


## Model Details
- Algorithm: Logistic Regression  
- Vectorization: TF-IDF  
- Train-Test Split: 80% / 20%  
- Class balancing: Enabled  
- Evaluation Metric: Accuracy score  


## How to Run the Project

    1. Clone the repository
    ```bash
    git clone https://github.com/Altamash0008/spam-detection.git
    cd spam-detection
    
    2. Install required libraries
        pip install -r requirements.txt
    
    3. Run the Streamlit app
        streamlit run spam_detect_app.py 


## Output
- Displays dataset sample and class distribution
- Shows model accuracy
- Allows user to input a message and receive:
    - Spam / Not Spam prediction
    - Confidence score

## Screenshots

    1. Home Page
        ![Home Page](screenshots_spam/spam_app_home.png.jpeg)

    2. Predictions
        ![Prediction Result](screenshots_spam/prediction_spam.jpeg)
        ![Prediction Result](screenshots_spam/prediction_ham.jpeg)