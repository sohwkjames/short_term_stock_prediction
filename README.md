# short_term_stock_prediction
Implementing the research done at:

https://www.researchgate.net/publication/325786183_Predicting_Short-Term_Stock_Prices_using_Ensemble_Methods_and_Online_Data_Sources

### 1. What data to get?

(a) historical stock prices; 
(b) several well-known technical indicators; 
(c) counts and sentiment scores of published news articles for a given stock; 
(d) trends in Google searches for the given stock ticker;
(e) number of unique visitors for pertinent Wikipedia pages. 

### 2. Feature selection and model training process

Once the data is collected, we use a structured approach for data preparation. Then, the AI platform trains four machine learning ensemble methods: (a) a neural network regression ensemble; (b) a support vector regression ensemble; (c) a boosted regression tree; and (d) a random forest regression
