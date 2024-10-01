# Medical Document Summarization Using TextRank Algorithm

## Project Description

Medical documents often contain extensive information that can be challenging to process efficiently. This project proposes a method for summarizing medical documents using the **TextRank algorithm**, a graph-based ranking algorithm commonly used in natural language processing (NLP). The TextRank algorithm is applied to medical documents to extract key sentences and phrases, which are then used to generate concise summaries.

The effectiveness of the proposed method is evaluated using standard metrics for text summarization, such as **ROUGE scores**, on a diverse set of medical documents. The outcomes of this project have the potential to streamline the process of extracting essential information from medical texts, aiding healthcare professionals in decision-making processes and improving overall efficiency in healthcare settings.

## Features

- Extracts key sentences and phrases from medical documents
- Generates concise summaries
- Evaluate the performance using ROUGE metrics

## Dependencies

The project primarily uses Python, and the following libraries are required:

- `numpy`
- `pandas`
- `nltk`
- `re`
- `sklearn`
- `networkx`
- `rouge_score`

## Data Files Required

The GloVe embeddings were trained on various large corpora, including Wikipedia and Gigaword. The "300d" represents that each word is embedded into a 300-dimensional vector. It is commonly used in NLP tasks, such as text summarization, sentiment analysis, and machine translation, to convert words into a format that machine learning models can understand. The significance of this file in this project is to compare the words in medical documents and remove stopwords. The dataset can be found here : https://www.kaggle.com/datasets/thanakomsn/glove6b300dtxt
