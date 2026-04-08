# Twitter Sentiment Analysis

This project demonstrates a sentiment analysis system for Twitter data. 
It classifies tweets as **positive, negative, or neutral** and visualizes the overall sentiment distribution.

## Objective
The goal of this project is to showcase a machine learning pipeline for sentiment analysis using social media data. 
It provides insights into public opinion on specific topics.

## Dataset
- A sample dataset of tweets is included (`twitter_training.csv`).  
- The dataset was freely available online for demonstration purposes.  
- The dataset has been preprocessed (cleaned) to remove unnecessary characters, links, and emojis.

## Data Cleaning & Preprocessing
- **Two-step cleaning process**:
  1. **Initial cleaning:** removal of special characters, links, emojis, and unnecessary spaces  
  2. **Second pass:** ensures any remaining unwanted characters or noise are removed  
- Tokenization and normalization  
- Creation of a `cleaned_dataset.csv` ready for sentiment analysis  

## Model & Analysis
- Sentiment classification using Python libraries  
- Tweets are categorized as **positive, negative, or neutral**  
- Classification output includes percentages of positive, negative, and neutral tweets  
- Visualization of sentiment distribution using Matplotlib  

## Tools & Libraries
- Python  
- Tweepy  
- re  
- Pandas  
- NumPy  
- Matplotlib  
- scikit-learn (`feature_extraction`, `model_selection`, `tree`, `metrics`)  
- csv  

## How to Run
1. Clone the repository  
2. Open `Twitter_Sentiment_Analysis.ipynb` in Jupyter Notebook or Google Colab  
3. Run the notebook step by step to see analysis and visualizations  
4. Ensure required libraries from `requirements.txt` are installed  

> Optional: For those interested in data cleaning, the code to clean the raw dataset is provided in the notebook. 
> You can use it to preprocess the data yourself.  

## Notes
- **No API tokens are included** for security reasons.  
- Full dataset preview may not be available on GitHub; use Python to load the CSV for analysis.
