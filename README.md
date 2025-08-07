# 🇮🇳 Indian Language Identification using VoxLingua107

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Model](https://img.shields.io/badge/Model-VoxLingua107-blueviolet)](https://github.com/pszwarg/voxlingua107)
[![Colab](https://img.shields.io/badge/Try%20on-Colab-yellow?logo=google-colab)](https://colab.research.google.com/)

---

This project focuses on identifying **spoken Indian languages** from audio clips using **VoxLingua107**, a self-supervised multilingual model. The model is **fine-tuned on 10 Indian languages**, and the audio preprocessing includes **speech segmentation using Silero VAD**.

---

## 🚀 Features

- 🔊 **Audio Language Identification** from raw `.wav` files  
- 🤖 Fine-tuned **VoxLingua107** for 10 major Indian languages  
- ✂️ **Chunking pipeline** using pretrained **Silero VAD**  
- 📦 All chunking code in `chunking.py`  
- 🧪 Tools for **inference**, **evaluation**, and **training**  
- 🔧 Easy-to-use command-line and Python API

---

## 🗣️ Supported Indian Languages

The following languages were used for fine-tuning:

- Hindi  
- Bengali  
- Tamil  
- Telugu  
- Marathi  
- Gujarati  
- Kannada  
- Malayalam  
- Punjabi  
- Urdu  

---

## 📦 Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/indian-language-identification.git
cd indian-language-identification
