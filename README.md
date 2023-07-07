# Sentiment Analysis on Airline Reviews

**NOTE**: This is an ongoing project, and all the files in this repository will be updated as the project proceeds!

✈ This project performs sentiment analysis on a dataset of airline reviews over two decades. The project aims to understand the overall sentiment of the reviews and see if any interesting patterns or insights can be drawn.

### Dataset💾
The dataset used for this project comprises reviews of various airlines. It is publicly available on Kaggle ([here](https://www.kaggle.com/datasets/joelljungstrom/128k-airline-reviews))
It contains multiple columns with information about the review, such as the reviewer's nationality, the review date, the airline, the type of cabin traveled in, the overall rating, and the review text.

## Methodology
**1. Data Cleaning, Preprocessing, and EDA**<br>
I conducted preliminary data exploration to understand the dataset, cleaned the dataset to improve the data quality, and performed exploratory data analysis.
Along the way, I created several visualizations, including bar plots and a heatmap, to grasp patterns and gain valuable insights.
A draft of this part is also on Kaggle ([here](https://www.kaggle.com/code/treelunar/airline-review-analysis-part-1-eda))

**2. Initial Sentiment Analysis Using VADER**<br>
The first approach to sentiment analysis in this project uses the VADER sentiment analysis tool, specifically designed for social media and works well with short, informal texts.
VADER is known for working well for analyzing short texts with subtle emotions.
Despite its efficiency and easiness to use, VADER is not equipped to capture nuances and contexts. Nonetheless, it provides a good starting point for understanding the sentiment expressed in our airline reviews.

**3. Advanced Sentiment Analysis Using RoBERTa**<br>
After the initial analysis with VADER, a more advanced sentiment analysis is performed using the RoBERTa model, a variant of the BERT model optimized for more robust performance. The RoBERTa model provides a deep learning approach to sentiment analysis, and it can understand complex, subtle sentiment and context better than VADER.
The RoBERTa model is used to create embeddings for the reviews, which are then saved and can be used for further analysis.

**4. Regression Models**<br>
- More to come!
  
**5. Conclusion**
