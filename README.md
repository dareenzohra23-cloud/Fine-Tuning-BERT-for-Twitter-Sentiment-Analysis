# Fine-Tuning-BERT-for-Twitter-Sentiment-Analysis
Fine-tuning BERT for multi-class Twitter sentiment analysis using PyTorch and Hugging Face Transformers.
# 🧠 BERT Fine-Tuning for Twitter Sentiment Analysis

## 📌 Project Overview
This project focuses on fine-tuning a pre-trained BERT model (`bert-base-uncased`) for multi-class sentiment classification on a Twitter dataset.

The goal is to classify tweets into:
- Positive 😊
- Neutral 😐
- Negative 😠

---

## 🎯 Objective
- Understand transformer-based models (BERT)
- Perform fine-tuning on real-world text data
- Evaluate model performance using standard metrics

---

## ⚙️ Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Workflow
Raw Data → Preprocessing → Tokenization → Model Training → Evaluation → Analysis

---

## 🧹 Data Preprocessing
- Removed null values
- Converted text to lowercase
- Encoded sentiment labels into numeric values

---

## 🔤 Tokenization
- Used `bert-base-uncased` tokenizer
- Applied truncation and padding (`max_length=128`)

---

## 🏗️ Model
- Pre-trained BERT model for sequence classification
- Modified for 3 output classes

---

## ⚙️ Training
- Optimizer: AdamW
- Learning Rate: 2e-5
- Batch Size: 8
- Epochs: 1 (optimized for memory constraints)

---

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 🧪 Experiments
- Full fine-tuning of BERT
- Freezing BERT layers and training only classifier

---

## 📈 Results & Insights
- Fine-tuned BERT achieved strong classification performance
- Full fine-tuning provided better accuracy compared to frozen layers
- Memory optimization (reduced dataset size & sequence length) was crucial

---

## 🚀 Conclusion
This project demonstrates the effectiveness of transfer learning using BERT for NLP tasks. It also highlights the importance of optimization when working with large transformer models.

---

## 🔗 How to Run
1. Clone the repository  
2. Install dependencies  
3. Run the Jupyter Notebook  

---

## 🙌 Acknowledgment
Dataset sourced from Kaggle (Twitter Sentiment Dataset)

---

## 📬 Contact
Feel free to connect for discussions on NLP, ML, and AI!
