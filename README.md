 **Spam Mail Detection Project**

**Project Overview**

This is a simple **Spam Mail Detection** project where we build a machine learning model to classify emails as Spam or Not Spam (Ham) based on their text content.  
The project demonstrates how to perform data preprocessing, feature extraction using TF-IDF Vectorizer, and model training using **Logistic Regression**.

**Technologies Used**

- Python 
- Pandas 
- NumPy 
- scikit-learn 

**Project Steps**

1. **Load Dataset**
   The dataset is loaded from a CSV file `mail_data.csv` containing emails labeled as Spam or Ham.

2. **Data Cleaning**
   We handle missing values by replacing them with empty strings:
   mail_data = raw_mail_data.where(pd.notnull(raw_mail_data), '')
   
4. **Feature Extraction**
  Text is converted into numerical features using TF-IDF Vectorizer.

6. **Train-Test Split**
  Data is split into training and test sets (80% train, 20% test).

8. **Model Training**
  A Logistic Regression model is trained on the processed data.

10. **Model Evaluation**
  The model is evaluated using accuracy score.
