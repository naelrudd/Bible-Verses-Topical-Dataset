# 📖 Bible Verses Topical Dataset (ID)

This repository contains a structured dataset of Bible verses categorized by topic and context. It is useful for spiritual study, thematic analysis, and NLP applications.

## 📂 Dataset Information
- **File Name:** `bible_verses_dataset.csv`
- **Columns:**
  - `verse`: The full Bible verse text
  - `reference`: The book, chapter, and verse reference (e.g., "2 Tesalonika 3:3")
  - `topic`: The main theme of the verse (e.g., "Perlindungan Tuhan", "Transformasi Mental")
  - `context`: A brief explanation of the verse in relation to its topic

## 🔍 Usage
This dataset can be used for:
- **Biblical studies**: Finding verses by topic  
- **Natural Language Processing (NLP)**: Text analysis of scripture  
- **Devotional apps**: Organizing and displaying Bible verses by theme  
- **AI & Machine Learning**: Training models for religious text analysis  

## 📥 Access the Dataset
To use the dataset in Google Colab without manual uploads, fetch it directly from this repository:

```python
import pandas as pd

url = "https://raw.githubusercontent.com/[your-username]/[your-repo]/main/bible_verses_dataset.csv"
df = pd.read_csv(url)
df.head()
