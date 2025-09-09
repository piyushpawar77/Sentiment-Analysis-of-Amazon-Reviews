# Amazon Product Reviews Sentiment Analysis

This project analyzes customer reviews from Amazon using both **VADER** and **RoBERTa** sentiment models. It combines traditional lexicon-based methods with advanced transformer-based techniques to explore how sentiments align with review ratings and text features.

## 🚀 Features
- Clean and preprocess review text
- Extract text-based features (word count, token length, etc.)
- Perform sentiment analysis with VADER and RoBERTa
- Compare sentiment scores with star ratings
- Visualize results using word clouds, bar plots, violin plots, PCA, and more

## 📂 Dataset
The dataset (`Reviews.csv`) contains reviews with columns like `Text`, `Summary`, `Score`, `Id`, and `Time`. The analysis focuses on the first 500 reviews.

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
