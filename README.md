# Master's Thesis Project: Galaxy Classification with CNN and ViT Models

This repository contains the code and documentation for my Master's thesis on galaxy classification.

---

### Abstract

The amount of astronomical data collected by observatories has exponentially increased in recent years. Classifying astronomical objects captured through different observational methods is a crucial part of processing astronomical data. This thesis contributes to the field of galaxy classification by enhancing accuracy and exploring the relationship between data quality, model performance, and observational advancements.

The datasets used are **Galaxy10SDSS**, **Galaxy10DECals**, and a high-redshift sample of Galaxy10DECals. The methodology includes preprocessing images with techniques such as Supervised and Unsupervised Wiener Deconvolution, Chan-Vese segmentation, and Non-Local Means denoising. For multi-class classification, both **Convolutional Neural Networks (CNNs)** and **Vision Transformer (ViT)** models were applied. Generally, preprocessing improved model performance, with ViT being the best model in most cases, though CNN outperformed ViT for the high-redshift sample. The best preprocessing methods were **Non-Local Means Denoising** and **Supervised Wiener Deconvolution**. In terms of computational efficiency, Supervised Wiener Deconvolution was optimal, while ViT models were more efficient than CNNs.

---

### Methodology

- **Datasets**: Galaxy10SDSS, Galaxy10DECals, and high-redshift samples from Galaxy10DECals.
- **Preprocessing Techniques**: 
  - Supervised and Unsupervised Wiener Deconvolution
  - Chan-Vese Segmentation
  - Non-Local Means Denoising
- **Models Used**: Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs)
- **Key Findings**:
  - ViT models generally provided the best performance, except for high-redshift samples where CNNs performed better.
  - Best preprocessing techniques were Non-Local Means Denoising and Supervised Wiener Deconvolution.
  - For computational efficiency, Supervised Wiener Deconvolution was most efficient, and ViT models were faster than CNNs.

---

### Experimental Design

Below is a preview of the experimental design followed in this research project.

![Experimental Design](https://github.com/user-attachments/assets/711bed92-424d-4c25-a470-7cacd2ae0d58)

---

### Data Previews

**Original Images and Categories for Classification**  
These previews illustrate the original images and categories used for classification.

![Original Images and Categories](https://github.com/user-attachments/assets/d6c1f716-1040-4b4e-8fa0-e003d503e0ca)

---

**Masks Applied During Preprocessing**  
Here are examples of masks applied to the images during preprocessing.

![Applied Masks](https://github.com/user-attachments/assets/7b0f3a4f-e910-474e-a372-778f032e6813)

---

For more details, please refer to the code and detailed documentation in this repository.
