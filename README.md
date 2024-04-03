# Movie-Genre-Classification
This project aims to develop a machine learning model (Logistic Regression &amp; Decision Tree) to classify songs into genres (Hip-Hop and Rock) accurately. The system will analyze audio features such as danceability, energy, acoustic Ness, tempo, etc. and metadata to categorize songs into predefined genres.

Using a dataset comprised of songs of two music genres, I will train a classifier to distinguish between the two genres based only on track information derived from Echonest (now part of Spotify). I will first make use of pandas and seaborn packages in Python for sub setting the data, aggregating information, and creating plots when exploring the data for obvious trends or factors I should be aware of when doing machine learning.

Next, I will use the scikit-learn package (It’s an open-source python library that that features various classification, regression, clustering, and dimensionality reduction algorithms.) to predict whether I can correctly classify a song's genre based on features. I will go over implementations of common algorithms such as PCA, logistic regression, decision trees, and so forth.

# Model Evaluations

Decision Tree: 
               precision    recall  f1-score   support

     Hip-Hop       0.82      0.77      0.79       230
        Rock       0.78      0.82      0.80       225

    accuracy                           0.80       455
   macro avg       0.80      0.80      0.80       455
weighted avg       0.80      0.80      0.80       455

Logistic Regression: 
               precision    recall  f1-score   support

     Hip-Hop       0.84      0.80      0.82       230
        Rock       0.81      0.85      0.83       225

    accuracy                           0.82       455
   macro avg       0.82      0.82      0.82       455
weighted avg       0.83      0.82      0.82       455
