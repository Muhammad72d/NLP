# NLP
#  Arabic NER 
#  Named Entity Recognition (NER) Project

This project focuses on **Named Entity Recognition (NER)** using state-of-the-art NLP models.  
The goal is to automatically identify and classify entities such as **persons, organizations, locations, dates, etc.** in text.  



## 📖 Project Overview
This project focuses on **Natural Language Processing (NLP) for Arabic text** worry about the important task:

 **Named Entity Recognition (NER)**  
   Extracting entities such as **persons, organizations, locations, and dates** from Arabic news articles or tweets using **MARBERT**.  

The main objective is to build a pipeline that **detects entities in raw Arabic text**.

---

## ⚙ Project Workflow
1. **Data Preprocessing**  
   - Cleaning and normalizing Arabic text.  
   - Splitting long articles into smaller chunks to fit model constraints.  

2. **Named Entity Recognition (NER)**  
   - Using **MARBERT** fine-tuned for token classification.  
   - Extracting entities (`entity_group`, `word`, `score`, `start`, `end`).   

3. **Final Output**  
   - Original text.  
   - Extracted entities (as structured JSON/dictionary or DataFrame).   


---
## modules
- **matplotlib.pyplot**
- **AutoTokenizer**
- **AutoModelForTokenClassification**
- **AutoModelForSeq2SeqLM**
- **pipeline**
- **pandas**
- **os**
---
