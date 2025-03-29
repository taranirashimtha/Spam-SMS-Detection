# Spam SMS Detection using Machine Learning

This project focuses on detecting spam messages using a machine learning model trained on SMS data. The model processes text messages and classifies them as either spam or ham(not spam).

##  Dataset  
The dataset used consists of labeled SMS messages with categories:  
- Spam: Unwanted promotional or fraudulent messages  
- Ham: Legitimate messages  

##  Model Used  
- Random Forest Classifier: A powerful ensemble learning method based on decision trees  
- Naïve Bayes Classifier: A probabilistic classifier suitable for text classification  

##  Steps Involved  
1️⃣ Data Preprocessing  
   - Cleaning and tokenizing text  
   - Removing stopwords and punctuation  
   - Converting text to numerical format using TF-IDF

2️⃣ Model Training  
   - Split data into training and testing sets  
   - Trained using Random Forest & Naïve Bayes
   - Evaluated using accuracy, precision, recall, and F1-score 

3️⃣ Predictions  
   - The trained model predicts whether a new message is spam or not .

##  Tech Stack  
- Python  
- Scikit-learn 
- Pandas, NumPy
- NLTK (Natural Language Toolkit)

##  How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/taranirashimtha/Spam-SMS-Detection.git
   cd Spam-SMS-Detection
