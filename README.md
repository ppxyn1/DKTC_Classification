# DKTC Classification
### 📌 Project Overview
- Objective: This project aims to develop a model that classifies threatening conversations (threats, extortion, workplace bullying, and other types of harassment) and general conversations in Korean. By training an NLU (Natural Language Understanding)-based model, we seek to analyze text data effectively and automatically determine whether a conversation is threatening.   
  
---
  
### 📊 Dataset Composition
*`Data`* [tunib-ai/DKTC](https://github.com/tunib-ai/DKTC): TUNiB's Self-Produced Dataset to Participate in the Voice Recognition Track of the 4th AI Grand Challenge 2021. 

- The training dataset consists of approximately 1,000 samples per class for four categories: threats, extortion, workplace bullying, and other harassment.
- The test dataset consists of approximately 100 samples per class for five categories: threats, extortion, workplace bullying, other harassment, and general conversation.
  

| Dataset | Classes | Samples |  
|--------|--------|--------|
| Train | Threats, Extortion, Workplace Bullying, Other Harassment | around 4,000 |  
| Test | Threats, Extortion, Workplace Bullying, Other Harassment | around 500 |   
| Additional Data	| General Conversation (Synthetic Data, AI-hub Dataset) | (+)samples |

---

*`Evaluation`*: Measure by the f1 score between the results classified by the model and the correct answer.

---
### 📂 Directory

```
┣ assets/         # About Dataset, results(photos) and report(.md)
┣ models/         # Trained models and checkpoints
┣ src/            # Source code, data analysis, and experiment notebooks
┃ ┗ notebooks/    # Data analysis and experiment notebooks (.ipynb)
┃ ┗ utils/        # Preprocess and other required modules (.py)
┗ 📜 README.md    # Project description file
```


---
### 📈 Version
| Version    | Date | Contentes | Update Notes | Number of Members |  
| ------- | ------ | --------- | --------- | ----------- | 
|  v1.0.0   | Feb.21.2025 | Draft | [Group project](https://github.com/ChoSungWoo0/AIFFEL_DLthon_NLP_classification)     | 4      | 
|  v1.0.1   | ongoing | Organise the draft project and visualisation  | -  |    1   | 

---

