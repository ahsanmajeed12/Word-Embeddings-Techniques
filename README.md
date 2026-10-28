<div align="center">

  <h1>✨ Word Embeddings Techniques ✨</h1>
  <p><b>A Comprehensive Hands-On Guide to Natural Language Processing (NLP) Vectorization</b></p>

  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=4285F4&center=true&vCenter=true&width=600&lines=From+Scratch+Implementations;One-Hot+Encoding+%7C+BoW+%7C+TF-IDF;Word2Vec+(CBOW+%26+Skip-gram);GloVe+%7C+FastText+%7C+Gensim" alt="Typing SVG" />

  <br/><br/>

  [![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
  [![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00.svg?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
  [![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
  [![Gensim](https://img.shields.io/badge/Gensim-4.4.0-333333.svg?style=for-the-badge)](https://radimrehurek.com/gensim/)

  <br/>
  
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="600" alt="NLP Banner Animation"/>

</div>

---

## 📌 Overview

Welcome to the **Word Embeddings Techniques** repository! This project serves as an end-to-end practical walkthrough of how text is transformed into numerical representations for machine learning models. 

It covers everything from traditional frequency-based approaches to advanced subword-level neural embeddings—built **both from scratch using NumPy** and using **industry-standard libraries** like `scikit-learn`, `gensim`, and `fasttext`.

---

## 🚀 Covered Techniques & Concepts

| Technique | Approach | Key Feature / Focus |
| :--- | :--- | :--- |
| **One-Hot Encoding** | Traditional | Manual NumPy mapping vs. `sklearn.preprocessing.OneHotEncoder` |
| **Bag of Words (BoW)** | Traditional | Frequency counting from scratch vs. `CountVectorizer` |
| **TF-IDF** | Frequency-Based | Term Frequency-Inverse Document Frequency from scratch vs. `TfidfVectorizer` |
| **Word2Vec (CBOW)** | Neural Approach | Continuous Bag of Words architecture with custom Forward/Backward pass |
| **Word2Vec (Skip-gram)** | Neural Approach | Target-to-context prediction built with custom softmax & weight updates |
| **GloVe** | Matrix Factorization | Co-occurrence matrix generation & pre-trained Wikipedia embeddings via `Gensim` |
| **FastText** | Subword-Based | Character n-grams implementation to handle Out-Of-Vocabulary (OOV) words |

---

## 🛠️ Project Structure

```text
├── Word_Embeddings_Techniques.ipynb   # Master Google Colab Notebook
├── README.md                           # Project Documentation
