Problem and Motivation
- US public companies submit report regarding operational or financial change with corresponding label to Security exchange commision
- Companies sometimes misclassify concerning disclosure as label 8 (miscellaneous) while other more appropriate label exists
- Due to quantity of report, using natural language processing is practical alternative to manual review

- 3000 entries
- 16 labels
- Training Set : reports that aren’t labeled as miscellaneous

NLP algorithm
- Preprocess the data by deleting stop ward, stemming, lemmanizing and tokenizing the input
- Used bag of word approach with inverse frequency weight
- Predict using Multi-Nominal Naive Bayes

Prediction Result
- 91% Accuracy achieved using Porter Stemmer and Wordnet Lemmatizer
