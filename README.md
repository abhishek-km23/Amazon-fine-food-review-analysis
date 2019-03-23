# Amazon-fine-food-review-analysis
Performed Exploratory Data Analysis, Data Cleaning, Data Visualization and Text Featurization(BOW, tfidf, Avg-Word2Vec and tfidf-W-W2V). Build several ML models like KNN, Naive Bayes, Logistic Regression, SVM, Random Forest &amp; GBDT, Decision Trees, K-Means, Agglomerative &amp; DBSCAN Clustering,   The purpose of this analysis is to make up a prediction model where we will be able to predict whether a recommendation is positive or negative. In this analysis, we will not focus on the Score, but only the positive/negative sentiment of the recommendation.

Data includes:
Reviews from Oct 1999 - Oct 2012
568,454 reviews
256,059 users
74,258 products
260 users with > 50 reviews

Attribute Information:
Id
ProductId - unique identifier for the product
UserId - unqiue identifier for the user
ProfileName
HelpfulnessNumerator - number of users who found the review helpful
HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
Score - rating between 1 and 5
Time - timestamp for the review
Summary - brief summary of the review
Text - text of the review

Results of different applied models can be noticed in each corresponding file.
