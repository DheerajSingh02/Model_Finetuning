# Emotion Classification with Parameter-Efficient Fine-Tuning using LoRA


This project demonstrates how to fine-tune a small language model using **LoRA (Low-Rank Adaptation)** for a 6-class **emotion detection task**, updating only **0.3%** of model parameters.

> ✅ Efficient  
> ✅ Lightweight  
> ✅ Reproducible  

---

## 📌 Overview

Fine-tuning large language models can be resource-intensive. This project uses **LoRA** to adapt a **BERT-tiny** model for **emotion classification** using the [Hugging Face "emotion" dataset](https://huggingface.co/datasets/dair-ai/emotion) with just **13,062 parameters trained**.

---

## 💡 Problem Statement

Build an emotion classifier to identify one of the following emotions from a given sentence:
- joy
- sadness
- love
- anger
- fear
- surprise

---

## 🧪 Setup

### 1. Clone the Repo
```bash
git clone https://github.com/DheerajSingh02/Model_Finetuning.git
cd Model_Finetuning

