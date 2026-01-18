# text-summarization-amazon-reviewsS
Text Summarization using Extractive and Abstractive Models on Amazon Reviews with Streamlit Deployment
# Text Summarization on Amazon Fine Reviews

This project implements and compares extractive and abstractive text summarization models using a public Kaggle dataset of Amazon product reviews. The project includes data preprocessing, exploratory data analysis, model training, evaluation, and a deployed Streamlit web application.

---

## 📌 Project Objectives
- Perform text summarization on real-world review data
- Compare extractive and abstractive summarization techniques
- Evaluate model performance using ROUGE metrics
- Deploy a functional Streamlit web application

---

## 📊 Dataset
- **Name:** Amazon Fine Reviews – Cleaned & ML Ready
- **Source:** Kaggle (Public Dataset)
- **Input:** Review text
- **Output:** Human-written summary

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Hugging Face Transformers (T5)
- Sumy (TextRank)
- ROUGE
- Streamlit

---

## 🧹 Data Preprocessing
- Removal of null values
- Text normalization (lowercasing, punctuation removal)
- Length filtering for transformer models
- Train-test split

---

## 📈 Exploratory Data Analysis
- Distribution of review lengths
- Distribution of summary lengths
- Comparison between input and output text sizes

---

## 🤖 Models Implemented
| Model | Type |
|------|------|
| TextRank | Extractive |
| T5-Small | Abstractive |

---

## 📏 Evaluation Metrics
- ROUGE-1
- ROUGE-2
- ROUGE-L

---

## 🖥️ Streamlit Web Application
The Streamlit app allows users to:
- Enter custom review text
- Select a summarization model
- Generate and view summaries in real time

---

## 🚀 How to Run the Project

### 1️⃣ Install dependencies
```bash
pip install -r requirements.txt
