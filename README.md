# Juniperus Segmentation and CNN Bias Analysis

Deep learning-based segmentation of polymorphic *Juniperus* shrubs in high-mountain satellite imagery.

---

## Overview

Automatic mapping of shrub species such as *Juniperus communis* and *Juniperus sabina* is essential for monitoring high-mountain ecosystems and understanding landscape changes associated with climate change.

This project investigates different deep learning segmentation architectures for individual shrub detection in high-resolution aerial and satellite imagery.

The study compares semantic, instance and panoptic segmentation approaches, focusing on the texture bias of convolutional neural networks (CNNs) and their impact on shrub detection performance.

The project evaluates and compares the behavior of several state-of-the-art architectures, including Mask R-CNN, DeepLabV3+, PanopticFPN and PointRend.

---

## Models Evaluated

- Mask R-CNN
- DeepLabV3+
- PanopticFPN
- PointRend (instance segmentation)
- PointRend (semantic segmentation)

---

## Objectives

The main objective of this project is to compare the generalization and segmentation performance of different deep learning architectures for the detection of *Juniperus* shrubs.

Specific goals include:

- Evaluating instance, semantic and panoptic segmentation approaches.
- Analyzing CNN texture bias in polymorphic vegetation.
- Comparing in-domain and out-of-domain generalization.
- Measuring ecological metrics such as shrub density and crown coverage.
- Studying detection errors related to shrub size and landscape texture.
- Understanding how architectural differences influence shrub detection robustness.

---

## Technologies

- Python
- PyTorch
- Detectron2
- OpenCV
- Jupyter Notebook
- Google Colab

---

## Datasets

Two datasets were used during experimentation:

- **PI (Photo Interpretation Data)** for training and internal validation.
- **FW (Field Work Data)** for external evaluation and generalization analysis.

---

## Dataset and Annotations

Example of satellite imagery, manual polygon annotations and binary masks used during training.

![Dataset annotations](images/triptych_dataset_annotations.png)

---

## Model Comparison

Qualitative comparison between different segmentation architectures evaluated in the project.

Mask R-CNN achieved the most consistent performance for individual shrub detection.

![Model comparison](images/model_comparison_best_case.png)

---

## Challenging Scenarios and Generalization

Example of a difficult scenario where the evaluated architectures exhibit different behaviors under challenging terrain and boundary conditions.

![Challenging case](images/challenging_case_water_boundary.png)

---

## Repository Structure

```text
notebooks/   -> training and evaluation notebooks
images/      -> prediction examples and figures
report/      -> master's thesis report
```

---

## Report

The complete master's thesis report is included in the repository.

---

## Author

Ana Fuentes Rodríguez. 
BSc in Physics | MSc in Data Science and Computer Engineering
