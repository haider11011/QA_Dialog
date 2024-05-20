# QA_Dialog
# Information Retrieval and Question Answering System

This project is an implementation of a Question Answering and Dialog System focused on information retrieval from a dataset of news articles. The system aims to provide users with accurate and relevant answers to their questions by extracting information from the articles.

## Table of Contents
- [Abstract](#abstract)
- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [System Architecture](#system-architecture)
- [Model Selection and Training](#model-selection-and-training)
- [User Interaction](#user-interaction)
- [System Evaluation](#system-evaluation)
- [Conclusion](#conclusion)
- [References](#references)

## Abstract
This project presents the development and evaluation of a Question Answering and Dialog System focused on information retrieval from a dataset of news articles. The primary objective is to implement a real-world solution for NLP tasks, specifically addressing the challenges of question-answering and dialogue systems within the context of news articles. The system uses state-of-the-art NLP models to provide accurate answers to user queries by extracting relevant information from the articles.

## Introduction
With advancements in Natural Language Processing (NLP) following the introduction of Google's BERT framework, our project aims to leverage these technologies to create an effective question-answering system. We adopted a transfer learning approach, using pre-trained language representations and fine-tuning them for news-based question-answering tasks.

## Data Preprocessing
Our preprocessing steps include:
- **Stopwords Removal:** Excluding common words that add little semantic value.
- **Tokenization:** Converting text to lowercase and splitting it into individual tokens.
- **Vectorization:** Transforming textual data into numerical form for efficient computation.

These steps help in cleaning and standardizing the dataset, making it ready for analysis and modeling.

## System Architecture
The system architecture involves several key components:
- Preprocessing of news articles.
- Indexing articles based on named entity recognition.
- Utilizing a BERT language model for question answering.
- Custom utilities for text matching, entity linking, and generating natural language responses.

## Model Selection and Training
We evaluated several state-of-the-art language models and selected BERT (Bidirectional Encoder Representations from Transformers) as the most suitable for our application due to its bidirectionality, unsupervised pre-training, and transformer architecture. We fine-tuned BERT on the Stanford Question Answering Dataset (SQuAD), achieving competitive performance metrics.

## User Interaction
Users can interact with the system by entering their questions in natural language. The system processes the questions, retrieves the most relevant articles, and provides answers along with confidence scores. The system maintains context and coherence in user interactions, making the experience conversational.

## System Evaluation
The system was tested with various user queries and performed well in providing accurate and relevant answers. It maintains context in conversations and adapts to different types of questions. However, there are opportunities for improvement, particularly in handling more complex or open-ended questions.

## Conclusion
This project successfully implemented an information retrieval and question-answering system for news articles. By integrating NLP techniques and fine-tuning a BERT model, the system provides accurate answers to user queries. Future work could focus on enhancing the system's ability to handle complex questions and expanding the dataset to cover a broader range of topics.

## References
For detailed references, please refer to the project report.

## Contributors
- Haider Ali Lokhand
- Paridhi Awadheshpratap Singh
- Chahat Segan

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
