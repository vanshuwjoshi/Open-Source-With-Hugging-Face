# Open-Source Models with HuggingFace

Welcome to my repository for the DeepLearning.AI course on [Open-Source Models using HuggingFace](https://www.deeplearning.ai/short-courses/open-source-models-hugging-face/)! This repository contains various projects I've completed, including conversational models, translation, summarization, and sentence embedding using sentence transformers.

## Projects

### Conversation Models

In this project, I implemented a conversational model using HuggingFace's `transformers` library. The model is capable of engaging in human-like conversations, providing responses to user inputs in a natural manner.

Key components:
- **Model:** facebook/blenderbot-400M-distill
- **Libraries:** `transformers`

### Translation

This project involves building a translation model that can translate text from one language to another. Using HuggingFace's pre-trained models, I created a translation pipeline that supports multiple language pairs.

Key components:
- **Model:** facebook/nllb-200-distilled-600M
- **Libraries:** `transformers`, `torch`

### Summarization

In the summarization project, I implemented a model to generate concise summaries from longer texts. This can be particularly useful for quickly understanding large documents or articles.

Key components:
- **Model:** facebook/bart-large-cnn
- **Libraries:** `transformers`

### Sentence Embedding

This project uses sentence transformers to generate embeddings for sentences, which can be used for various downstream tasks such as semantic similarity, clustering, and classification.

Key components:
- **Model:** sentence-transformers/all-MiniLM-L6-v2
- **Libraries:** `sentence-transformers`
