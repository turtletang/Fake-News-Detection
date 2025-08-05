# 📰 Fake News Detection Using ML, DL, and Transformers

This project develops an automated fake news detection system using:
- Traditional Machine Learning models (SVM, Random Forest, Naïve Bayes)
- Deep Learning models (RNN, LSTM)
- Transformer-based model (BERT)

By combining advanced feature extraction methods (TF-IDF, Bag of Words, contextual embeddings from BERT) and testing across these models, we aim to provide a robust and accurate system for real vs. fake news classification.

---

## 📌 Project Highlights

- Achieved up to **99.35% accuracy** with Random Forest (TF-IDF).
- Demonstrated **superior generalization** of BERT (97.86% accuracy) despite high computational cost.
- Identified common misclassification patterns (e.g., political content, journalistic tone).
- Conducted error analysis for each modeling approach.

---

## 📁 Repository Structure
- ├── demo/ # Demo scripts and model files
- │ └── demo.py # Main interactive CLI demo
- ├── Deeplearning.ipynb # RNN and LSTM models + evaluation
- ├── Machinelearning.ipynb # SVM, RF, NB models + evaluation
- ├── Transformer.ipynb # BERT model + training pipeline
- ├── Train.csv # Kaggle dataset used for training/testing
- └── Report.pdf # Full research report

## 📊 Datasets
Source: Kaggle Fake News Detection dataset

Size: ~20,800 labeled articles

Fields Used: title and author (concatenated)

## 📈 Model Performance Summary
- Model	Accuracy	Precision	Recall	F1-score
- Random Forest	99.35%	99%	99%	99%
- SVM	99.30%	99%	99%	99%
- Naïve Bayes	96.23%	96%	96%	96%
- LSTM	92.98%	93%	93%	93%
- RNN	92.79%	93%	93%	93%
- BERT	97.86%	98%	98%	98%


