# 📝 Text Summarization using Transformers

This project demonstrates how to build and fine-tune a **sequence-to-sequence (Seq2Seq)** model for **automatic text summarization** using the Hugging Face 🤗 Transformers library.
It leverages pre-trained transformer models such as **BART**, **T5**, **Pegasus**, along with the **datasets** library for data loading and **PyTorch** for training and inference.

---

## 🚀 Features

* Loads and preprocesses a summarization dataset using `datasets.load_dataset()`.
* Uses a pre-trained summarization model (`AutoModelForSeq2SeqLM`) and tokenizer.
* Supports model fine-tuning with custom `TrainingArguments` and `Trainer`.
* Includes evaluation metrics like ROUGE for summarization quality.
* Enables quick inference with the Hugging Face `pipeline("summarization")`.

---

## 🧠 Technologies Used

* **Python 3.x**
* **Hugging Face Transformers**
* **PyTorch**
* **Hugging Face Datasets**
* **Pandas**

---

## ⚙️ Setup Instructions

### 1. Install Dependencies

```bash
pip install transformers datasets torch pandas
```

### 2. Run the Notebook

Open the notebook in Jupyter or VS Code and run all cells:

```bash
jupyter notebook Summarization.ipynb
```

---

## 📈 Results

* The model generates concise summaries while retaining the main idea of the input text.
* ROUGE scores can be used to measure summarization quality.

---

## 📚 Future Improvements

* Experiment with different models (e.g., `t5-small`, `facebook/bart-large-cnn`, `google/pegasus-xsum`).
* Add beam search and temperature tuning for better summary quality.

---

## 🧩 Author

Developed by **Gunjan Soni**
Feel free to fork, modify, and enhance this notebook for your own summarization tasks!

