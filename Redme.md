# Lenisha

> A GPT‑v1 architecture — a minimal/educational implementation of a GPT‑style language model.

## ✅ What is Lenisha

Lenisha is a lightweight GPT‑v1 style architecture written in a Jupyter Notebook (`gpt.ipynb`).  
It is designed for experimentation and learning — to help you understand how a transformer‑based language model works “under the hood,” without the complexity of large industrial codebases.  

## 🧠 Motivation & Goals

- To learn and demonstrate the core mechanics of transformer‑based language modeling.  
- To give other students / developers a simple, easy-to-follow reference implementation.  
- To explore custom modifications/experiments on a manageable scale (since this repo is small and self‑contained).  

## 📂 Repository Structure

```
Lenisha/
├── gpt.ipynb       ← Jupyter Notebook containing model code, training and inference logic
```

## Getting Started

### Prerequisites

- Python 3.x  
- Jupyter Notebook (or Jupyter Lab)  
- Typical ML / DL Python libraries (e.g. `torch`, `numpy`, etc.) — install based on your notebook’s imports  

### Running the Project

1. Clone the repo  
   ```bash
   git clone https://github.com/SulavGyawali/Lenisha.git
   cd Lenisha
   ```  
2. Open `gpt.ipynb` in Jupyter Notebook / Lab  
3. Follow the notebook: configure hyper‑parameters, run training / inference cells  

## ✨ What You Can Do

- Step through a minimal GPT‑v1 implementation to understand attention, tokenization, positional embeddings, forward pass, etc.  
- Modify architecture — change number of layers, embedding size, context length, etc.  
- Train on a small dataset for toy experiments (since the code is small).  
- Use as a learning base or starting point for custom NLP experiments.  

## ⚠️ Limitations / Known Issues

- This is **not** a production-grade model — it’s purely educational / experimental.  
- Trained results (if using small datasets) may not reflect real-world performance / language fluency.  
- No extensive dataset preprocessing, tokenizers, evaluation pipeline, or deployment setup (as of now).  

## 🚀 Future Ideas / To‑Dos

- Add a proper tokenizer / preprocessing pipeline.  
- Support saving & loading model weights.  
- Add training & evaluation scripts (outside notebook) for scalability.  
- Integrate example dataset and show sample generation outputs.  
- Improve docs with usage examples, sample outputs, limitations clearly listed.  




