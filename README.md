# SI650-Incentivized-Product-Review-Detection
NLP Course Final Project @ University of Michigan
## Overview
As people have increasingly relied on online product reviews to make purchasing decisions nowadays, the problem of companies using incentivized reviews to boost brand exposures have continued to rise, especially in the beauty product industry. For this project, we will be performing text classification to identify incentivized product reviews from Sephora by using neural network models such as BERT and LSTM, as well as other fundamental linear models like Naive Bayes, SVM, and Logistic Regression.
## Data Collection 
One of the beauty product websites that is well known for having mass amounts of incentivized reviews is Sephora, which led to continuous complaints and discussions from customers over the years. To tackle this problem, the Sephora website recently introduced new features such as marking reviews as “Incentivized” or as “Verified Purchase” when specific standards are met. Given this feature, we are able to utilize these tags as our labels for categorizing the reviews. We scraped data from the Sephora website using BeautifulSoup, and obatined reviews of over 1,000 skincare products with 184,638 reviews in total. Up to 101,261 reviews in this dataset were neither marked as incentivized nor marked as verified purchases on the Sephora website. In order to accurately classify reviews as incentivized and non-incentivized, only reviews that are marked incentivized and non-verified purchases were considered as “Incentivized Reviews”. On the other hand, reviews that are marked as verified purchases and have no incentivized tags were considered as “Non-incentivized Reviews”. As such, our dataset used for actual training only consisted of 66,032 (79.5 %) incentivized reviews and 16,928 (20.5 %) non-incentivized reviews
## Methods
### 1. Statistical Linear Models
### 2. Biderectional LSTM
### 3. BERT MiniLM
