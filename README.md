## Amazon Reviews Modeling

### Data Source
The analysis is based on the dataset: [Amazon Product Reviews](https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews).

###  Overview

1. **`amazon_reviews_exploration`**  
   Exploring reviews to identify patterns and clusters:
   - **EDA** exploration of review metadata, ratings and textual content;
   - **PCA** reduction of feature dimensions;
   - **Clustering** K-Means and HDBSCAN, calculating Silhouette Scores and Davies-Bouldin Scores;

2. **`amazon_reviews_sentiment_modeling`**  
   Sentiment analysis on Amazon product reviews:
   - **DistilBERT** Pretrained DistilBERT to identify score thresholds;   
   - **Custom DL Models:**  
     - An initial sequential LSTM model;
     - A more advanced architecture, incorporating convolutional layers, batch normalization and pooling;
   - **Product Sentiment Ranking:** Sentiment scores aggregated to calculate sentiment ranks for products;
     
