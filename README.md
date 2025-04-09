# OIBSIP_LEVEL1_TASK-4
A Sentiment Analysis project on Twitter data using NLP techniques to classify tweets as Positive, Negative, or Neutral.


Project_Overview

Social media platforms like Twitter generate massive amounts of user-generated content daily. Analyzing this data provides valuable insights into public opinion, customer feedback, and trends.


Project Objective

- To clean and preprocess raw Twitter data.
- To extract useful features from the text data.
- To build and evaluate a machine learning model that classifies tweets into:
    -> Positive
    -> Negative
    -> Neutral
 - To visualize sentiment distribution and insights.


Tech Stack Used
- Programming Language: Python
- Libraries & Tools:
- Pandas
- NumPy
- NLTK (Natural Language Toolkit)
- Matplotlib
- Seaborn
- Scikit-learn (Machine Learning)
- Jupyter Notebook


Dataset Description
The dataset used for this project contains:
 - clean_text: Pre-cleaned tweets from users.
 - category: Sentiment label for each tweet (Positive / Negative / Neutral).


Data Preprocessing
Performed the following preprocessing steps:
- Converted text to lowercase.
-> Removed:
   - Numbers
   - Special characters
   - Punctuation
   - URLs and mentions
   - Removed stop words using NLTK.
   - Performed Lemmatization using WordNet Lemmatizer to convert words to their base form.

 
Model Building
- Feature Extraction Techniques:
   -> Count Vectorizer
   -> TF-IDF Vectorizer

- Machine Learning Model Used:
   -> Logistic Regression (Best Accuracy Achieved)


Results and Visualization
 - Tweets successfully classified into Positive, Negative, and Neutral categories.
 - Visualizations Created:
    -> Sentiment Distribution Bar Chart
    -> Word Cloud for frequently used words
    -> Count Plot for sentiment comparison


Conclusion
This project demonstrates the application of NLP and Machine Learning techniques to extract sentiments from text data. It provides valuable insights into public opinion and can be extended to real-time systems for businesses and organizations.
