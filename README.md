[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1d6b7iy4Yj52VRYk3yAI1DiOZj3bfxrNl?usp=sharing)
# USER QUESTION ANSWERING MODEL - FINE TUNING BERT
This repository contains a Jupyter notebook for fine-tuning the **BERT** (Bidirectional Encoder Representations from Transformers) model on a Question Answering (QA) task using the Hugging Face Transformers library and PyTorch. It also contains a notebook where the task is performed without fine-tuning the transformer.

## 📌 Project Overview - fine tuned BERT version

The goal of this project is to:

* Load and preprocess a QA dataset
* Tokenize and format the data for BERT
* Fine-tune the pre-trained `bert-base-uncased` model
* Evaluate the model's performance on the validation/test data

This serves as a foundational project for learning how to adapt transformer-based models to QA tasks.

---

## 🔧 Features

* ✅ Preprocessing and formatting data for SQuAD-style QA
* ✅ Fine-tuning BERT on a subset of QA data
* ✅ Evaluation metrics (Exact Match & F1 Score)
* ✅ Easy-to-follow notebook format

---

## 📚 Dataset

This notebook uses a [SQuAD-style dataset](https://rajpurkar.github.io/SQuAD-explorer/), which includes:

* Context passages
* Questions related to those passages
* Ground truth answers for supervision

You can modify the notebook to use your own custom QA dataset if desired.

---

## 🚀 How to use this
Download the `BERT fine tuned for QA.ipynb` file and run it !

## 🧪 Model & Training

* Model: `bert-base-uncased`
* Training framework: PyTorch
* Tokenizer: BERT tokenizer
* Loss: CrossEntropyLoss
* Evaluation: Exact Match (EM), F1 score

---

## 🛠️ Customization

* Replace `bert-base-uncased` with any other model from Hugging Face Hub.
* Plug in your own dataset by following the input format used in the notebook.

---

## 🙌 Acknowledgments

* Hugging Face 🤗 for `transformers` and `datasets` libraries
* SQuAD dataset creators

