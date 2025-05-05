# ✈️ Sentiment Analysis on Airline Tweets using BERT Fine-Tuning

This project applies Natural Language Processing (NLP) techniques to classify the sentiment of tweets about airlines using a fine-tuned BERT model from Hugging Face.

## 📌 Objective

To train a robust sentiment classification model (positive, neutral, negative) capable of handling class imbalance using transfer learning with BERT.

---

## 🛠 Technologies Used

- Python 3.10+
- [Transformers (Hugging Face)](https://huggingface.co/transformers/)
- PyTorch
- Scikit-learn
- Pandas
- Matplotlib / Seaborn
  
---

## 📈 Model Performance

Initial training achieved:
- **Accuracy**: 84%
- **F1-score (negative)**: 0.91
- **F1-score (neutral)**: 0.69 → expected to improve with class reweighting
- **F1-score (positive)**: 0.78

After applying `class_weight` to penalize errors in minority classes, performance for underrepresented sentiments is expected to increase.
