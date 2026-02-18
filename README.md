# HSQP: A Plug-and-Play Symbolic–Quantized Framework for Time-Series Tokenization in Large Language Models

<p align="center">
  <b>Time-Series Tokenization · Symbolic Representation · Quantization · LLMs</b>
</p>

---

## 🔍 Overview

**HSQP** is a **plug-and-play symbolic–quantized framework** designed to convert continuous time-series into **compact, semantically meaningful token sequences** suitable for **Large Language Models (LLMs)**.

Unlike conventional discretization or neural-only tokenizers, HSQP integrates:

- **Symbolic aggregation** for temporal structure preservation  
- **Quantization** for numerical compactness  
- **Hierarchical tokenization** for scalable long-horizon forecasting  

HSQP can be seamlessly attached to existing forecasting architectures (e.g., PatchTST, TimeLLM) and LLM-based pipelines without retraining the backbone model.

---

## ✨ Key Contributions

- A unified **symbolic–quantized tokenization pipeline** for time-series  
- Plug-and-play compatibility with **LLMs and transformer forecasters**  
- Strong performance across **forecasting, compression, and reconstruction**  
- Interpretable and low-entropy token sequences  
- Minimal overhead and modular design  

---

## 🧱 Repository Structure

```text
Time-series-Tokenization-For-LLMs/
│
├── data/                    # Datasets (not tracked)
│   ├── raw/
│   └── processed/
│
├── src/                     # Core reusable modules
│   ├── tokenization/        # HSQP, ABBA, quantization
│   ├── datasets/            # Dataset loaders
│   ├── models/              # Model wrappers
│   ├── training/            # Training logic
│   ├── evaluation/          # Metrics & evaluation
│   └── utils/               # Utilities
│
├── experiments/
│   ├── configs/             # YAML experiment configs
│   └── results/             # Output logs (not tracked)
│
├── demos/                   # Reproducible notebooks
│   ├── LLM_ABBA_demo.ipynb
│   ├── PatchTST_HSQP_demo.ipynb
│   ├── TimeLLM_HSQP_demo.ipynb
│   └── TimeVQVAE_demo.ipynb
│
├── scripts/                 # Entry-point scripts
│   ├── preprocess.py
│   ├── train.py
│   └── evaluate.py
│
├── requirements.txt
├── LICENSE
└── README.md


## Installations
🔹 git clone https://github.com/shamsua/Time-series-Tokenization-For-LLMs.git  
🔹 cd Time-series-Tokenization-For-LLMs  
🔹 pip install -r requirements.txt  




