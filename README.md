# Capstone_2
Classifying Hate Speech on Twitter using NLP and Stacked ML

The goal of this project is to develop a classifer capable of serving as a Hate Speech filter for a social media company.  The idea for this project can be found in the "Initial Proposal" document in the Reports folder.

To acheive this, over 30,000 tweets will be made into training and test data, various NLP features are developed, ML models are trained, and a stacked model is generated to provide high predictive power.

The organization is as follows:

The files containing raw data from Vidhya Analytics can be found in the csv_and_npz_files folder and are labeled "train_E6oV3lV" and "test_tweets_anuFYb8."

They are read to csv, cleaned, normalized, and tokenized in the "Data Preprocessing" notebook, the "processed_tweets" csv is then exported to the csv_and_npz_files folder.

This file is read into the EDA, where it is explored.

This file is also reasd into the ML Preprocessing notebook where the tokens are converted to features via Bag of Words, TFIDF, Word to Vector, and Doc to Vector Methods.  The results are again stored in the csv_and_npz_files folder.

The respective files are loaded into the ML and Stacking notebook, where ML analysis is applied.

Proposal, Interim and Final Reports can be found in the Reports folder.

A special thanks to my professional mentor at Springboard, Mr. Kenneth Gil-Pasquel

