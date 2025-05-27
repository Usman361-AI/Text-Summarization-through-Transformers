# 🧠 Text Summarisation using Transformer

This project demonstrates a **Transformer-based model** for abstractive text summarization using a toy dataset. It showcases the architecture, tokenization, positional encoding, and training of a Transformer from scratch using TensorFlow.

---

## 📌 Project Overview

| Component         | Description |
|------------------|-------------|
| 📄 Dataset        | A toy dataset with 5 sample articles and their summaries |
| 🔍 Preprocessing  | Text cleaning, tokenization, padding |
| 🔧 Model          | Transformer-based encoder-decoder using Keras |
| 📈 Output         | Trained model to predict summaries from input texts |

---

## 🛠️ Model Architecture

The model consists of:
- Token and position embeddings
- Multi-head self-attention layers
- Feed-forward neural networks
- Encoder-decoder attention
- Custom loss and training loop

---

## 📊 Training

The model is trained on a small dataset for demonstration purposes. The loss over epochs is plotted at the end.

---

## 🚀 Sample Prediction

> **Input**: "The stock market crashed due to inflation fears."  
> **Predicted Summary**: *"Market crashed."*

---

## 🧾 Requirements

Install all dependencies via:

```bash
pip install -r requirements.txt
```

---

## 📂 File Structure

```
├── Text_summarisation_Transformer.ipynb  # Main notebook
├── README.md
└── requirements.txt
```

---

## 🙌 Author

This project was built as a demonstration of transformer models on simple text. Feel free to fork and extend with larger datasets!

