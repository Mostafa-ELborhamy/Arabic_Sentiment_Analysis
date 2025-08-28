# 🚗 Arabic Sentiment Analysis (Automobile Domain)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

This project performs **sentiment analysis on Arabic automobile-related text** using **AraBERT v0.2 (`aubmindlab/bert-base-arabertv02`)**.  
The model classifies text into **Positive**, **Negative**, or **Mixed** sentiment.

---

## ✨ Features
- Fine-tuned **AraBERT** for Arabic sentiment classification  
- Dataset: *Arabic Automobile Dataset* (`ArabicAutomobileDataset.csv`)  
- 3 sentiment classes: `positive`, `negative`, `mixed`  
- Evaluation with Accuracy, Precision, Recall, and F1  
- Training and evaluation provided as a **Jupyter Notebook (`.ipynb`)**

---

## 🗂️ Dataset
The dataset consists of **automobile-related Arabic text samples** with annotated sentiment labels.  
- File: `ArabicAutomobileDataset.csv`  
- Columns: `text`, `label`  
- Classes: `pos`, `neg`, `mix`

*(If dataset is private/custom, specify accordingly. If public, add link/citation.)*

---

## 🏋️ Training
We fine-tuned **`aubmindlab/bert-base-arabertv02`** on the dataset. Training was done in a Jupyter Notebook using PyTorch and Hugging Face Transformers.

Training workflow:
1. Load and preprocess dataset  
2. Tokenize text using **AraBERT tokenizer**  
3. Fine-tune BERT with classification head  
4. Evaluate on validation split  

---

## 📊 Results
| Metric           | Value   |
|------------------|---------|
| Training Loss    | X.XXX   |
| Validation Loss  | X.XXX   |
| Accuracy         | XX.XX % |
| Precision        | XX.XX % |
| Recall           | XX.XX % |
| F1 Score         | XX.XX % |

*(Replace `X.XXX` with your actual results from the notebook.)*

---

## 📦 Installation
Clone the repo and install dependencies:

```bash
git clone https://github.com/<your-username>/arabic-sentiment-analysis.git
cd arabic-sentiment-analysis
pip install -r requirements.txt
