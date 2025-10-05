# Sentiment Analysis with DistilBERT

## 📌 Objective
This project fine-tunes a pretrained **DistilBERT model** for binary sentiment classification 
(positive/negative) using the IMDb reviews dataset.  
It demonstrates the power of transformer-based NLP models.

## 📊 Dataset
- **IMDb dataset** (50,000 labeled movie reviews)  
- Available directly via HuggingFace Datasets library  

## ⚙️ Methods
- Tokenization with `AutoTokenizer`  
- Model: DistilBERT with classification head  
- Training: HuggingFace `Trainer` API  
- Evaluation: Accuracy, F1-score, confusion matrix  

## 🚀 Results
- Accuracy: ~XX% on test set  
- F1-score: XX%  
- See `/results` folder for graphs  

## 🛠️ How to Run
1. Clone repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/bert-sentiment-analysis.git

