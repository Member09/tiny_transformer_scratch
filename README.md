# tiny_transformer_scratch
This project implements a minimal GPT-style Transformer model from scratch in PyTorch. 
The goal is to build a clean, transparent implementation of the key components that power large language models, enabling research and experimentation with scaling laws at a small scale.

---

## 📌 What This Project Does

- Implements a decoder-only Transformer from scratch
- Trains on a small dataset (Tiny Shakespeare)
- Allows variation of model size, depth, and training data
- Intended for educational and scaling law experimentation

---

## 🔍 Scaling Law Exploration

Try plotting:
- Loss vs model size
- Loss vs tokens
- Loss vs context length

This simulates Chinchilla and Kaplan findings on a micro-scale.

---

## 📚 References

- [Kaplan et al. (2020)](https://arxiv.org/abs/2001.08361)
- [Hoffmann et al. (2022)](https://arxiv.org/abs/2203.15556)
- [minGPT](https://github.com/karpathy/minGPT) by Karpathy
- [Transformers from Scratch](https://sebastianraschka.com/blog/2023/transformers-from-scratch.html)

---

## 🧠 Motivation

This is part of an AGI research learning journey to understand Transformer architecture and scaling from first principles.
