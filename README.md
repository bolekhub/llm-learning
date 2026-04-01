## 🚀 How to run it
 
### Option 1 — Google Colab (easiest, free, PyTorch pre-installed) ✅
 
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bolekhub/llm-learning/blob/main/transformer_block.ipynb)
 
Or manually:
1. Go to [colab.research.google.com](https://colab.research.google.com)
2. **File → Upload notebook** → upload `transformer_block.ipynb`
3. **Run all cells** — no setup needed ✅
 
### Option 2 — Local
 
```bash
pip install torch jupyter
jupyter notebook transformer_block.ipynb
```
 
### Option 3 — JupyterLite (jupyter.org/try)
 
> ⚠️ PyTorch does **not** work in browser-based JupyterLite environments. Use Colab instead.
 
---
 
## 📖 Article Series
 
This repo is the code companion to the **Demystifying LLMs** series on LinkedIn — written for developers, from a developer still figuring it out.
 
- [Tokenization, Embeddings & Attention](#) — *the building blocks*
- [What happens inside a Transformer block?](#) — *Q, K, V, FFN, and why it all repeats*
- *(coming soon)* Training, loss functions & backpropagation
 
---
 
## 🛠 Requirements
 
```
torch >= 2.0
```
 
No other dependencies. Pure PyTorch — no HuggingFace, no abstractions.
 
