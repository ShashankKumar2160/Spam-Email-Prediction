# Spam Email Prediction 📧🚫

Welcome to the **Spam Email Prediction** project! This is a machine learning-based solution to classify emails as **spam** or **ham** (not spam) using Natural Language Processing (NLP) and Multinomial Naive Bayes classifier.

> **Project by:** [Shashank Kumar](https://github.com/ShashankKumar2160)  
> 📩 Email: shashankkumar2160@gmail.com

---

## 📝 Project Overview

The goal of this project is to develop a predictive model that can efficiently detect spam emails based on their content. The dataset consists of labeled email messages, and we perform text cleaning, transformation, and model training to achieve high accuracy in classification.

---

## 🛠️ Technologies & Tools Used

- **Python 3**
- **Jupyter Notebook**
- **Pandas** — for data manipulation
- **NumPy** — for numerical computations
- **Matplotlib & Seaborn** — for data visualization
- **Scikit-learn** — for ML algorithms and evaluation
- **NLTK** — for text preprocessing
- **TF-IDF Vectorizer** — for feature extraction

---

## 📂Project Structure

```
├── spamPrediction.ipynb          # Main Jupyter notebook
├── dataset.csv                   # Dataset file (spam/ham emails)
├── README.md                     # Project documentation
├── requirements.txt              # List of dependencies
```

## ⚙️ Workflow

1. **Data Loading**  
   Load and explore the email dataset.

2. **Data Cleaning & Preprocessing**  
   - Lowercasing
   - Removing punctuation
   - Removing stopwords
   - Stemming

3. **Feature Extraction**  
   - Convert text to numerical vectors using **TF-IDF**

4. **Model Building**  
   - Model used: **Multinomial Naive Bayes**

5. **Model Evaluation**  
   - Accuracy Score
   - Confusion Matrix
   - Precision, Recall, F1-Score

6. **Prediction**  
   - Test the model on new/unseen emails.

---

## 🚀 How to Run the Project

1. Clone the repository:
   \```
   git clone https://github.com/ShashankKumar2160/Spam-Email-Prediction.git
   cd Spam-Email-Prediction
   \```

2. Install the required packages:
   \```
   pip install -r requirements.txt
   \```

3. Open the Jupyter Notebook:
   \```
   jupyter notebook spamPrediction.ipynb
   \```

4. Run all the cells and see the magic!

---

## 📊 Results

- ✅ **Model Accuracy:** ~97%
- ✅ **High Precision and Recall**
- ✅ **Confusion Matrix** and classification report included in the notebook.

> 🎉 The model performs excellently in distinguishing between spam and ham emails!

---

## 🤖 Future Enhancements

- Deploy the model as a web application
- Test on larger and diverse datasets
- Explore deep learning approaches (e.g., LSTM, BERT)

---

## 🤝 Connect with Me

- **GitHub:** [ShashankKumar2160](https://github.com/ShashankKumar2160)
- **Email:** shashankkumar2160@gmail.com

---

## 📄License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*Made with ❤️ by Shashank Kumar*
