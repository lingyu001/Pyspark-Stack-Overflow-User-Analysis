# Pyspark-Stack-Overflow-User-Analysis

# Explore the Stack Overflow User Behavior and Predict Question Popularity
# Background:

Stack Overflow is a collaboratively edited question-and-answer site originally focused on programming topics. There are a variety of features tracked, including a variety of feedback metrics, such as:

Title
Favorite counts
View counts
Answer counts
Score
Question tag
etc.
The project focuses on the analysis of user behavior on the site. Stack Exchange provides anonymized data, and I used Spark to perform data manipulation, analysis, and machine learning on the post and user data set.

Data:
There are two sets of data used in the project: A small dataset for xml parsing and Spark pipeline test

108741 Posts
50320 User Accounts
The full dataset for exploratory analysis

Posts
User Accounts


## Analysis include:

1. Explorary Analysis: 
1). Post of high reputation users
2). Identify veterans and brief users - sample test data
3). Identify veterans and brief users - full data
4). Word2vec Model for synonyms similarity

2. Classification: 
predict the tags of a question from its body text. Instead of predicting specific tags, we try to predict if a question contains one of the top ten most common tags.
