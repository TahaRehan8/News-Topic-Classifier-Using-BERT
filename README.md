# 📑 News Topic Classifier (BERT + Hugging Face)

This repository contains an implementation of a **News Topic Classification model** using **BERT** and the **AG News dataset**. The project is developed as part of **DHC3135 – Task 1 Phase 2**.

## 📘 Project Overview

* Fine-tunes a **BERT-base-uncased** model for **text classification**.
* Dataset: **[AG News](https://huggingface.co/datasets/ag_news)** (4 classes: *World, Sports, Business, Sci/Tech*).
* Evaluation: **Accuracy** & **Weighted F1 Score**.
* Interactive **Gradio demo** for real-time text classification.

## 📂 Repository Structure

```
├── DHC3135_Task_1_Phase_2.ipynb   # Main notebook with implementation
├── README.md                      # Project documentation
└── requirements.txt               # Dependencies (optional)
```

## ⚙️ Installation

Clone the repository:

```bash
https://github.com/TahaRehan8/News-Topic-Classifier-Using-BERT.git
cd https://github.com/TahaRehan8/News-Topic-Classifier-Using-BERT.git
```

Install dependencies:

```bash
pip install transformers datasets evaluate scikit-learn gradio torch --upgrade
```

## ▶️ Usage

Run the Jupyter Notebook:

```bash
jupyter notebook DHC3135_Task_1_Phase_2.ipynb
```


## 📊 Results

* Model: `bert-base-uncased` fine-tuned on **AG News**
* Metrics (sample):

  * Accuracy: \~94%
  * Weighted F1: \~94%

## 🌐 Gradio Demo

Example usage:

   ![1000051771](https://github.com/user-attachments/assets/36358bcd-b061-40e5-95c3-61b5a2ffa44c)

## 📌 Requirements

* Python 3.8+
* PyTorch
* Hugging Face Transformers
* Datasets
* scikit-learn
* Gradio


