# Task 3: Sentiment Analysis of Product Reviews

## Project Overview
This project analyzes customer reviews to determine sentiment (positive, neutral, negative) using both rule-based and machine learning approaches. The system can classify text and provide insights for business decision-making.

## Business Problem
Companies receive thousands of reviews but lack automated systems to:
1. Categorize feedback by sentiment
2. Identify common pain points
3. Track brand perception over time
4. Respond to negative feedback promptly

## Dataset
- **Type:** Customer product reviews
- **Size:** 20+ sample reviews (expandable to thousands)
- **Features:** Review text, rating (1-5), sentiment label
- **Source:** Synthetic dataset representing real-world reviews

## Methodology

### 1. Text Preprocessing
- Lowercasing, special character removal
- Stopword removal (preserving negation words)
- Tokenization and lemmatization
- Text cleaning pipeline

### 2. Sentiment Analysis Approaches
- **Rule-based:** TextBlob sentiment scoring
- **Machine Learning:** Naive Bayes & Logistic Regression
- **Feature Extraction:** Bag of Words & TF-IDF
- **Model Evaluation:** Accuracy, Confusion Matrix, Classification Report

### 3. Visualization
- Sentiment distribution charts
- Word clouds (positive vs negative)
- Model performance comparison
- Confusion matrix heatmaps

## Results

### Model Performance
- **Best Model:** Logistic Regression with TF-IDF
- **Accuracy:** 85.0% (on test set)
- **Improvement over TextBlob:** +15.0%

### Key Findings
1. Positive reviews often contain: "love", "excellent", "recommended", "quality"
2. Negative reviews often contain: "disappointed", "poor", "waste", "terrible"
3. Short reviews (<5 words) are hardest to classify accurately
4. Sarcasm and mixed sentiments remain challenging

### Business Insights
- **Top Positive Indicators:** quality, excellent, love, amazing, perfect
- **Top Negative Indicators:** disappointed, poor, waste, terrible, broken
- **Recommendation:** Focus on addressing negative feedback mentioning "quality" and "service"

## Files Included
1. `Sentiment_Analysis.ipynb` - Complete Jupyter notebook with analysis
2. `sentiment_analysis_results.csv` - Processed data with sentiment labels
3. `model_predictions.csv` - Model predictions on test data
4. `README.md` - This documentation file

## How to Run
1. Open `Sentiment_Analysis.ipynb` in Jupyter Notebook or Google Colab
2. Run all cells sequentially
3. Test with custom reviews using the interactive function
4. View visualizations and analysis results

## Technologies Used
- **Python 3.x**
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **NLP:** NLTK, TextBlob, scikit-learn
- **Visualization:** WordCloud, Seaborn heatmaps
- **Machine Learning:** Scikit-learn (Naive Bayes, Logistic Regression)

## Future Improvements
1. Implement deep learning (LSTM, BERT)
2. Add aspect-based sentiment analysis
3. Real-time sentiment monitoring dashboard
4. Multi-language support

## Author
[Your Name]

## Internship
Oasis Infobyte - Data Analytics Domain