# Natural-Language-Processing

Political Preference Analysis on Campaign  related Social Media Texts 

There are lots of applications of text classification in the commercial world. This project is aimed to classify a given speech according to a tweet post to identify the author who support democratic party or republican party. Our group is mostly using Jupyter Notebook and python to develop the system binary classification problem, relying on Scikit-Learn for building the machine learning components.

## Procedure

Crawled tweets of the Democratic, Republicans, and non-party people, filtering images & links, and manually tagging them

Conducted in-depth pre-text processing, including emoji character removal, case conversion and word embedding vector
extraction

Shuffled and divided the preprocessed text proportionally into training set and prediction set. Called tf-idf algorithm to
calculate the importance of words

Used different models for training and tuning, such as naive bayes, K closest, SVM, random forest and MLP
