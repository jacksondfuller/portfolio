# Jackson Fuller Portfolio

## [Menstruation Twitter Topic Modeling and Sentiment Analysis](https://github.com/LoveYourMenses/twitter-attitudes/)
Objective: To understand key topics and themes, and prevailing sentiments of menstruation related conversations on Twitter
- Scraped tweets by keyword from Twitter using snscrape
- Processed tweets using NLP techniques including tokenization and lemmatization
- Fit Short Text Topic Modeling (STTM) algorithm to tweets with k=5 to create clusters of tweets with common topic categories
- Employed VADER sentiment analysis tool to analyze polarity of tweets by respective topic

![](/images/wordcloud_menstruation.jpeg)

## [Marketing Customer Segmentation](https://github.com/jacksondfuller/customer_segmentation)
Objective: To identify distinct segments in the current customer base in order to target future marketing campaigns
- Processed and cleaned dataset, explored outliers and correlations between variables
- Reduced dimensionality using principal component analysis (PCA)
- Used Sum of Squared Error (SSE) to determine optimal K value
- Built and compared K-means, Gaussian Mixture (GMM), and K-medoids models to investigate cluster profiles of customers

![](/images/kmeans_segments.jpeg)

## [Retail Sales Forecasting](https://github.com/jacksondfuller/retail_sales)
Objective: To build a model that accurately forecasts retail sales using the past quarter’s data
- Processed data, investigating distributions and correlations of variables
- Checked for multicollinearity, and checked assumptions for linear regression
- Tuned ordinary least squares model accounting for insignificant variables
- Applied cross-validation and used r squared and mean squared error to evaluate models

![](/images/corr_sales.jpeg)

## [Loan Default Predictor](https://github.com/jacksondfuller/loan_default)
Objective: To build a classification model to best predict when customers of a bank will default on a loan
- Built and compared models using linear discriminant analysis (LDA), quadratic discriminant analysis (QDA), logistic regression, and K-nearest neighbors (KNN)
- Compared all models using only balance as a feature vs using all features

![](/images/knn_loan.png)
