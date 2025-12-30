# An Explainable AI based Plant Disease Identification using a Two-Stage Detection-Classification Pipeline

[![Project Page](https://img.shields.io/badge/Project-Page-green?style=for-the-badge&logo=googlechrome&logoColor=white)](https://YOUR_USERNAME.github.io/YOUR_REPO_NAME) 
[![Kaggle](https://img.shields.io/badge/Kaggle-Code-blue?style=for-the-badge&logo=kaggle&logoColor=white)](YOUR_KAGGLE_LINK_HERE) 
[![Conference](https://img.shields.io/badge/ICCIT-2025-red?style=for-the-badge)](https://iccit.org.bd/2025/)

**Official implementation of the paper presented at the 2025 28th International Conference on Computer and Information Technology (ICCIT).**

> **Abstract:** Plant disease looms over global food security as a significant threat. Despite this, accurately identifying diseases from images taken in real-world field conditions remains a major challenge. Standard classification models often fail in scenarios with complex backgrounds, variable lighting, and image noise. To address this, this study proposes a robust two-stage detection-classification pipeline using YOLOv11n and ECA-NFNet-L0.

---

## 🏗️ Overview

<p align="center">
  <img src="static/images/teaser.jpg" width="70%" alt="Pipeline Architecture">
</p>

Our method decouples localization from classification to handle complex backgrounds effectively:

1.  **Stage 1 (Localization):** A **YOLOv11n** object detector locates and crops leaf areas, achieving a mAP@0.5 of **92.9%**.
2.  **Stage 2 (Classification):** Cropped leaves are processed by an **ECA-NFNet-L0** framework with efficient channel attention.

**Results on PlantDoc Dataset:**
* **Accuracy:** 78.5%
* **Weighted F1-score:** 78.4%

---

## 🚀 Getting Started

### Prerequisites
The code is hosted on Kaggle for easy reproducibility. You do not need to set up a local environment if you run the notebook directly.

### Running the Code
Click the button below to access the full training and inference pipeline:

[<img src="https://kaggle.com/static/images/open-in-kaggle.svg" height="40"/>](YOUR_KAGGLE_LINK_HERE)

---

## 📂 Dataset
We utilized the **PlantDoc** dataset for training and evaluation.
* **Original Dataset:** [Link to PlantDoc](https://github.com/pratikkayal/PlantDoc-Dataset)
* **Preprocessing:** Details on augmentation and resizing are available in the notebook.

---

## 📝 Citation
**Coming Soon.** The full BibTeX citation and IEEE Xplore link will be added here once the conference proceedings are available online. 

*Presented at ICCIT 2025, Cox’s Bazar, Bangladesh (December 19-21, 2025).*

---

## 📧 Contact
For questions or collaboration, please reach out to:
* **Tahir Hasan**: tahir.hasan.thk@gmail.com
