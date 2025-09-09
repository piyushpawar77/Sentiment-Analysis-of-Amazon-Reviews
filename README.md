# Amazon Product Reviews Sentiment Analysis

This project analyzes customer reviews from Amazon using both **VADER** and **RoBERTa** sentiment models. It combines traditional lexicon-based methods with advanced transformer-based techniques to explore how sentiments align with review ratings and text features.

## 🧠 Sentiment Analysis Methods

This project uses two popular sentiment analysis tools:

### 📊 VADER (Valence Aware Dictionary and Sentiment Reasoner)
VADER is a lexicon-based sentiment analysis tool that works well on social media text. It uses a list of words with predefined sentiment scores to calculate how positive, negative, or neutral a sentence is. It's lightweight and fast, making it great for real-time applications.

### 🤖 RoBERTa (A Robustly Optimized BERT Pretraining Approach)
RoBERTa is a deep learning model based on the Transformer architecture. It is trained on large text datasets and can understand complex language patterns, making it more accurate in analyzing sentiment compared to traditional methods. In this project, we use a version fine-tuned for Twitter sentiment analysis.

## 📂 Dataset

The dataset is not included due to size restrictions. You can download the Amazon Reviews dataset from [Kaggle](https://www.kaggle.com/bittlingmayer/amazonreviews) or other sources and place the `Reviews.csv` file in the project directory before running the notebook.

## 🚀 Features
- Clean and preprocess review text
- Extract text-based features (word count, token length, etc.)
- Perform sentiment analysis with VADER and RoBERTa
- Compare sentiment scores with star ratings
- Visualize results using word clouds, bar plots, violin plots, PCA, and more

## 🛠 Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- NLTK (tokenization, VADER sentiment analysis)
- Hugging Face Transformers (RoBERTa model)
- Scikit-learn (PCA, scaling)
- WordCloud for text visualization

## 📊 Insights
- Sentiment scores correlate with star ratings
- Identify reviews where sentiment differs from rating
- Explore positive and negative word patterns
- Use PCA to reduce sentiment features and spot trends

## 📥 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/amazon-reviews-sentiment.git
   cd amazon-reviews-sentiment
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Download Reviews.csv and place it in the project folder.

Run the notebook to explore the analysis.

📌 Notes
Tested with nltk version 3.7

Handles missing values and runtime errors

Combines simple and deep learning methods for robust sentiment insights
