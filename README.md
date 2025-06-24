# Text-Summarization-using-CNN
# Advanced Text Summarization System

![NLP](https://img.shields.io/badge/NLP-Text%20Summarization-blueviolet)
![Transformers](https://img.shields.io/badge/Powered%20By-HuggingFace%20Transformers-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

A dual-approach text summarization system implementing both extractive (spaCy) and abstractive (BART) methods, with ROUGE metric evaluation.

## ✨ Features

- **Two Summarization Techniques**:
  - 🎯 Extractive (spaCy) - Preserves original phrasing
  - 🎨 Abstractive (BART) - Generates new concise text
- **Quantitative Evaluation**:
  - ROUGE-1, ROUGE-2, and ROUGE-L metrics
  - Comparative analysis between methods
- **Production-Ready**:
  - Configurable summary length
  - Batch processing support

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/text-summarization.git
cd text-summarization

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

pip install -r requirements.txt
python -m spacy download en_core_web_sm
