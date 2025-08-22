# 📧 Spam Mail Detection

This project detects whether an email is **Spam** or **Ham (Not Spam)** using **Machine Learning**.  
It includes **text preprocessing, feature extraction, and classification models** to build an accurate spam detection system.

---

## 📂 Dataset
The dataset consists of email messages labeled as **spam** or **ham**.  
(You can use datasets from [Kaggle SMS Spam Collection](https://www.kaggle.com/uciml/sms-spam-collection-dataset) or custom datasets.)

---

## 🛠️ Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Scikit-learn  
- NLTK / Regular Expressions  
- Jupyter Notebook  

---

## ⚙️ Workflow
1. **Data Preprocessing**
   - Handle missing values
   - Convert labels (ham → 0, spam → 1)
   - Clean text (remove stopwords, punctuation, etc.)

2. **Feature Extraction**
   - Bag of Words (BoW)  
   - TF-IDF Vectorizer  

3. **Model Training**
   - Naive Bayes  
   - Logistic Regression   

4. **Evaluation**
   - Accuracy Score  
   - Confusion Matrix  
   - Precision, Recall, F1-score  

---

## 📊 Results
- Naive Bayes performed best for spam detection with high accuracy.  
- Text preprocessing and TF-IDF significantly improved model performance.  

---
