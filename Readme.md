# 🧠 AI vs Real Image Detector (PyTorch)

A deep learning–based image classification system that detects whether an image is **AI-generated** or **human-created**.

Built from scratch using **PyTorch**, trained on mixed real-world and AI-art datasets, and designed with clean inference and deployment in mind.

---

## 🔥 Why This Project Matters

With AI-generated content exploding everywhere, the ability to **verify authenticity** is no longer optional—it’s essential.

This project focuses on:
- Learning real vs AI visual patterns
- Building robust CNN pipelines
- Writing reusable inference code
- Thinking like a production ML engineer

---

## 🧩 Model Overview

- Framework: **PyTorch**
- Architecture: CNN-based classifier
- Classes:
  - `AI Art`
  - `Human Art`
- Input: RGB Images
- Output: Class + confidence score

---

## 📂 Dataset

The dataset consists of:
- AI-generated artwork
- Human-created artwork

Images are resized and normalized before training.

> ⚠️ Dataset not included due to size constraints.

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Anurag07-crypto/ai-vs-real-image-detector.git
cd ai-vs-real-image-detector
