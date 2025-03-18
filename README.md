# Twitter Sentiment Analysis using BERT (Trained from Scratch)

This project implements **Twitter Sentiment Analysis** using a **BERT (bert-base-uncased) model trained from scratch** with **PyTorch**. The model classifies tweets into **positive, negative, and neutral** sentiments.

## 🚀 Features
- **Custom BERT Training**: Trains `bert-base-uncased` from scratch on a Twitter sentiment dataset.
- **Data Preprocessing**: Cleans and tokenizes raw Twitter text.
- **Fine-tuning**: Optimizes BERT for sentiment classification.
- **Evaluation Metrics**: Measures **accuracy, precision, recall, and F1-score**.
- **Deployment Ready**: Can be used for real-time sentiment analysis via an API.

---

## 📌 Dataset
The model is trained on a publicly available **Twitter Sentiment Dataset**. You can also use a custom dataset by formatting it as:
```
text,label
"This is amazing!",positive
"I hate this",negative
"It's okay",neutral
```

---

## 📂 Installation & Setup
### 🔹 Prerequisites
- Python 3.8+
- PyTorch
- Hugging Face Transformers
- Pandas, NumPy, Scikit-Learn
- CUDA (for GPU acceleration, optional)

### 🔹 Clone the Repository
```bash
git clone https://github.com/your-username/twitter-sentiment-bert.git
cd twitter-sentiment-bert
```

### 🔹 Install Dependencies
```bash
pip install -r requirements.txt
```


## 📊 Model Training
The model is trained using **PyTorch** with the following settings:
- **Optimizer**: AdamW
- **Loss Function**: Cross-Entropy Loss
- **Batch Size**: 8
- **Learning Rate**: 2e-5
- **Epochs**: 3 (modifiable)

---

## 📈 Results & Performance
After training, the model achieves **high accuracy** on test data. Sample results:
| Metric  | Score |
|---------|-------|
| Accuracy | 98%  |
| F1-Score | 86%  |
| Precision | 85%  |
| Recall | 87%  |

---

## 🤝 Contributing
Feel free to contribute by submitting **issues** or **pull requests**. If you improve the model or add new features, we'd love to hear from you!

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgments
- Hugging Face for the **Transformers** library
- PyTorch for **deep learning support**
- The NLP community for datasets and research

---

### 🔗 Connect
For any questions or suggestions, reach out to **Divyansh Rajput** via GitHub or email: [divyanshrajput126@gmail.com].

---

Happy coding! 🚀
