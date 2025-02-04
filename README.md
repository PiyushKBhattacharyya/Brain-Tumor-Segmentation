# Brain Tumor Segmentation using U-Net

## Overview
This project implements a **U-Net-based deep learning model** for **automatic brain tumor segmentation** using MRI scans. The model is trained on the **BraTS 2020 dataset** to segment different tumor regions, including:
- **Necrotic core (NEC)**
- **Edema (ED)**
- **Enhancing tumor (ET)**

The primary goal is to assist in **computer-aided diagnosis** by providing accurate tumor segmentation from MRI images.

## Dataset
- **Name:** BraTS 2020
- **Modalities:** T1, T1ce, T2, FLAIR
- **Annotations:** Ground truth labels for different tumor regions

## Methodology
1. **Data Preprocessing**
   - MRI scans are normalized.
   - Data augmentation techniques applied to enhance generalization.
2. **Model Architecture**
   - **U-Net** with encoder-decoder structure.
   - Skip connections for preserving spatial features.
3. **Training Process**
   - Loss Function: **Dice Coefficient Loss**
   - Optimizer: **Adam**
   - Evaluation Metrics: **Dice Score, IoU, Precision, Recall**
4. **Inference**
   - Generates segmented tumor regions from input MRI scans.


## Installation & Usage
### Prerequisites
- Python 3.8+
- TensorFlow / PyTorch
- Numpy, OpenCV, Matplotlib
- SimpleITK for NIfTI processing
## Acknowledgments
- **BraTS 2020 Dataset** (MICCAI)
- **U-Net Architecture** by Ronneberger et al.

---
### ⭐ Star this repository if you find it useful!

