# Sentiment Analysis with GPT-3.5-turbo API

## Overview

This project leverages the GPT-3.5-turbo API to perform sentiment analysis tasks. It showcases both few-shot and zero-shot classification for sentiment analysis. Additionally, the project integrates text vectorization using the `text-embedding-ada-002` embedding model. This model generates embeddings, which serve as input features for a Random Forest classifier, for sentiment analysis.

## Usage

To use this project:

1. **Few-Shot Sentiment Analysis**: Utilize the GPT-3.5-turbo API for few-shot sentiment analysis. Provide a prompt containing the context and text for analysis.

2. **Zero-Shot Sentiment Analysis**: Employ the GPT-3.5-turbo API for zero-shot sentiment analysis. Present text without specific context, and the model will infer the sentiment.

3. **Random Forest Sentiment Analysis**: Use the `text-embedding-ada-002` model in conjunction with a Random Forest classifier to perform sentiment analysis.
