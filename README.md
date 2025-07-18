# NLP-Review-Analysis

**1.Project Title:**
IMDB Movie Review Sentiment Analysis with Logistic Regression

**2.Project Description:**
I constructed a sentiment analysis model that labels IMDB movie reviews as positive or negative based on Logistic Regression. The primary goal was to use Natural Language Processing (NLP) techniques to preprocess raw text data and create an interpretable and cost-effective machine learning model.

**3.Text Preprocessing Steps:**
To get the data ready for modeling, I carried out the following preprocessing steps:
Contraction Handling: Utilized the contractions library to expand contracted words (e.g., "didn't" → "did not") to enhance tokenization.
Lowercasing & Cleaning: Changed all the text to lowercase and stripped off punctuation, digits, and special characters using regular expressions.
Tokenization and Lemmatization: Used SpaCy to tokenize the reviews and lemmatize each word to its base form, which aids in dimensionality reduction.
Stopword Elimination: Removed frequent but uninformative words (such as "the", "is", "and") from the dataset using SpaCy's stopword vocabulary.

**4.Feature Engineering:**
Vectorized the preprocessed text data using TF-IDF (Term Frequency–Inverse Document Frequency) to transform it into a numerical representation that can be used by machine learning algorithms. This method assigns greater weight to unique words and reduces the weightage of frequent words.

**5.Model Training:**
A Logistic Regression model was trained on vectorized data. Training and test sets were used to split the dataset to measure generalization performance. Logistic Regression was used due to its simplicity, ease of interpretation, and suitability for binary classification problems.

**6.Model Evaluation:**
Model performance was measured using:
Accuracy score on test data
Confusion matrix to identify true vs. false predictions
Classification report with precision, recall, and F1-score
These measures assisted in assessing how well the model was able to differentiate between positive and negative reviews.

**7.Result:**
The model had a decent accuracy, proving that Logistic Regression, when accompanied with effective text preprocessing and TF-IDF features, can be effective in sentiment analysis tasks. The project assisted in solidifying my knowledge of text preprocessing pipelines, SpaCy, and logistic regression in NLP.
