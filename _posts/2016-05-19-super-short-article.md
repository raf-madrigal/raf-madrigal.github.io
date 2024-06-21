---
layout: post
title: "Analyzing the Philippine Government’s COVID-19 Response: A Data-Driven Perspective"
categories: misc
---

#Title
Analyzing the Philippine Government’s COVID-19 Response: A Data-Driven Perspective

#Headline/ Summary
A Clustering Analysis of President Duterte’s Weekly Programs Reveals the Philippine Government's Focus and Challenges During the COVID-19 Pandemic

#Background
Since the outbreak of COVID-19 in Wuhan in November 2019, the world has faced unprecedented health and economic challenges. The Philippines, under President Duterte, implemented one of the world's longest lockdowns starting March 16, 2020, to curb the virus's spread. Despite these efforts, the pandemic continued to strain the country's healthcare system and economy. This study leverages a data-driven approach to analyze President Duterte’s weekly broadcasts, aiming to uncover the government’s priorities and response effectiveness during the pandemic.

#Business Challenge
The primary challenge for the Philippine government was managing the dual crises of public health and economic stability. The pandemic led to a sharp GDP contraction and overwhelmed healthcare facilities. The study aimed to discern if the government’s communications and actions effectively addressed these critical issues by analyzing the content of the President’s weekly programs.

#Goals
- Analyze the content of President Duterte’s weekly programs to identify key topics and trends.
- Understand the government's response priorities during the COVID-19 pandemic.
- Assess the alignment of government communication with public health and economic needs.
- Identify areas of improvement and potential gaps in the government's pandemic response.

#Solutions

The analysis followed a systematic approach using various data science techniques:

- Data Collection: Extracted 24 transcripts from the Presidential Communications Operations Office (PCOO), spanning from March 24 to August 11, 2020.
- Data Cleaning and Preprocessing: Removed stop words, lowercased text, vectorized words, and applied TF-IDF to evaluate word importance.
- Dimensionality Reduction: Employed truncated Singular Value Decomposition (SVD) to reduce data dimensionality.
- Clustering Analysis: Implemented k-means and agglomerative clustering to categorize the data into thematic groups.
- The key findings from the clustering analysis indicated frequent mentions of COVID-19, quarantine, and healthcare systems. Discussions consistently centered on health systems, quarantine enforcement, and government assurances, while economic plans were less emphasized.

#Conclusion
The clustering analysis of President Duterte’s weekly programs revealed that the Philippine government maintained a strong focus on health measures and quarantine enforcement throughout the pandemic. Despite governance and budget allocation challenges, the broadcasts served as a crucial platform for addressing public concerns. However, the initiatives did not significantly curb the rise in COVID-19 cases, suggesting a need for adopting more effective strategies from other countries. Transparent and relevant communication remained vital for public reassurance during the crisis.

#Tools
- Python: For data cleaning, processing, and clustering analysis.
- TF-IDF (Term Frequency-Inverse Document Frequency): To evaluate the importance of words in the transcripts.
- Truncated SVD (Singular Value Decomposition): For dimensionality reduction.
- k-Means and Agglomerative Clustering: To identify and categorize thematic clusters within the data.
- Data Visualization Tools: For presenting the findings in an understandable format.
