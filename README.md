# 🌊 Water Quality Classifier using PyTorch

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-red?logo=pytorch)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A deep learning-based binary classification project to predict water quality using a 3-layer dense neural network built in PyTorch, trained on normalized water quality data.

---

## 📁 Project Structure

```
DL-WaterQuality-Classifier/
├── DL_WaterQuality.ipynb  						  # Main training/testing notebook
├── water_quality.csv                             # Dataset file
├── requirements.txt                              # Python dependencies
├── README.md                                     # Project overview
└── .gitignore                                    # Git exclusion rules
```

---

## 📌 Features
- Clean and preprocess water quality dataset
- Normalize features
- Build and train a deep neural network in PyTorch
- Evaluate performance with accuracy and loss plots

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/shahsanjanav/DL-WaterQuality-Classifier.git
cd DL-WaterQuality-Classifier
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch the Notebook
```bash
jupyter notebook DL_WaterQuality.ipynb
```

---

## 🧠 Model Architecture
- Input Layer: Based on number of features
- Hidden Layers: Dense + ReLU + Dropout
- Output Layer: Sigmoid activation for binary classification
- Loss: Binary Cross Entropy Loss
- Optimizer: Adam

---

## 📊 Dataset
The `water_quality.csv` dataset contains multiple physical and chemical water parameters labeled for classification.

---

## 🛠 Built With
- [Python 3.10+](https://www.python.org/)
- [PyTorch](https://pytorch.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [pandas, numpy, sklearn, matplotlib](https://pypi.org/)

---

## 📄 License
MIT License © 2025 Sanjana Shah

---

## 👤 Author

**Sanjana Shah**  
✨ Machine Learning & Generative AI Enthusiast  
📫 Connect on [LinkedIn](https://www.linkedin.com/in/sanjanavshah)
GitHub: [@shahsanjanav](https://github.com/shahsanjanav)

---

⭐ If you like this project, consider starring it on GitHub!
