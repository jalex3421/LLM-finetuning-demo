# 🦥💡 LLM Fine-Tuning with Unsloth

Author: Alejandro Meza Tudela

Welcome to my notebook on **fine-tuning Large Language Models (LLMs)** using [Unsloth](https://github.com/unslothai/unsloth) 
This guide walks you through the **end-to-end process** of customizing an LLM for your own dataset — all while keeping things **efficient, affordable, and fun**.  

---

## 📚 What You’ll Learn
This notebook demonstrates:

1. 📂 **Define a custom dataset**  
2. 🏗️ **Load a base model**  
3. 🎛️ **Apply LoRA adapters** for efficient fine-tuning  
4. 📝 **Format a dataset** for training  
5. 🧑‍🏫 **Train the model with `SFTTrainer`**  
6. 🤖 **Run inference** and test the fine-tuned model  

---

## 🔧 Tools & Frameworks
- **Unsloth** – Fast, lightweight LLM finetuning  
- **LoRA (Low-Rank Adaptation)** – Trainable adapters that save GPU memory & time  
- **PyTorch** – Backend for training  
- **Hugging Face Transformers** – Tokenization & model hub  

---

## ✨ Why Unsloth?
Unsloth is an **open-source framework** designed to make LLM fine-tuning:  
✅ **Faster** (optimized GPU memory usage)  
✅ **Cheaper** (less compute & VRAM needed)  
✅ **Accessible** (clean, easy-to-use API)  

Perfect for **students, researchers, and builders** who want to create their own specialized LLMs.  

---

## 🎥 Acknowledgments
This project was inspired by the awesome YouTube channel **[Tech with Tim](https://www.youtube.com/@TechWithTim)** and his video:  
> *“EASIEST Way to Fine-Tune a LLM and Use It With Ollama”*  

Big thanks for making LLM finetuning more approachable 🙌  

---

## 🚀 Getting Started
Clone the repo and open the notebook:

```bash
git clone https://github.com/your-username/llm-finetune-unsloth.git
cd llm-finetune-unsloth
jupyter notebook
