# LLaMA 3 Fine-Tuning for Medical Chain-of-Thought Reasoning (Unsloth + Hugging Face)

This project demonstrates how to fine-tune the [LLaMA 3 (3B) Instruct model](https://huggingface.co/meta-llama/Meta-Llama-3-3B-Instruct) using a Chain-of-Thought dataset specific to medical reasoning, with **Unsloth**, **PEFT (QLoRA)**, and **Hugging Face** integration.

## 🚀 Project Overview

- 🔬 Dataset: [FreedomIntelligence/medical-o1-reasoning-SFT](https://huggingface.co/datasets/FreedomIntelligence/medical-o1-reasoning-SFT)
- 🧠 Model: Meta-LLaMA 3 (3B) Instruct
- 🛠️ Fine-Tuning: SFT with PEFT using Unsloth
- 📊 Evaluation: ROUGE-L scores before and after fine-tuning
- 🧪 Trained on: Google Colab

## 📁 Files

- `llama3_finetune_medical_cot.ipynb` – Full notebook with training pipeline
- `README.md` – Project summary

## 📈 ROUGE-L Evaluation

- **Before Fine-Tuning**: `0.3052`
- **After Fine-Tuning**: `0.3052` (slight fluctuation due to short training)

## ✅ Steps Included

1. Model loading (Unsloth)
2. Dataset loading and formatting
3. PEFT configuration (QLoRA)
4. Training with `SFTTrainer`
5. ROUGE-L evaluation
6. Saving and uploading to Hugging Face Hub

## 🤖 Model on Hugging Face Hub

📌 https://huggingface.co/imranmansha/llama3-medical-finetuned

## 🧠 Creator

- **Name:** Imran Mansha
- **LinkedIn:** [[Your LinkedIn link here](https://www.linkedin.com/in/imranmansha/)]
- **YouTube Walkthrough:** [[YouTube link here](https://youtu.be/ogoe71cpUe4?si=rT-agQQK_QkZmBr2)]

---

## 📝 License

This project is licensed under the MIT License.
