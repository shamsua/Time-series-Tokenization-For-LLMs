# HSQP: A Plug-and-Play Symbolic–Quantized Framework for Time-Series Tokenization in Large Language Models

<p align="center">
  <b>Time-Series Tokenization · Symbolic Representation · Quantization · LLMs</b>
</p>

---

## HSQP Tokenization Pipeline

The figure below illustrates the **HSQP (Hierarchical Symbolic–Quantized Pipeline)** workflow for converting continuous time-series into token sequences for Large Language Models (LLMs). It shows the key stages: symbolic aggregation, quantization, and hierarchical tokenization.

<img src="figures/HSQP_Vizualization.png" alt="HSQP Pipeline" width="700"/>

<p align="center"><em>Figure 1: Overview of the HSQP tokenization pipeline, showing data flow from raw time-series to tokenized sequences ready for LLM integration.</em></p>

---

## 🔍 Overview

**HSQP** is a **plug-and-play symbolic–quantized framework** designed to convert continuous time-series into **compact, semantically meaningful token sequences** suitable for **Large Language Models (LLMs)**.

Unlike conventional discretization or neural-only tokenizers, HSQP integrates:

- **Symbolic aggregation** for temporal structure preservation  
- **Quantization** for numerical compactness  
- **Hierarchical tokenization** for scalable long-horizon forecasting  

HSQP can be seamlessly attached to existing forecasting architectures (PatchTST, TimeLLM, TimeCMA) and LLM-based pipelines without retraining the backbone model.

---

## ✨ Key Contributions

- A unified **symbolic–quantized tokenization pipeline** for time-series  
- Plug-and-play compatibility with **LLMs and transformer forecasters**  
- Strong performance across **forecasting, compression, and reconstruction**  
- Interpretable and low-entropy token sequences  
- Minimal overhead and modular design  

---

## Installations
🔹 git clone https://github.com/shamsua/Time-series-Tokenization-For-LLMs.git  
🔹 cd Time-series-Tokenization-For-LLMs  
🔹 pip install -r requirements.txt  

## Acknowledgement
This work builds upon prior advances in symbolic time-series representation, quantization, and transformer-based forecasting.

