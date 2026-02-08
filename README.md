# Fruits & Vegetables Classification

A production-ready Python project that trains, evaluates, and serves a CNN classifier to distinguish fruits vs vegetables from images.

This repo demonstrates:<br>
✅ dataset preprocessing & augmentation  
✅ modular PyTorch model training  
✅ performance evaluation with metrics & confusion matrix  
✅ tests and reproducibility  
✅ containerized inference  

---

## 🧠 Overview
Computer vision model built using PyTorch to classify images into fruit or vegetable categories.  
Focuses on clean code, reproducibility, and clear experiment tracking.

---

## 📊 Dataset

- Images categorized into fruit and vegetable classes
- Dataset organized using folder-based class labels
- Standard train/validation split
- Basic augmentations applied (resize, normalization)

Note: Dataset is not included in the repo due to size constraints.

---

## 📁 Project Structure
- `data/`: raw and processed images  
- `notebooks/`: exploratory training and visualization  
- `src/`: reusable Python modules  
- `models/`: trained checkpoints  
- `outputs/`: results and logs  
- `tests/`: unit tests  
- `Dockerfile`: container for inference  

```
Fruits-Vegetables-Classification/
├── data/
│   ├── raw/                    # original dataset
│   ├── processed/              # resized/augmented images
├── notebooks/                  # experiments, EDA
│   └── training.ipynb
├── src/                       # reusable code
│   ├── dataset.py
│   ├── model.py
│   ├── train.py
│   └── eval.py
├── models/                    # checkpoints, final saved models
│   └── best_model.pth
├── outputs/                   # results (metrics, confusion matrices, logs)
├── tests/                    # unit tests for data/model components
├── Dockerfile                # containerize training/inference
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🚀 Getting Started

**1) Clone & install**
```bash
git clone https://github.com/AnmolBennett/Fruits-Vegetables-Classification
cd Fruits-Vegetables-Classification
pip install -r requirements.txt
