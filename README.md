# 📱 Amazon Alexa Review Sentiment Analysis

A comprehensive exploratory data analysis of 3,150 Amazon Alexa customer reviews, analyzing sentiment patterns, product performance, rating distributions, and customer feedback behavior using Python.

## 📊 Project Overview

This project performs detailed sentiment analysis on Amazon Alexa customer reviews to understand customer satisfaction, product variation performance, and key drivers of positive and negative feedback. The analysis explores patterns in customer ratings, review text, product variations, and their relationships with overall sentiment.

### Key Analysis Performed:
- Sentiment distribution (positive vs negative reviews)
- Rating patterns and their correlation with feedback
- Product variation performance analysis
- Review length analysis by sentiment
- Word cloud visualization for common terms
- Relationship between star ratings and sentiment labels
- Product variation popularity and ratings
- Customer review text mining

## 📁 Dataset

The dataset (`amazon_alexa.tsv`) contains 3,150 customer reviews with the following columns:

| Column | Description |
|--------|-------------|
| rating | Customer star rating (1-5) |
| date | Date of the review |
| variation | Alexa product variation/model |
| verified_reviews | Customer review text |
| feedback | Sentiment label (0=Negative, 1=Positive) |

### Generated Features:
| Feature | Description |
|---------|-------------|
| review_length | Character count of each review |
| word_count | Number of words in each review |

## 🛠️ Technologies Used

- **Python 3.12.7**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib & Seaborn** - Data visualization
- **NLTK** - Text processing and stopwords
- **WordCloud** - Text visualization

## 📈 Key Insights

The analysis reveals:
- **91.8%** positive reviews, **8.2%** negative reviews
- **72.6%** of all ratings are 5-star
- Negative reviews are **40% longer** than positive reviews on average
- Clear relationship: Ratings 1-2 = Negative, Ratings 3-5 = Positive
- **Walnut Finish** is the best-rated variation (4.89 average rating)
- **Black Dot** is the most reviewed variation (516 reviews)

## 🚀 Getting Started

### Prerequisites

Install the required libraries:
pip install pandas numpy matplotlib seaborn nltk wordcloud
Running the Analysis
Clone the repository:

Amazon Alexa Review - Sentiment Analysis
Launch Jupyter Notebook:

jupyter notebook
Open and run Amazon Alexa Review Sentiment Analysis.ipynb

### 📝 Analysis Steps
 Step 1 — Import Required Libraries

 Step 2 — Load and Explore the Data

 Step 3 — Data Cleaning and Initial Checks

 Step 4 — Create New Features

 Step 5 — Rating Analysis

 Step 6 — Sentiment Analysis

 Step 7 — Rating vs Feedback Analysis

 Step 8 — Product Variation Analysis

 Step 9 — Review Length Analysis

 Step 10 — Word Cloud Visualization

 Step 11 — Positive and Negative Word Clouds

 Step 12 — Summary Statistics and Key Insights


### 📊 Sample Visualizations
The analysis generates:

Rating distribution bar chart and pie chart

Sentiment distribution visualization

Rating vs Feedback cross-tabulation

Top 10 product variations by count and rating

Review length histograms (overall, positive, negative)

Word clouds for all reviews, positive reviews, and negative reviews

### 🎯 Key Findings
## ✅ What's Working Well:
Customer Satisfaction: 91.8% of reviews are positive

Product Quality: 5-star ratings dominate at 72.6%

Top Performers: Walnut Finish and Oak Finish variations have highest ratings

### ⚠️ Areas for Improvement:
Negative Feedback: Sound quality and connectivity issues mentioned frequently

Review Length: Negative reviewers write longer, more detailed complaints

### 📂 Repository Structure
text
 amazon-alexa-sentiment-analysis/
 │
 ├── data/
 │   ├── amazon_alexa.tsv                    
 │   ├── Predictions.csv                      
 │   └── SentimentBulk.csv                    
 │
 ├── amazon_alexa_sentiment_analysis.ipynb   
 ├── requirements.txt                         
 └── README.md                       

### 📦 Dependencies
text
numpy
pandas
matplotlib
seaborn
nltk
wordcloud

### 🙏 Acknowledgments
Dataset sourced from Amazon Alexa customer reviews

Analysis inspired by real-world sentiment analysis applications

Built with Python's data science ecosystem

Special thanks to the open-source community for NLTK and WordCloud libraries        
