# 🧠 CS5720 - Home Assignment 4  
**University of Central Missouri**  
**Department of Computer Science & Cybersecurity**  
**Course:** Neural Network and Deep Learning (CS5720)  
**Semester:** Spring 2025  

**Student Name:** Nagabandi Shravya  
**Student ID:** 700757053  

---

## 📚 Assignment Overview

This repository contains solutions to Home Assignment 4 covering Chapters 9 & 10. The tasks involve foundational concepts and implementations in NLP, Attention mechanisms, and pre-trained Transformers.

---

## ✅ Questions Covered

### 🔹 Q1: NLP Preprocessing Pipeline
- Tokenization, stopword removal, and stemming using `nltk`.
- Input Sentence:  
  `"NLP techniques are used in virtual assistants like Alexa and Siri."`

### 🔹 Q2: Named Entity Recognition with SpaCy
- Extracts named entities (e.g., PERSON, ORG, DATE) and prints entity text, label, and character positions.
- Input Sentence:  
  `"Barack Obama served as the 44th President of the United States and won the Nobel Peace Prize in 2009."`

### 🔹 Q3: Scaled Dot-Product Attention
- Implements attention mechanism using NumPy.
- Calculates attention weights and final output based on Q, K, V matrices.

### 🔹 Q4: Sentiment Analysis with HuggingFace Transformers
- Loads a pre-trained pipeline and analyzes sentiment of input text.
- Input Sentence:  
  `"Despite the high price, the performance of the new MacBook is outstanding."`

---

## 🛠 Requirements

Install dependencies before running:

```bash
pip install nltk spacy numpy transformers
python -m nltk.downloader punkt stopwords
python -m spacy download en_core_web_sm
