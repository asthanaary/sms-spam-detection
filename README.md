#  SMS Spam Detection

A Machine Learning project to classify SMS messages as **Spam** or **Ham** (Not Spam).  
Built with **Python**, **scikit-learn**, and **Natural Language Processing (NLP)** techniques using a **Random Forest Classifier**.

---

##  Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)

---

##  Overview
This project applies **Natural Language Processing (NLP)** with a **Random Forest Classifier** to detect spam messages in SMS datasets.  
The workflow includes:
- Text preprocessing (tokenization, stopword removal, stemming/lemmatization)
- Feature extraction using **TF-IDF**
- Model training & evaluation with Random Forest

---

##  Features
- Clean and preprocess SMS text data  
- Extract features using **TF-IDF Vectorizer**  
- Train a **Random Forest Classifier** for classification  
- Evaluate using Accuracy, Precision, Recall, and F1-Score  
- Save trained model for later predictions  

---

##  Project Structure
├── data/ # Dataset files
├── notebooks/ # Jupyter notebooks for EDA & experiments
├── src/ # Scripts for preprocessing & model training
├── models/ # Saved trained model
├── results/ # Metrics and plots
├── requirements.txt # Dependencies
└── README.md
---

##  Installation
Clone the repository:
```bash
git clone https://github.com/<your-username>/SMS-Spam-Detection.git
cd SMS-Spam-Detection
