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
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
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

Or launch the Gradio demo:

```bash
python app.py
```

## 📊 Results

* Model: `bert-base-uncased` fine-tuned on **AG News**
* Metrics (sample):

  * Accuracy: \~94%
  * Weighted F1: \~94%

## 🌐 Gradio Demo

Example usage:

```text
![1000051771](https://github.com/user-attachments/assets/5bbfcfc1-3b1e-4e6d-aba9-1af9416374c3)

```

## 📌 Requirements

* Python 3.8+
* PyTorch
* Hugging Face Transformers
* Datasets
* scikit-learn
* Gradio


