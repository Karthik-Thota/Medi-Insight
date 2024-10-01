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
