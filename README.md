# 📱 SMS Spam Detection using Machine Learning

This project is a complete machine learning pipeline to detect spam messages in SMS text. It uses Natural Language Processing (NLP) techniques and a Multinomial Naive Bayes model to classify messages as either "spam" or "ham" (not spam).

## 📂 Project Structure

📁 SMS-Spam-Detection  
├── SMS Detection1.ipynb        # Main notebook with data processing, training, and evaluation  
├── spam1.csv                   # Labeled dataset for training and testing  
├── requirements.txt            # Required Python libraries  
└── README.md                   # Project overview and documentation  

## 🧠 Model Workflow

1. Load and explore dataset  
2. Text preprocessing (lowercasing, punctuation removal, stopword removal, tokenization using NLTK)  
3. Feature extraction using TF-IDF Vectorizer  
4. Model training using Multinomial Naive Bayes  
5. Evaluation with accuracy, confusion matrix, and classification report  

## 🔧 Requirements

Install all dependencies using:

```
pip install -r requirements.txt
```

## 📊 Dataset

- File: `spam1.csv`  
- Description: Labeled SMS messages with two categories — `spam` and `ham`


## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- Pandas
- numpy
- matlplotlib
- streamlit
- Scikit-learn
- NLTK


## 📈 Results

- High model performance on test data  
- Evaluation metrics include: Accuracy, Precision, Recall, and F1-score

## 🚀 How to Run

1. Clone this repository  
2. Install dependencies from `requirements.txt`  
3. Open and run `SMS Detection1.ipynb` in Jupyter Notebook or Google Colab

## 📌 Future Work

- Deploy model with a web UI using Streamlit or Flask  
- Experiment with deep learning models (e.g., LSTM, BERT)  
- Publish to Heroku or AWS Lambda

## 🤝 Contributing

Feel free to fork this repo and open a pull request with improvements or suggestions.
