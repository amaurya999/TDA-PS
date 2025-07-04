# Persistence Statistics Feature Generator

[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-370/)

This repository contains code and data used to generate **TDA-based Persistence Statistics features** from binary images, as described in the paper [_Hybrid Topological Data Analysis and Deep Learning for Basal Cell Carcinoma Diagnosis_](https://link.springer.com/article/10.1007/s10278-023-00924-8).

---

## 📁 Repository Structure

- **`TDA_PS_sample_images/`**  
  Contains sample binary images used for feature extraction.

- **`persistence_statistics_1D code.ipynb`**  
  Jupyter notebook to generate Persistence Statistics features.  
  👉 **Before running**, update the image path and CSV save location at the end of the notebook.

- **`sample_features/`**  
  Folder containing the generated feature CSV files. You can inspect these to see what features look like.

- **`py37.yaml`**  
  Conda environment file for installing dependencies.

---

## 🛠️ Setup Instructions

Install the conda environment from the provided YAML file:

```bash
conda env create -f py37.yaml