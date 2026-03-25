# Customer Review Analysis – Food Products

## 📌 Project Overview
This project analyzes customer reviews from the Amazon Fine Food Reviews dataset to understand the main problems reported by users.

## 🎯 Objective
The goal was to identify common issues in negative reviews and understand what causes customer dissatisfaction.

## 🧰 Tools
- Python
- Pandas
- Matplotlib
- Scikit-learn (CountVectorizer)

## 🔍 Approach

### Data Analysis
Dataset is unbalanced – most reviews are 5/5, while negative ones (1–2 stars) are around 14%.  
This means the analysis focuses on a smaller but more meaningful part of the data.

### Text Analysis
Reviews are relatively long (around 80 words on average), which provides enough information for analysis.  
Negative reviews tend to be slightly longer, suggesting that users describe problems in more detail.

### Bigram Analysis
Bigram analysis shows that taste is one of the most important factors in negative reviews.  
Users often mention taste and flavor when describing problems.

Phrases like "waste money" suggest that customers feel the product is not worth the price.  

We can also see issues related to:
- product categories (e.g. pet food, drinks)
- expiration dates
- customer service

However, bigrams alone do not always show clear sentiment, because some phrases (like "taste good") can still appear in negative reviews.

## ⚠️ Limitations
- Bigram analysis does not fully capture context
- No advanced NLP techniques were used

## 🚀 Next Steps
- Add sentiment classification model
- Try topic modeling
- Improve text preprocessing
