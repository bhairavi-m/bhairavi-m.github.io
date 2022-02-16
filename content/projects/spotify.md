---
title: "Session-based Skip Prediction: Spotify 🎹"
date: 2021-11-20
---
Spotify is a leading music service fuelled by its customization and music knowledge driven by algorithms to understand the way users sequentially interact with music. This project focussed on the task of session-based sequential skip prediction, i.e., predicting whether users will skip tracks, given their immediately preceding interactions in their listening session.

This project was an exciting supervised machine learning classification problem. It helped us understand intricate behavioral patterns of how users engage with tracks and which track features play an important role in prediction. It was done as part of a three-member team, and we came up with two approaches: feature-based classification using boosted trees and the second dealing with sequential modeling using RNNs. I primarily worked on setting up functions in Python (using Google Colab) that performed feature-based classification using algorithms like Random Forest Classifier, XGBoost Classifier, and Logistic Classifier. I discovered that the XGBoost classifier achieved the best validation scores across all evaluation metrics. I also preprocessed the data using PCA and conducted an error analysis for the extended models using RNNs. We individually went over all stages of the pipeline (preprocessing, feature engineering, modeling), which enabled ease of collaboration in the end and helped us iterate through different methods parallelly.

The main challenge for Spotify is to recommend the right music to each user. Hence, most of the work focuses on Recommender Systems and a little on describing how users sequentially interact with the streamed content they are presented. The outcome of our empirical analysis highlighted the importance of sequence in the prediction and how well the recommendation system is working. Our sequential modeling using RNNs increased the accuracy from 64% to 78%, and we are currently working on tuning the hyperparameters of this Char RNN model to generate more accurate results.


View the code -> [GitHub](https://github.com/bhairavi-m/Spotify-Sequential-Skip-Prediction)

Read the report -> [Google Drive](https://drive.google.com/file/d/1BQT-Utcb4O52bOcUdhZ3uln9xhe2022N/view)

#### Team
[Purva Sheth](https://www.linkedin.com/in/purva-sheth/) [Parth Sheth](https://www.linkedin.com/in/parthmsheth/) 