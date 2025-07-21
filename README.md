# Hotel Review Sentiment Analysis Using NLP

This project demonstrates a full Natural Language Processing (NLP) pipeline applied to hotel review data. 
The goal is to analyze customer feedback, extract insights, and evaluate the alignment between predicted sentiment and customer ratings using the VADER sentiment analyzer.

## 📌 Objectives

- Clean and tokenize raw hotel review text
- Remove stopwords and apply lemmatization
- Generate and analyze n-grams (bigrams and trigrams)
- Perform sentiment analysis using VADER
- Compare sentiment predictions to actual review ratings
- Evaluate the impact of preprocessing steps


## 🛠️ Technologies Used

- Python
- NLTK
- pandas
- matplotlib
- VADER Sentiment Analyzer
- nltk.FreqDist for term frequency analysis


## 📂 Project Structure

### Step 1: Text Cleaning and Tokenization

- Lowercased text, removed punctuation/special characters
- Tokenized into sentences and word tokens
- Counted unique tokens pre-cleaning

### Step 2: Stopword Removal and Normalization

- Removed English stopwords
- Applied lemmatization with proper POS tagging
- Counted unique tokens post-lemmatization
- Calculated reduction in vocabulary size

### Step 3: N-Grams and Frequency Analysis

- Generated bigrams and trigrams from cleaned tokens
- Identified most frequent words and phrases
- Compared term frequencies across positive and negative reviews
- Visualized top 20 tokens and bigrams using matplotlib

### Step 4: Sentiment Analysis with VADER

- Reconstructed lemmatized text for sentiment scoring
- Applied VADER to generate sentiment scores
- Classified sentiment as positive, negative, or neutral
- Compared predicted sentiment with actual ratings
- Calculated accuracy and visualized mismatches

### Step 5: Evaluation of Preprocessing Pipeline

- Measured vocabulary size at each stage:
  - Original
  - After stopword removal
  - After lemmatization
- Calculated and interpreted token reduction percentages


## 📊 Results

- Achieved sentiment classification accuracy of approximately **XX%**
- Vocabulary reduced by **YY%** after preprocessing
- Most mismatches occurred with **neutral ratings (3-star)**, indicating ambiguity
- Identified key positive and negative phrases that frequently appeared in reviews


## 📈 Example Visualizations

- Top 20 most common words in all reviews
- Top 20 most common bigrams
- Most frequent words in positive vs. negative reviews


## 🚀 Future Improvements

- Incorporate domain-specific stopwords (e.g., “hotel”, “room”)
- Explore deep learning-based sentiment analysis (BERT, RoBERTa)
- Enhance sarcasm/negation handling
- Build an interactive dashboard (Streamlit/Plotly)


## 🧠 Author

**Alejandro Silva**  
Data Scientist | NLP Enthusiast | Energy + Forecasting Expert  
[LinkedIn](https://www.linkedin.com/in/alejandro-silva/)  
For collaboration, reach out via GitHub or email!
