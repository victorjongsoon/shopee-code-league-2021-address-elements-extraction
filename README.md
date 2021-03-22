# Shopee Code League 2021 - Address Elements Extraction (Competition 2 - Data Science)
This is the source code for 2nd competition (data science) of the Shopee Code League 2021. We came in 90th out of 1034 participating teams (Open and Student) with an accuracy of **61.222%**. This competition has been a great experience for me. I am glad to see how well we can do in a high pressure situation given limited amount of time. Although we did not came in first, I am happy to work with a great team and accomplish our goals.

# Dataset
The dataset is downlaoded from Kaggle (https://www.kaggle.com/c/scl-2021-ds/data).

# Task (extracted from tasksheet pdf)
In this competition, you’ll work on addresses collected by us to build a model to correctly extract
Point of Interest (POI) Names and Street Names from unformatted Indonesia addresses.
Participants are expected to build their own model for this competition, submissions by teams
which directly call any third party APIs on the test set will not be taken into consideration.

# Approach
Our team's approach in this competition is to train the dataset (train.csv) using Named Entity Recognition (NER) using Spacy. We convert the dataset into json format so that it is "readable" for the model for training. After we have trained the model, we test the model accuracy with the testing file (test.csv).

# Accuracy: 61.222% - 90th/1034 in Private Leaderboard
![Image of Private Leaderboard](https://github.com/victorjongsoon/shopee-code-league-2021-address-elements-extraction/blob/main/images/private-leaderboard.PNG)
![Image of Participating Teams in Private Leaderboard](https://github.com/victorjongsoon/shopee-code-league-2021-address-elements-extraction/blob/main/images/private-leaderboard-total.PNG)

# Skillset required for the project (Machine Learning)
* Python (Numpy, Pandas etc.)
* NER - Spacy
