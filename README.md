# NLP Portfolio

A collection of Natural Language Processing projects covering a wide range of techniques, from foundational text representations to real-world applications in healthcare and news analytics.

---

## Projects Overview

| # | Topic | Techniques Used |
|---|-------|----------------|
| 01 | NLP Pipeline | Tokenization, POS Tagging, Lemmatization, NER |
| 02 | Text Representations | BoW, TF-IDF, N-Grams, Word2Vec, GloVe, FastText |
| 03 | Text Classification | Logistic Regression, Naive Bayes, SVM |
| 04 | Named Entity Recognition | spaCy, Custom NER, Entity Extraction |
| 05 | Topic Modeling | LDA, LSA, News Dataset Analysis |
| 06 | Keyword Extraction | RAKE, YAKE, KeyBERT |
| 07 | Text Summarization | Extractive & Abstractive Summarization |
| 08 | Medical NLP | Prescription Parsing, Clinical Text Processing |

---

## Folder Structure

```
nlp-portfolio/
├── 01_NLP_Pipeline/          # End-to-end NLP processing pipeline
├── 02_Text_Representations/  # Classic and neural text vectorization methods
├── 03_Text_Classification/   # Supervised text categorization
├── 04_Named_Entity_Recognition/  # Entity detection and extraction
├── 05_Topic_Modeling/        # Unsupervised topic discovery from text
├── 06_Keyword_Extraction/    # Automated keyword and keyphrase extraction
├── 07_Text_Summarization/    # Automatic document summarization
└── 08_Medical_NLP/           # Healthcare-focused NLP (prescription parsing)
```

---

## Highlights

### 🩺 Medical NLP — Prescription Parser
Parses real-world medical prescription text to extract:
- Drug names
- Dosage & frequency
- Patient instructions

A rare and high-value application of NLP in the healthcare domain.

### 🏷️ Named Entity Recognition
Identifies and classifies entities (people, organizations, locations, dates) in unstructured text using spaCy and custom-trained models.

### 📰 Topic Modeling on News Data
Uses LDA and LSA on a real Kaggle news dataset to automatically discover hidden topics across thousands of articles.

### 📝 Text Summarization
Implements both extractive (sentence ranking) and abstractive (seq2seq) summarization pipelines.

---

## Tech Stack

- **Language:** Python 3
- **Core Libraries:** spaCy, NLTK, scikit-learn, Gensim, Transformers (HuggingFace)
- **Embeddings:** Word2Vec, GloVe (6B, 50d), FastText (cc.en.300)
- **Notebooks:** Jupyter Notebook
- **Datasets:** Kaggle News Dataset, Medical Prescription Data

---

## How to Run

1. Clone the repo:
```bash
git clone https://github.com/YOUR_USERNAME/nlp-portfolio.git
cd nlp-portfolio
```

2. Install dependencies:
```bash
pip install spacy nltk scikit-learn gensim transformers jupyter
python -m spacy download en_core_web_sm
```

3. Open any notebook:
```bash
jupyter notebook
```

---

## Background

These projects were developed as part of an advanced Machine Learning curriculum, applying NLP techniques to real-world datasets across multiple domains including news, healthcare, and general text corpora.
