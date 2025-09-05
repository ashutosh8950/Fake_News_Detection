# Fake_News_Detection
📰 Fake News Detection

A machine learning project to classify news articles as real or fake using multiple ML models. The dataset is preprocessed, vectorized, and evaluated using various supervised learning techniques.

📌 Project Overview

Fake news has become a major concern in today’s digital era. This project builds a Fake News Detection system that can classify whether a news article is Fake or Real using Natural Language Processing (NLP) and Machine Learning models.

The workflow includes:

Data preprocessing and cleaning

Text vectorization

Model training & evaluation

Performance comparison across algorithms

⚙️ Tech Stack

Language: Python

Libraries:

Data Handling: pandas, numpy

Visualization: matplotlib, seaborn

NLP & ML: scikit-learn

Text Processing: re, string

📂 Dataset

The dataset includes True and Fake news articles.

Dataframes are merged, shuffled, and preprocessed to create a balanced dataset.

Text is cleaned and converted into numerical vectors for ML models.

🚀 Models Implemented

The following models were trained and evaluated:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Passive Aggressive Classifier

📊 Evaluation Metrics

Accuracy Score

Classification Report (Precision, Recall, F1-Score)

📈 Results

Each model’s performance is compared, and results are presented using evaluation metrics and visualizations.

🔧 How to Run

Clone the repository:

git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection


Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook / Google Colab:

jupyter notebook FAKE_NEWS_DETECTION.ipynb

📌 Future Enhancements

Use Deep Learning models (e.g., LSTM, BERT) for better accuracy.

Deploy as a web app using Flask/Django.

Integrate real-time fake news detection from online sources.

📜 License

This project is open-source and available under the MIT License.
