# Tweet Binary Classification Using Naive bayes Classifier 


#### Author:  - <a href="https://github.com/WailBouhadda">Wail Bouhadda</a>

## Table of Contents

- [Project Overview](#project-overview)
- [Data Preprocessing](#data-preprocessing)
- [Feature Extraction](#feature-extraction)
- [Model Training](#model-training)
- [Data Visualization](#data-visualization)
- [Model Evaluation](#model-evaluation)
- [Confusion Matrix and ROC Curve](#confusion-matrix-and-roc-curve)
- [Testing on Real Data](#testing-on-real-data)
- [Future Directions](#future-directions)

## Project Overview

The Tweet Binary Classification project focuses on binary classification of tweets into two categories: "sports" and "politics." It encompasses various data preprocessing techniques, feature extraction, model training, data visualization, and performance evaluation.

  ![df](https://github.com/WailBouhadda/Tweet-Binary-Classification-Using-Naive-bayes-Classifier/assets/47559086/e04e1ed7-62db-49fa-aa1b-215afae6a81e)


## Data Preprocessing

- Lowercasing: Ensured text consistency by converting text to lowercase.
- Punctuation Removal: Eliminated unnecessary punctuation and special characters.
- Tokenization: Split text into words.
- Stop Words Removal: Removed common stop words.
- Lemmatization: Reduced words to their root forms.

## Feature Extraction

Feature extraction in the  project was carried out using the Bag of Words (BoW) method. BoW is a commonly used technique for text classification that represents text data as a matrix of word frequencies.

Bag of Words (BoW): Selected as the feature extraction method. BoW converts text data into a matrix where each row represents a document (tweet) and each column represents a unique word in the dataset. The matrix entries indicate the frequency of each word's occurrence in the corresponding document.

This BoW representation allowed the model to work with numerical data, facilitating the binary classification task of categorizing tweets into "sports" and "politics."

## Model Training

- Multinomial Naive Bayes: Chosen for its simplicity and reliable performance.
- Performance Metrics: Evaluated the model using accuracy, precision, recall, F1-score, and ROC AUC.
  

## Data Visualization

- Class Distribution: Visualized the distribution of tweets in "sports" and "politics" categories.

  ![barchart](https://github.com/WailBouhadda/Tweet-Binary-Classification-Using-Naive-bayes-Classifier/assets/47559086/6990fa16-acb0-470b-b84a-8a8d59060ec7)

- Top 10 Words: Identified and displayed the top 10 most frequently used words.

  ![wordscount](https://github.com/WailBouhadda/Tweet-Binary-Classification-Using-Naive-bayes-Classifier/assets/47559086/d4df4cdb-8393-42e5-9158-f1c6e0242309)


## Model Evaluation

The model's performance metrics, including accuracy, precision, recall, F1-score, and ROC AUC, were assessed.

  ![metrics](https://github.com/WailBouhadda/Tweet-Binary-Classification-Using-Naive-bayes-Classifier/assets/47559086/c25b7d8a-853d-4bc2-ab37-7523f44fbffc)

## Confusion Matrix and ROC Curve

The confusion matrix and ROC curve provided insights into the model's performance.

The confusion matrix provided insights into the model's true positives, true negatives, false positives, and false negatives. 

  ![confusionmatrix](https://github.com/WailBouhadda/Tweet-Binary-Classification-Using-Naive-bayes-Classifier/assets/47559086/a6fb76a4-84a9-42ca-9af2-c95ca47df66c)

Additionally, the ROC curve depicted the model's performance in terms of the true positive rate and false positive rate across various thresholds.

  ![ROC curve](https://github.com/WailBouhadda/Tweet-Binary-Classification-Using-Naive-bayes-Classifier/assets/47559086/da080f9d-482c-406d-88b0-edd3399efb47)


## Testing on Real Data

The project extended beyond model evaluation by applying the trained model to real-world data for practical use.

  ![test1](https://github.com/WailBouhadda/Tweet-Binary-Classification-Using-Naive-bayes-Classifier/assets/47559086/9cc0b8b9-bdcb-47c7-9a37-ac17a2c057ae)

  ![test2](https://github.com/WailBouhadda/Tweet-Binary-Classification-Using-Naive-bayes-Classifier/assets/47559086/94f86dfd-4ba1-4666-873b-27613538393e)


## Future Directions

Future work may involve refining the model, exploring alternative classification algorithms, and expanding the project's scope to accommodate more classes and data sources.



