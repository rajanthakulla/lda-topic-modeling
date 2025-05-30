# LDA-topic-modeling
Topic modeling using LDA on textual data with preprocessing in Python.

### Download Dataset 
- click the link: https://drive.google.com/drive/folders/1p2GdB35FBLJ6XxdbpV2OuH4s4MAxRmfd?usp=sharing


## 📌 Features

- Reads and processes a dataset of text documents.
- Cleans text using:
  - Tokenization
  - Stopword removal
  - Lemmatization
- Applies **Count Vectorization** to create a Document-Term Matrix.
- Trains an LDA model to identify hidden topics in the corpus.
- Displays the top 10 keywords for each discovered topic.

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- NLTK
- Scikit-learn
- pandas
- pyLDAvis (installed but not visualized in notebook)

## 📋 Preprocessing Steps

1. Lowercasing and tokenization
2. Removing punctuation and stopwords
3. Lemmatization of tokens
4. Filtering out documents with fewer than 5 tokens

## 🔍 Topic Modeling

- Model: `LatentDirichletAllocation` from `sklearn.decomposition`
- Number of Topics: 5
- Vectorization: `CountVectorizer` (using pre-tokenized inputs)


## 🚀 Getting Started

### Prerequisites

```bash
'pip install pandas scikit-learn nltk pyLDAvis'




