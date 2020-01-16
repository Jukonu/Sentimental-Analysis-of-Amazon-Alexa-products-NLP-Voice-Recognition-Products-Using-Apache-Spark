Sentimental Analysis of Amazon Alexa products
(on Voice Recognition/Natural Language Processing)
This project tends to address the problem "Betterment required in the Amazon Alexa products on Voice Recognition/Natural Language Processing".

This Dataset is a collection of Amazon customer reviews for Alexa Echo, Firestick, Echo Dot etc.and will be retrieved from the Kaggle website (Extracted from Amazon's website).

It is comprised of 3150 Amazon customer reviews for Alexa Echo, Firestick, Echo Dot, etc. sized at 503KB. The dataset consists of columns that show details like the star ratings, date of reviews posted, variants of Amazon Alexa products and feedbacks about the different Alexa products.

This study tends to analyze Amazon’s Alexa products; to predict feedback views on the Amazon Alexa products using text, variation, and feedbacks. Train machine models for sentiment analysis and analyze customer reviews by showing distributions of positive reviews as well as negative reviews. Also, it will display some exploratory data analysis that will reveal distributions of unique variations contained in the dataset. Models to be used will be Text classification, Random Forest and Gradient Boosting.

Train a number of different models on the training set and evaluate each one on the validation set to see which model generalizes best to the unseen data. The test set will be used to provide an unbiased evaluation of the tuned model. The test set is used only once to evaluate the final model. Upon which decision can be made to choose which model provides optimal feedbacks.
Models employed were weighted Loss Logistic Regression upon up-sampling the imbalanced dataset. 

Second and third models employed are random forest and GBT upon splitting the DataFrame into testing and training data set and up-sampling the training the dataset and fitting the pipeline on the up-sampled dataset.

The five columns in the dataset are – ratings, date, variation, verified_reviews, feedback. I initiated the steps below:
1.	Exploratory Analysis
2.	Feature Engineering
i.	STOPWORDS Removal
ii.	Stemming
iii.	Punctuation removal
iv.	Indexing
v.	OneHotEncoding
vi.	TFIDF

3.	Up-sampling imbalanced data for minority class
i.	Up-sampling for Weighted Logistic Regression
ii.	Up-sampling for Random Forest and GBT Classifiers
4.	Models employed:
i.	Weighted Logistic Regression
ii.	Random Forest
iii.	Gradient Boosting Tree
5.	Evaluation Metrics-
i.	Area Under Curve(AUC)
ii.	Probability

Obviously, outputs show that value of AUC proves that GBT classifier performed better then random forest tree classifier and weighted Logistic regression in predicting the values and that our model is highly prolific for usage in predicting feedback for users. It is pertinent that, from this data view we can say that there needs to be quite plenty of improvement in the sound systems sold to customer by Amazon.

