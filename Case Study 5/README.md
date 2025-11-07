# 🍽️ Restaurant Review Sentiment Analysis using LLaMA and Mistral LLMs

This project leverages multiple **Large Language Models (LLMs)** — *LLaMA* and *Mistral* — to automatically analyze restaurant reviews and extract deep customer insights, including:

- ✅ Overall sentiment (Positive / Negative / Neutral)
- 🧩 Aspect-based sentiment analysis (e.g., food, service, ambiance)
- 💬 Extraction of liked/disliked features within each aspect
- 🤖 Automated, human-like responses based on the review tone

---

## 🚀 Features

- Multi-LLM architecture (**LLaMA + Mistral**) for enhanced accuracy  
- Aspect-based sentiment detection with contextual understanding  
- Structured JSON outputs for improved interpretability  
- Automated response generation for customer engagement  
- Results exportable as a CSV file for further analysis  

---

## 🧠 Project Workflow

| Task | Description | Model Used |
|------|--------------|-------------|
| **Task 1** | Identify overall sentiment of each review | LLaMA |
| **Task 2** | Generate structured sentiment outputs | LLaMA |
| **Task 3** | Detect overall and aspect-level sentiments | LLaMA |
| **Task 4** | Extract liked/disliked features from aspects | LLaMA |
| **Task 5** | Generate customer-facing responses | Mistral |

---

## 🧰 Technologies Used

- 🐍 **Python 3.10+**
- 🤖 **llama-cpp-python**
- 🤖 **mistralai**
- 📦 **pandas**, **huggingface_hub**
- 💾 **json**, **re**

---

## ⚙️ Installation

Run the following commands inside your notebook or terminal:

```bash
pip install --upgrade pip wheel setuptools
pip install llama-cpp-python mistralai pandas huggingface_hub --prefer-binary
