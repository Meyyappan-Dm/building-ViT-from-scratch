# 🧠 Vision Transformer (ViT) from Scratch - CIFAR-10

This project implements a Vision Transformer (ViT) from scratch using PyTorch and trains it on the CIFAR-10 dataset.
Inspired by the "Attention Is All You Need" paper and the original ViT model, the goal was to deeply understand transformer-based vision models by building all components manually— from patch embedding to encoder stacks.

---

## 📌 Features

- Built entirely from scratch (no high-level ViT libraries used)
- Patch embedding using `einops`
- Custom multi-head attention and encoder block
- Classification head with positional encoding
- Trained on CIFAR-10 with 224×224 resized inputs
- Visualization of training loss per epoch

---

## 🧱 Architecture Overview

- **Patch size**: 16×16
- **Image size**: 224×224 (resized from 32×32)
- **Latent size**: 768
- **Number of heads**: 12
- **Number of encoder blocks**: 12
- **Number of classes**: 10 (CIFAR-10)
- **Dropout**: 0.1

---

## 🧪 Results

- Trained for **5 epochs**
- Final training loss: **~2.47**
- Training curve plotted using `matplotlib`
- Goal was to understand model building, not to optimize accuracy

## What I Learned

      How Vision Transformers process images using patch embeddings

      Building custom encoder blocks and attention layers in PyTorch

      Differences between CNNs and Transformers for vision tasks

      Performance trade-offs when training large models on small datasets
