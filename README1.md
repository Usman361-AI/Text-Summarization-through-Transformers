# Text Summarization using Transformer

This project implements an end-to-end Text Summarization system using a custom Transformer model built from scratch with TensorFlow/Keras.
It focuses on generating concise summaries from long-form articles using sequence-to-sequence learning with attention mechanisms.

## Folder Structure
```
text_summarization_transformer/
├── text_summarization_transformer.ipynb ← Main Colab notebook
├── data/
│ ├── articles.json ← Original long texts
│ └── summaries.json ← Corresponding human-written summaries
├── tokenizer/
│ ├── article_tokenizer.pkl ← Fitted tokenizer for articles
│ └── summary_tokenizer.pkl ← Fitted tokenizer for summaries
└── README.txt
```

## Project Goals
- Build a sequence-to-sequence Transformer model for abstractive text summarization.
- Understand and implement:
- Positional encoding
- Scaled dot-product attention
- Multi-head attention
- Encoder-decoder architecture
- Train the model on a custom dataset of article-summary pairs.
- Evaluate and generate predictions from test inputs.

## Technologies Used
- **Data Processing:** Pandas, NumPy
- **Tokenization:** TensorFlow/Keras
- **Model Architecture:** Custom Transformer
- **Visualization:** Matplotlib
- **Notebook Environment:** Google Colab

## Dataset
The project uses a manually curated dataset of article-summary pairs.

- `data/articles.json` - Full text articles
- `data/summaries.json` - Corresponding summaries

You can replace these files with your own data. Ensure both are lists of strings and aligned index-wise.

## How to Run (in Google Colab)
1. Upload the project folder structure.
2. Open the `text_summarization_transformer.ipynb` notebook.
3. Install dependencies if needed (`!pip install tensorflow`).
4. Run all cells to train and evaluate the Transformer.

## Highlights
- Custom implementation of positional encoding and multi-head attention.
- Encoder-decoder structure for text generation.
- Supports sequence padding, start/end token handling, and teacher forcing.
- Easily extendable to larger datasets or pre-trained embeddings.

## Example Input & Output
**Input Article:**
"Machine learning enables systems to learn and improve automatically..."

**Generated Summary:**
"Machine learning helps systems improve automatically."

## References
- [Attention is All You Need (Vaswani et al., 2017)](https://arxiv.org/abs/1706.03762)
- TensorFlow Official Documentation
- Custom implementation guidance via OpenAI’s ChatGPT

## Author
**USMAN**
User-Profile: Usman361-AI

## Bonus Ideas for Extension
- Use pre-trained embeddings like GloVe or BERT.
- Add beam search decoding for better generation quality.
- Visualize attention weights.
