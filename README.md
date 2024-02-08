
## Project Name: FindYourStocks - Stock Recommendation System**

**Developers:** Leisha Murthy and Rohan Bhalla

## Problem to Solve:
Provide investing beginners with a convenient way of looking up companies (stocks) to invest in based on their interests and preferences, taking into account industries and stock performance.

## Statistical Methods and Machine Learning Algorithms Used:
- **Content-Based Filtering Approach**: Utilized statistical methods like CountVectorizer and machine learning algorithms such as cosine similarity.
- **CountVectorizer**: Converted textual stock data into a numerical representation for easy processing.
- **Cosine Similarity**: Measured the similarity between stocks based on their content, helping recommend the most similar stocks to users.
- **Model Evaluation**: Employed quantitative methods like cross-validation and performance metrics, alongside qualitative checks against industry data sites to validate predictions.

## Other Potential Models Considered:
- **TF-IDF**: Was evaluated but not chosen due to dataset limitations.
- **Linear Approach with Direct Comparison**: Rejected for not addressing dataset nuances effectively.

## Business Applications:
- **Personal Investment Firms and Financial Advisors**: Can use the model to offer personalized stock recommendations to clients, improving investment decisions and returns.
- **Individual Investors**: Can leverage the model to identify and evaluate potential investments based on their preferences and interests.
- **Insight into Investor Sentiment**: The model can offer insights into investor sentiment, aiding various business decisions.

## Possible System Extensions:
- **Recommendations Beyond S&P 500**: The system's framework can be adapted to recommend stocks outside of the S&P 500.
- **Extended Dataframes for Different Timeframes**: Addition of dataframes for 3-year, 5-year, and 10-year stock trend data with averages and percent change information, aiding in recommending stocks based on users' short-term or long-term investment strategies.
