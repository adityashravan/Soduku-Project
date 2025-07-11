# 🔢 AI-Powered Sudoku Solver 🧠📷

This project uses **Deep Learning** and **Computer Vision** to read and solve Sudoku puzzles from real-world images.

---

## 📌 Features

- 🧠 CNN-based digit classifier
- 🧾 Detects Sudoku grids from images
- 📦 Automatically splits into 81 cells
- 🔍 Classifies digits using a trained CNN model
- 🧩 Solves puzzles using recursive backtracking
- ✅ Handles noisy and skewed inputs

---


---

## 🚀 How It Works

### 1. Train the Digit Classifier
A CNN is trained on digit images (0–9) with augmentations.

```python
model.fit(datagen.flow(train_X, train_y, batch_size=32), epochs=30, ...)


