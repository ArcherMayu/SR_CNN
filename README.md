# 🖼️ Image Super-Resolution using SRCNN

This project implements **Super-Resolution Convolutional Neural Networks (SRCNN)** to enhance the resolution of low-quality images. It was developed in Python using **TensorFlow/Keras** and tested through a Jupyter Notebook.

---

## 📌 Objective
- To improve image resolution using deep learning techniques.  
- Compare low-resolution inputs with reconstructed high-resolution outputs.  
- Analyze performance using metrics like **PSNR** and **MSE**.

---

## 📂 Project Structure
├── SR_CNN.ipynb # Jupyter Notebook with full implementation
├── data/ # Training/testing dataset
├── results/ # Generated high-resolution images
└── README.md # Project documentation



---

## 🚀 Features
- Implements **SRCNN** model for image super-resolution.  
- Trains on sample dataset (you can use DIV2K, Set5, or your own dataset).  
- Visualizes **low-resolution vs super-resolved vs ground-truth** images.  
- Evaluates with quantitative metrics.  

---

## 🛠️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/SR-CNN.git
cd SR-CNN
pip install -r requirements.txt
```



Requirements

Python 3.x
TensorFlow / Keras
NumPy, Matplotlib, OpenCV, scikit-image





📊 Dataset

You can use datasets such as:

DIV2K Dataset
ADNI
Or test on your own images by placing them inside data



 
Model Architecture (SRCNN)

Conv Layer 1: Extracts patches & features

Conv Layer 2: Non-linear mapping

Conv Layer 3: Reconstructs high-resolution image




