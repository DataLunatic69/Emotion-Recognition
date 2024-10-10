# **Emotion Classifier using DistilBERT**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)
[![Model Type: DistilBERT](https://img.shields.io/badge/Model-DistilBERT-green)](https://huggingface.co/distilbert-base-uncased)

## **Table of Contents**
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Training the Model](#training-the-model)
- [Model Performance](#model-performance)
- [License](#license)

---

## **Overview**

The Emotion Classifier uses **DistilBERT** to detect emotions from text input. It supports categories such as anger, joy, sadness, fear, and surprise, making it ideal for sentiment analysis tasks.

---

## **Features**
- Text classification into emotion categories using pre-trained DistilBERT.
- Fine-tuning with PyTorch for custom datasets.
- Tkinter-based GUI for easy interaction.
- High accuracy and F1 score using standard evaluation metrics.

---

## **Installation**

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/emotion-classifier.git
cd emotion-classifier
```
### **2. Install Dependencies**
```bash
pip install -r requirements.txt
```
### **3. Download Pretrained Models**
```bash
from transformers import AutoTokenizer, AutoModelForSequenceClassification

model_ckpt = "distilbert-base-uncased"
tokenizer = AutoTokenizer.from_pretrained(model_ckpt)
model = AutoModelForSequenceClassification.from_pretrained(model_ckpt)

```



## **Usage**

### **Command Line Interface (CLI)**
```bash
python classify_emotion.py --text "I am so happy today!"

```
### **Graphical User Interface (GUI)**
```bash
python emotion_gui.py


```

## **Train the model**

### ****
```bash
python train_emotion_classifier.py --epochs 3 --batch_size 32 --lr 2e-5


```











