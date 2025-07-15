# 🧙‍♂️ ImageWizard – Interactive Image Processing Suite

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-orange?logo=python)

ImageWizard is a full-featured desktop application for image processing, built with Python and Tkinter. It offers a clean GUI and powerful features such as blurring, noise addition, histogram operations, edge detection, enhancement filters, and even lossless image coding using Huffman and Golomb algorithms.

---

## ✨ Features

### 🧰 Filters

* Blur
* Gaussian
* Median
* Max & Min Filters
* Adaptive Median

### 🎯 Edge Detection

* Sobel Operator
* Laplacian Operator
* Roberts Cross

### 🧪 Noise Injection

* Gaussian Noise
* Salt & Pepper Noise

### 📈 Histogram Processing

* Histogram Equalization
* Histogram Specification

### 🫲 Interpolation

* Nearest Neighbor
* Bilinear Interpolation

### 🔐 Image Coding

* Huffman Coding (with compression ratio display)
* Golomb Coding

### 💡 Enhancement

* Unsharp Masking
* Highboost Filtering

### ⚡ Frequency Domain

* Discrete Fourier Transform (DFT)
* High-Pass Filtering in Frequency Domain

---

## 🖼️ GUI Preview

> The application provides a responsive, dark-themed interface where users can:
>
> * Load and view images
> * Apply any transformation with one click
> * Compare original vs. edited output
> * Save the edited image

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/imagewizard.git
cd imagewizard
pip install -r requirements.txt
python main.py
```

> 📌 Requirements: Python 3.10+, PIL, NumPy, Matplotlib

---

## 📁 Project Structure

```
├── main.py               # The main GUI and image processing engine
├── Report.pdf            # Full technical documentation and math
└── README.md             # You're here!
```

---

## 📖 Documentation

A detailed technical report (`Report.pdf`) is included, covering:

* Mathematical foundation of each algorithm
* Implementation code snippets
* Experimental results and examples

