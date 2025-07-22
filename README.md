# 🧠 Sentiment Analysis on Amazon Product Reviews

This project analyzes customer reviews from Amazon to determine whether the sentiment is Positive, Negative, or Neutral.  
It uses Natural Language Processing (NLP) techniques with the VADER and TextBlob libraries.

## 📂 Dataset Used
- Input File: `amazon.csv`
- Fields: `reviewText`, `overall`, `reviewTime`, etc.

## 📊 What This Project Does
- Cleans review text (removes symbols, lowercases, etc.)
- Uses **VADER SentimentIntensityAnalyzer** to calculate sentiment score
- Labels each review as **Positive**, **Negative**, or **Neutral**
- Visualizes results using:
  - Sentiment distribution bar chart
  - Pie chart
  - WordCloud for positive & negative words

## 🛠️ Tools and Libraries
- Python
- Pandas
- NLTK (VADER)
- TextBlob
- Matplotlib, Seaborn
- WordCloud
- Google Colab

## 🚀 How to Run
1. Open `sentiment_analysis.ipynb` in Google Colab
2. Upload your `amazon.csv` file
3. Run all code cells step by step
4. Output file: `amazon_sentiment_output.csv`

## 📁 Output
- Cleaned and labeled data
- Sentiment-based visualizations
- Exported CSV with sentiment tags

## 📜 License
This project is under the MIT License.


## 👀 Sample Visualization

*(Insert screenshots of your WordCloud or bar graph here)*

## ✨ Future Improvements
- Add Streamlit dashboard UI
- Add rating-based sentiment comparison
- Connect to live Amazon API (if possible)


