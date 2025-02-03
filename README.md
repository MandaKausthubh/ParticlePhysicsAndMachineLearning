# Particle Physics and Machine Learning

Welcome to the **ParticlePhysicsAndMachineLearning** repository! 🚀 This project explores the intersection of **Particle Physics** and **Machine Learning (ML)** by leveraging deep learning models for physics event classification.

## 🔬 Project Overview
This repository aims to apply modern **deep learning techniques** to analyze and classify particle physics events using publicly available datasets. The primary focus is on **electron-photon and quark-gluon classification** using models like **ResNet and VGG**.

## 📂 Repository Structure
```
ParticlePhysicsAndMachineLearning/
├── data/              # Datasets (not included, see setup)
├── models/            # Deep learning models
├── notebooks/         # Jupyter notebooks for analysis and training
├── scripts/           # Python scripts for data preprocessing & training
├── results/           # Model performance results
├── README.md          # Project documentation
├── requirements.txt   # Dependencies
└── .gitignore         # Ignored files (e.g., datasets, logs)
```

## ⚡ Getting Started

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/MandaKausthubh/ParticlePhysicsAndMachineLearning.git
cd ParticlePhysicsAndMachineLearning
```

### 2️⃣ Set Up the Environment
It's recommended to use a **virtual environment** (e.g., `venv` or `conda`):

```sh
python -m venv venv
source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 4️⃣ Download the Dataset
This project relies on **CERN open datasets**. Download the required dataset and place it inside the `data/` directory.

### 5️⃣ Train a Model
To train the ResNet model on Electron-Photon classification:
```sh
python scripts/train_resnet.py
```

### 6️⃣ Evaluate Performance
To evaluate a trained model:
```sh
python scripts/evaluate.py --model models/resnet.pth
```

## 🏆 Results & Achievements
- Implemented **ResNet-15** and **VGG-Net** architectures for classification.
- Achieved **78.2% accuracy** and **72.38% validation score** for **electron-photon classification**.
- Closely matched results from **CERN's ML4Sci GSOC project** with an **AUC score of 78.87%**.

## 🤝 Contributing
We welcome contributions! If you'd like to improve the project, follow these steps:
1. **Fork** the repository.
2. Create a **new branch**: `git checkout -b feature-branch`
3. **Commit** your changes: `git commit -m "Added new feature"`
4. **Push** to your fork: `git push origin feature-branch`
5. Open a **Pull Request** 🚀

## 📜 License
This project is licensed under the **MIT License**.

## 📩 Contact
For questions or collaborations, reach out to **[Manda Kausthubh](https://github.com/MandaKausthubh)**.

---
Let's push the boundaries of **Particle Physics & Machine Learning** together! ⚛️🤖


