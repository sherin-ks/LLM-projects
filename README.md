# Text Summarization with CNN/Daily Mail Dataset

This project focuses on creating a **text summarization model** that generates concise summaries of news articles using pretrained language models (LLMs) such as BART, GPT, or T5. The model is fine-tuned using the **CNN/Daily Mail dataset**, which pairs news stories with human-written summaries. Both **extractive** and **abstractive** summarization methods are explored.

## Project Overview

Text summarization is a natural language processing (NLP) task that aims to reduce the length of a text document while preserving its core meaning. This project uses state-of-the-art models like BART to generate **abstractive summaries**—where the model generates new sentences for the summary. Additionally, we experiment with **extractive summarization**, which selects key sentences directly from the text.

### Abstractive Summarization:
- Generates new sentences that capture the essence of the input text.
- Uses pretrained models such as **BART** or **T5**.

### Extractive Summarization:
- Selects key sentences from the original text.
- Uses simpler algorithms like **TextRank** for summarization.

## Features

- Fine-tuned abstractive summarization using **BART** and the **CNN/Daily Mail** dataset.
- Evaluated using **ROUGE** score, a standard metric for summarization tasks.
- A simple web interface built with **Streamlit** to allow users to input text and generate summaries.
- Extractive summarization using the **TextRank** algorithm as a baseline.




