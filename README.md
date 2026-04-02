# SAR Ship Detection using U-Net

This project focuses on detecting ships in Synthetic Aperture Radar (SAR) images using the **U-Net deep learning model**. The model is trained and evaluated on multiple datasets to analyze its performance across different SAR image distributions.

---

## Overview

* Ship detection using SAR imagery
* Implemented using **U-Net (Segmentation Model)**
* Evaluated on **multiple datasets (HRSID & SSDD)**
* Focus on improving segmentation accuracy

---

## Model Used

### U-Net (Segmentation)

* Pixel-level ship detection
* Encoder-decoder architecture
* Effective for medical & SAR image segmentation
* Applied on both datasets for performance comparison

---

##  Datasets Used

###  HRSID Dataset

* High-resolution SAR images
* Used for training and evaluating segmentation performance

###  SSDD Dataset

* Standard SAR ship detection dataset
* Used to validate model generalization

> ⚠️ Datasets are not included in this repository due to size constraints.

---

##  Project Files

* `UnetHRSIDDATASET.ipynb` → U-Net on HRSID dataset
* `HSSD.ipynb` → U-Net on SSDD dataset

---

##  Tech Stack

* Python
* PyTorch
* OpenCV
* NumPy
* Google Colab

---

## Features

* U-Net based SAR image segmentation
* Multi-dataset training and testing
* Mask generation for ship detection
* Model evaluation and visualization

---

## Results

* U-Net successfully identifies ship regions in SAR images
* Performance tested across HRSID and SSDD datasets
* Demonstrates model generalization across datasets

---

## How to Run

1. Open notebooks in Google Colab
2. Mount Google Drive for dataset access
3. Run cells sequentially

---

## Future Improvements

* Improve precision and recall
* Data augmentation for better generalization
* Hyperparameter tuning
* Deploy as a web-based application

---

## Author

**Susmitha VG**
🔗 https://github.com/VGSusmitha22

---

⭐ If you found this useful, consider giving a star!
