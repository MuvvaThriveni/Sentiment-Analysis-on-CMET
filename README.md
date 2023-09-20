# Sentiment Analysis on Code-Mixed Data
# Introduction

This repository contains research work aimed at addressing the challenging task of sentiment analysis on code-mixed data. Code-mixing involves the interweaving of two or more languages within a single conversation or text, making sentiment analysis more complex and demanding.

# Objectives

Understand the Challenge: Analyze the complexities and nuances of sentiment analysis on code-mixed data.

Solve Existing Challenges: Provide solutions to current challenges using existing data and methods.

Future Work - Data Strategy: Develop efficient data strategies to enhance sentiment analysis accuracy and applicability.

# Research Paper

We have initiated a research paper to comprehensively address this task. The current progress includes solving a portion of the problem using existing data and techniques. The future work primarily focuses on refining data strategies to improve accuracy and robustness.

#  Methodology

### Data Preprocessing
We performed data preprocessing specific to code-mixed English-Telugu text, including:

### Normalization:
Normalized the data to counteract language variations, aiming to improve precision in sentiment analysis.

### Text Correction: 
Utilized the SymspellPy library for effective text correction, enhancing overall accuracy.

### Feature Engineering:
Feature engineering involves generating relevant features to enhance model performance. Given the complexity of code-mixed data, our feature engineering efforts were tailored to optimize sentiment analysis on this data type.

# Model Architectures

We employed various deep learning models to conduct sentiment analysis on the code-mixed English-Telugu text. The models used include:

### RNN (Recurrent Neural Network):
An initial attempt leveraging RNN to capture sequential dependencies in the code-mixed data.

### LSTM (Long Short-Term Memory):
Utilized LSTM to improve model understanding of long-term dependencies and nuances within the data.

### Bi-LSTM (Bidirectional LSTM):
Employed Bi-LSTM to capture information from both past and future inputs, enhancing context understanding.

### BERT (Bidirectional Encoder Representations from Transformers): 
Utilized the power of pre-trained BERT to analyze contextual embeddings and extract features from the code-mixed text.

### RoBERTa (A Robustly Optimized BERT Pretraining Approach):
Employed RoBERTa, a variant of BERT, for its robust pretraining approach and its potential in improving sentiment analysis.

### Evaluation Metrics
We evaluated the performance of the models using standard sentiment analysis metrics, including but not limited to:

### Accuracy: 
To measure the overall model performance.

### Precision:
To assess the ratio of true positive predictions to the total predicted positives.

### Recall:
To measure the ratio of true positive predictions to the total actual positives.

### F1-Score:
To evaluate the balance between precision and recall.

### Results
Evaluated the deep learning models with the following accuracy rates:

RNN: 74%

LSTM: 75%

Bi-LSTM: 76%

BERT: 80%

RoBERTa (using Simple Transformers): 80%

### Algorithms & Tools

We utilized the following algorithms and tools for our research:

Recurrent Neural Network (RNN)

Long Short-Term Memory (LSTM)

Bidirectional LSTM (Bi-LSTM)

BERT (Bidirectional Encoder Representations from Transformers)

RoBERTa (A Robustly Optimized BERT Pretraining Approach)

SymspellPy (for text correction)

Regex (for pattern matching and text processing)

# Future Work

### Enhancing Data Strategies for Improved Sentiment Analysis:
Our future work focuses on efficient data strategies to enhance sentiment analysis on code-mixed data, emphasizing:

### Data Collection and Labeling:
Gather diverse, high-quality code-mixed data.
Expert annotation for accurate sentiment labeling.

### Fine-Tuning Transformers:
Custom training and domain-specific tuning of pre-trained transformer models.

Currently working on future work.
