# Particle Physics and Machine Learning

Welcome to the **ParticlePhysicsAndMachineLearning** repository! 🚀 This project explores the intersection of **Particle Physics** and **Machine Learning (ML)** by leveraging deep learning models for physics event classification.

## 🔬 Project Overview
This repository aims to apply modern **deep learning techniques** to analyze and classify particle physics events using publicly available datasets. The primary focus is on **electron-photon** using models like **ResNet**.

## ⚡ Getting Started

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/MandaKausthubh/ParticlePhysicsAndMachineLearning.git
cd ParticlePhysicsAndMachineLearning
mkdir data
cd data
curl -o Photon.hdf5 https://cernbox.cern.ch/remote.php/dav/public-files/AtBT8y4MiQYFcgc/SinglePhotonPt50_IMGCROPS_n249k_RHv1.hdf5
curl -o Electron.hdf5 https://cernbox.cern.ch/remote.php/dav/public-files/FbXw3V4XNyYB3oA/SingleElectronPt50_IMGCROPS_n249k_RHv1.hdf5
cd ..
```


### ⚙️ Creating an Environment

Please note that this uses conda to create and manage the environment.
```sh
conda env create -f environment.yml
conda activate ML4Sci
```

## Achievemets:

This successfully replicates the predictions of the paper: **[E2E CMS](End-to-End Physics Event Classification with CMS Open Data: Applying Image-Based Deep Learning to Detector Data for the Direct Classification of Collision Events at the LHC
)** paper. Achieved an AOC Score of **78.93 %** (the paper predicts **79%**). This is one of the best results in this problem setup it the world!!

Acknowledgement: CMS Data CERN

## 📩 Contact
For questions or collaborations, reach out to **[Manda Kausthubh](https://github.com/MandaKausthubh)**.

---
Let's push the boundaries of **Particle Physics & Machine Learning** together! ⚛️🤖


