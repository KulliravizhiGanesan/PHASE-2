# Decoding Emotions: Sentiment Analysis of Social Media Conversation

## Project Overview
This project aims to design a system that can automatically analyze and classify emotions expressed in social media conversations. With the increasing amount of user-generated content on platforms like Twitter, Reddit, and YouTube, extracting insights from sentiments has become valuable for businesses, governments, and researchers.

## Objectives
- Build an accurate model for sentiment/emotion classification.
- Preprocess and clean social media text data.
- Visualize sentiment trends over time or topics.
- Evaluate and compare multiple modeling approaches.
- Deploy a user-accessible sentiment analysis system.

## Scope
- English-language content only.
- Platforms: Twitter, Reddit, YouTube.
- Sentiments: Positive, Negative, Neutral, etc.
- Approaches: Machine Learning and Deep Learning.
- Deployment via web dashboard or API.
- Multilingual and image-based sentiment analysis are excluded.

## Data Sources
- Twitter API (Tweepy or snscrape)
- Reddit API (PRAW or Pushshift)
- YouTube Data API
- Kaggle sentiment datasets
- Web-scraped forums/blogs (BeautifulSoup, Scrapy)

## Methodology
1. **Data Collection** – APIs or scraping tools.
2. **Data Cleaning** – Removing noise, normalizing text.
3. **EDA** – Sentiment distribution, trends, word frequencies.
4. **Feature Engineering** – Using TF-IDF, Word2Vec, or BERT.
5. **Model Building** – ML/DL algorithms (e.g., Logistic Regression, LSTM, BERT).
6. **Evaluation** – Accuracy, F1 score, confusion matrix.
7. **Visualization** – Word clouds, sentiment graphs, trend lines.
8. **Deployment** – REST API (Flask/FastAPI) or dashboard (Streamlit).

## Tools & Technologies
- **Languages**: Python
- **Libraries**: NLTK, SpaCy, Scikit-learn, TensorFlow, PyTorch
- **Visualization**: Matplotlib, Seaborn, Plotly, WordCloud
- **Deployment**: Flask, Streamlit, Docker, Heroku
- **Others**: Jupyter, Git, Google Colab

## Team Members and Roles
- **LEKHA R** – Problem Statement
- **GOPIKA V** – Project Objectives
- **DHARSHINI K** – Scope and Data Sources
- **JECINTHA M.S** – Methodology
- **KULLIRAVIZHI G** – Tools and Technologies

## How to Run the Project
1. Run `source_data.py` to generate `dataset.csv`.
2. Run `read_file.py` to load and explore the dataset.
3. Proceed to training, visualization, and deployment as needed.

---

Feel free to contribute or suggest improvements!
