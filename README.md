# text-emotion-sentiment-classifier
Classifies emotions and sentiment from text using Hugging Face transformers — supports joy, anger, sadness, and more.

# 🧠 Emotion & Sentiment Text Classifier

This project uses two powerful pretrained models from Hugging Face 🤗 to classify English text into:

1. **Binary Sentiment** – Positive or Negative  
2. **Fine-Grained Emotions** – Joy, Anger, Sadness, Fear, Love, Surprise, and more

---

## 🔍 Models Used

| Task            | Model Name                                                                 |
|-----------------|----------------------------------------------------------------------------|
| Sentiment       | [`distilbert-base-uncased-finetuned-sst-2-english`](https://huggingface.co/distilbert-base-uncased-finetuned-sst-2-english) |
| Emotion         | [`j-hartmann/emotion-english-distilroberta-base`](https://huggingface.co/j-hartmann/emotion-english-distilroberta-base) |

---

## 🚀 Features

- Classify multiple texts at once
- Texts are cleaned automatically before prediction
- Outputs the **top predicted label** and model **confidence score**
- Works in CLI or Jupyter notebook

---

## 🧪 Example Output

```text
Original: I love the way this turned out 💖
Sentiment: POSITIVE (0.9987)
Emotion: joy (0.9741)
