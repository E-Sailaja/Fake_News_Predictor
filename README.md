# Fake_News_Predictor
This project focuses on building a machine learning model to classify news articles as real or fake using a logistic regression algorithm. It includes data preprocessing, stemming, TF-IDF vectorization, and model evaluation. The main goal is to use natural language processing (NLP) techniques to identify potentially misleading news content.


## Dataset
- Contains columns: id, title, author, text, and label
- label: 1 = Fake, 0 = Real

## Steps
1. Data loading and preprocessing
2. Stemming and stopword removal
3. TF-IDF vectorization
4. Model training (Logistic Regression)
5. Accuracy evaluation

## Results
Achieved a good accuracy score on the validation set. The model performs well on detecting fake news based on text content.

## Future Improvements
- Add deep learning models like LSTM or BERT
- Use more features like publication date or source credibility
- Improve text cleaning using lemmatization
