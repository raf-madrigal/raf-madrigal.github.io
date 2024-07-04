---
layout: post
title: "HMM…INTENSE! Analyzing Emotion Distribution in News Articles Using Rappler’s Crowd-Annotated Mood Metrics"
categories: post
---

<!-- ### Title
HMM…INTENSE! Analyzing Emotion Distribution in News Articles Using Rappler’s Crowd-Annotated Mood Metrics -->

### Summary
A Comprehensive Machine Learning Approach to Understand Reader Emotions in News Articles Through Rappler's Mood Metrics

### Background
In recent years, there has been a significant shift towards consuming news on smartphones, especially among younger generations. This trend has not only changed how news is accessed but also highlighted the importance of emotions in news consumption. Emotions play a crucial role in decision-making and influence what content spreads fastest on social media. Recognizing this, Rappler, a prominent Philippine news website, developed a mood meter allowing readers to annotate their emotional responses to articles. This study leverages machine learning to analyze these emotions, providing deeper insights into how news impacts readers.

### Business Challenge
News articles often evoke complex emotions that go beyond mere factual reporting. Previous studies have largely focused on sentiment polarity (positive, negative, neutral) and basic emotion classification. However, they have not sufficiently explored the intensity and distribution of these emotions. The challenge lies in accurately recognizing and categorizing the variety of emotions readers experience, which is crucial for news agencies, marketers, and content creators to enhance engagement and impact.

### Goals
- Identify and analyze the distribution of emotions evoked by news articles.
- Develop a model to classify and predict the intensity of these emotions.
- Enhance understanding of how different topics and writing styles affect reader emotions.
- Provide actionable insights for improving content creation and reader engagement.

### Solutions
- Data Collection and Exploratory Analysis: Collected over 17,000 news articles from Rappler, spanning from August 2019 to July 2020.
Conducted initial data cleaning and preprocessing, including the removal of stop words, punctuation, and irrelevant metadata.
- Text Preprocessing and Vectorization: Applied Word2Vec for word embeddings, converting text into numerical vectors for machine learning models. Used techniques like lowercasing and lemmatization to standardize the text data.
- Data Balancing: Employed Synthetic Minority Over-sampling Technique (SMOTE) to address class imbalances in the dataset, ensuring a more robust model training process.
- Model Training and Hyperparameter Tuning: Trained various machine learning models, including ensemble trees, to classify emotions with their respective intensities. Conducted hyperparameter tuning to optimize model performance.
- Evaluation and Results: Evaluated models using F1 scores, ensuring a balance between precision and recall. Ensemble trees yielded the best performance, significantly outperforming benchmark dummy classifiers in emotion classification tasks.

### Conclusion
The study successfully developed a robust method for recognizing and classifying the intensity of emotions in news articles. By leveraging Rappler’s crowd-annotated mood metrics and advanced machine learning techniques, the model provides valuable insights into reader emotions. This approach can help news agencies tailor their content more effectively, enhancing reader engagement and impact. Future work can explore the use of advanced NLP and deep learning models for even finer emotion classification.

### Tools
- Python: For data preprocessing, model training, and analysis.
- Word2Vec: For text vectorization and word embeddings.
- SMOTE: For balancing the dataset.
- Ensemble Trees: For classification models.
- F1 Score: For model evaluation.