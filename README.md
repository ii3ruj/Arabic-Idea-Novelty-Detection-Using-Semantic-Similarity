# Arabic Startup Idea Novelty Detection Using Semantic Similarity Techniques

An Arabic NLP system for measuring the novelty of startup ideas using semantic similarity techniques and transformer-based models.

---

# Overview

This project detects the novelty of Arabic startup ideas by comparing them with existing ideas using semantic similarity.

---

# Dataset

The dataset contains ~3756 Arabic startup ideas from:
- Hackathons  
- Competitions  
- Twitter/X  
- LinkedIn  
- Public sources  

---

# Models

- Bag of Words (BoW)
- TF-IDF
- Sentence-BERT (SBERT)
- AraBERT

---

# System Pipeline

![System Pipeline](figure1_system_pipeline.png)

---

# Project Files

## 📊 Dataset
👉 [Download Dataset](3750_hackathon_ideas.csv)

## 📓 Code python 
👉 [Python](Arabic_Startup_Idea_Novelty_Detection_Using_Semantic_Similarity.ipynb)

## 📄 ACL Paper
👉 [View Paper](Arabic_Startup_Idea_Novelty_Detection_Using_Semantic_Similarity_Techniques.pdf)

---

# How to Run

```bash
pip install -r requirements.txt
```

Then run the notebook:
```
notebooks/Arabic_Startup_Idea_Novelty_Detection_Using_Semantic_Similarity.ipynb
```

---

# Results

Transformer models (SBERT + AraBERT) performed better in semantic understanding than TF-IDF and BoW.

---

# Author

**Ruba Aljuhani**  
Email: Ruba35@gmail.com  

GitHub: https://github.com/ii3ruj
