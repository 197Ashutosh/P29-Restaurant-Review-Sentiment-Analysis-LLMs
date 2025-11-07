# 🧠 Intelligent Sentiment Analysis Suite  
### Product & News Reviews | LangChain RAG | Multi-LLM Sentiment System  

This repository presents a unified suite of **LLM-powered sentiment analysis projects**, including product and news review systems, **LangChain-based RAG pipelines**, and a **Multi-LLM (LLaMA + Mistral)** framework. It performs **aspect-level sentiment detection**, **feature extraction**, and **automated response generation** from unstructured text.

---

## 📂 Projects Included
1. **Product Review Analyzer (v1)** — `Mini Project 1.ipynb`  
   Performs sentiment classification using Bag of Words and Logistic Regression.  

2. **Product Review Analyzer (v2)** — `Comparision BOW & GloVe.ipynb`  
   Compares traditional BoW with GloVe embeddings for improved sentiment accuracy.  

3. **News Review Analyzer (Sentence Transformer)** — `Mini Project 2.ipynb`  
   Uses Sentence Transformers for sentence-level semantic sentiment detection in news articles.  

4. **LangChain RAG Implementation** — `Mini Project 3.ipynb`  
   Demonstrates Retrieval-Augmented Generation (RAG) for document-based Q&A using vector stores and LLMs.  

5. **Multi-LLM Sentiment System (LLaMA + Mistral)** — `Restaurant-Review-Sentiment-Analysis-LLMs_Project-5.ipynb`  
   A hybrid model for overall and aspect-based sentiment detection, liked/disliked feature extraction, and natural response generation.

---

## ⚙️ Setup & Installation

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/Intelligent-Sentiment-Analysis-Suite.git
cd Intelligent-Sentiment-Analysis-Suite

# 2. Create and activate a virtual environment (recommended)
python -m venv venv
venv\Scripts\activate        # On Windows
# or
source venv/bin/activate     # On macOS/Linux

# 3. Install dependencies
pip install -r requirements.txt
