# CODTECH

COMPANY: CODTECH IT SOLUTIONS

NAME: KUNTA NANDITHA

INTERN ID: CT06WK26

DOMAIN: DATA SCIENCE

DURATION: 6 WEEKS

MENTOR: NEELA SANTOSH

## AUTOMATING THE ETL PROCESS (Task 1)
This project fetches trending YouTube videos using the YouTube API, performs data preprocessing and transformation, and saves the cleaned data to a CSV file.

## Tools Used
- Python
- Pandas
- Scikit-learn
- YouTube Data API

## ETL Steps
- **Extract**: API call to fetch trending videos
- **Transform**: Data cleaning, encoding, and formatting
- **Load**: Export the transformed data into a CSV file

## Output
The processed data is saved as `youtube_trending_videos.csv`.
[youtube_trending_videos.xls](https://github.com/user-attachments/files/19737159/youtube_trending_videos.xls)


#  Starbucks Review Sentiment Analysis(Task 2)

This project implements a deep learning model using TensorFlow to perform **sentiment analysis** on customer reviews of Starbucks products. The model classifies reviews into three categories: **positive**, **neutral**, and **negative** based on the text and associated rating.

---

## Project Objective

To build a **Natural Language Processing (NLP)** pipeline using a **deep learning model (LSTM)** to classify review sentiments. The goal is to understand customer feedback trends and provide insights using real Starbucks review data.

---

## Tools and Technologies

- Python 
- TensorFlow & Keras
- NLTK (Natural Language Toolkit)
- Pandas, NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## Dataset

The dataset consists of Starbucks customer reviews along with their ratings. The reviews are used to generate a sentiment label:
- `positive`: rating ≥ 4  
- `neutral`: rating = 3  
- `negative`: rating ≤ 2

---

## Steps Covered

1. **Data Loading & Cleaning**
2. **Text Preprocessing**
   - Tokenization
   - Stopword removal
   - Padding sequences
3. **Label Encoding**
4. **Train-Test Split**
5. **Model Building (LSTM)**
6. **Model Training**
7. **Evaluation**
   - Classification Report
   - Confusion Matrix
   - Sentiment Distribution Visualization

---

## Model Architecture

- **Embedding Layer**
- **LSTM Layer**
- **Dropout Layer**
- **Dense Output Layer** (Softmax activation for 3 sentiment classes)

---

## Results

- Sentiment distribution plot
- Confusion matrix for performance evaluation
- Precision, recall, and F1-score metrics


