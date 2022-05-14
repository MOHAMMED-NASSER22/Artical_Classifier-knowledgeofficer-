# Artical_Classifier-knowledgeofficer-


<h3 align="left">Tools & Libraries :</h3>

- jupyter Notebook (python 3).
- seaborn for visualization
- NLTK for text processing.
- sklearn (Logistic Regression & Naive Bayes & LinearSVC).

<p align="left"> In this project, my goal was to make a text classification </p>

1. **Project Idea** : The project idea is recommending web articles for the learners during their learning journey. Those articles will be recommended for the different nano degrees. e.g. Machine learning, Product management, UI/UX Design ... etc..

2. **data exploration** : investigating the target and the feature for additional information and deciding how to clean and preprocess the data
- count the target values
- search for duplicates & empty fileds
- create Word Cloud for each category 

3. **Data Cleaning** : 
- Concat them into one csv file.
- Drop duplicates.
- remove the empty fileds.

Remove punctuation
Convert all texts to be in lower case.
Use nltk.tokenize for sentences tokenization.
Remove stopwords from the tokenized text.
Apply Lemmatization to the texts.

4. **Data Preprocessing**  : In this step, I have important processes to apply to my dataframe to be ready as an input for the model.
- Remove punctuation
- Convert all texts to be in lower case.
- Use nltk.tokenize for sentences tokenization.
- Remove stopwords from the tokenized text.
- Apply Lemmatization to the texts.
- Down sampling
- Save the final processed dataframe to be used in the next step of Model Training.

5. **Model Training** : The data was good enough to be fitted on the used models and the results was greatly satisfying with the classical ML using 
