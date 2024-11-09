# British Airways Customer Insights Analysis

**Author:** Tram Nguyen  
**Date:** 27.08.2023

## Overview

This project focuses on web scraping and analyzing customer reviews of British Airways (BA) to uncover insights that could inform business strategies. The objective is to gather feedback, analyze sentiment, and highlight key areas for improvement.

## Project Objectives

- **Data Collection**: Scrape customer review data from a third-party source.
- **Analysis**: Perform text and sentiment analysis to gain insights into customer perceptions and areas for BA to improve.

## Tools and Libraries

- **Python**: Data scraping and analysis
- **BeautifulSoup**: Extracts review content
- **NLTK**: Text analysis and sentiment scoring
- **Jupyter Notebook**: Code execution and visualization

## Data Summary

- **Source**: BA customer reviews from a third-party site
- **Data File**: `BA_reviews.csv` containing 1,000 rows of customer feedback

## Analysis Techniques

1. **Word Frequency & Word Cloud**  
   Using NLTK, the most common words in customer reviews were extracted. A word cloud highlights frequently discussed topics such as "service," "flight," "staff," and "time."

2. **Sentiment Analysis**  
   Each review was scored on a negative, neutral, and positive scale using NLTK's `SentimentIntensityAnalyzer`. Key findings include:
   - **Positive Reviews**: 573
   - **Negative Reviews**: 421
   - **Neutral Reviews**: 6

   The distribution shows that customer feedback is generally polarized, with few neutral opinions. Positive feedback outnumbers negative, especially for verified trips.

3. **Score Distribution**  
   - Average sentiment score: **0.1643** (roughly 5.8 out of 10)
   - Distribution skewed slightly left, with a concentration of reviews in high or low ratings.

## Key Insights

- **Positive Aspects**: Customers frequently praise BA's service and staff.
- **Areas for Improvement**: The distribution suggests room for service enhancements to improve customer satisfaction further.
  
## Conclusion

The analysis reveals polarized feedback, with most customers holding strong positive or negative opinions. This suggests a significant opportunity for BA to address specific pain points and build on positive aspects to enhance overall customer satisfaction.

## Future Work

- **Expand Data Sources**: Incorporate additional review platforms.
- **Deeper Analysis**: Investigate specific themes within negative reviews.
- **Benchmarking**: Compare sentiment with competitors for broader insights.

---


 
