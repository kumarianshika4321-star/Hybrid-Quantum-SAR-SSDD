
# Quantum Image Representation–Based SAR Ship Detection

## Abstract

This repository presents a **research-oriented implementation of a Quantum Image Representation–based framework for Synthetic Aperture Radar (SAR) ship detection** using the **SAR Ship Detection Dataset (SSDD)**. The work investigates the feasibility of integrating **quantum-inspired image encoding techniques** with classical machine learning pipelines to enhance feature representation and detection performance in SAR imagery.

The proposed approach maps classical SAR images into **quantum state representations using amplitude-based encoding**, followed by hybrid quantum–classical processing and performance evaluation. Experimental results are analyzed using standard metrics and compared against classical baselines.

⚠️ *All quantum operations are simulated on classical hardware and are intended solely for academic and experimental research.*

---

## Keywords

Quantum Image Processing, SAR Imagery, Ship Detection, Hybrid Quantum–Classical Models, Remote Sensing, SSDD

---

## 1. Introduction

Synthetic Aperture Radar (SAR) imagery plays a crucial role in maritime surveillance due to its ability to operate under all-weather and day–night conditions. However, SAR images are characterized by speckle noise and complex backscatter patterns, making reliable ship detection challenging.

Quantum Image Processing (QIP) introduces novel paradigms for encoding and manipulating image data using quantum mechanical principles. This repository explores the application of **quantum image representation techniques** to SAR ship detection and evaluates their effectiveness in a hybrid quantum–classical framework.

---

## 2. Contributions

The main contributions of this work are:

* Design and implementation of a **quantum-inspired SAR image representation** using amplitude encoding
* Development of a **hybrid quantum–classical detection pipeline**
* End-to-end dataset loading, preprocessing, training, and evaluation workflow
* Quantitative performance evaluation using standard metrics
* Comparative analysis between quantum-inspired and classical approaches
* Research-ready experimental setup and visualization framework

---


## 3. Dataset Description

### SAR Ship Detection Dataset (SSDD)

The SSDD is a publicly available SAR dataset designed for ship detection research. It contains SAR images with annotated ship targets captured under diverse imaging conditions.

📌 **Due to size limitations, the dataset is not included in this repository.**

Official dataset source:

* [https://www.iceye.com/downloads/datasets](https://www.iceye.com/downloads/datasets)

### Dataset Placement

After downloading, place the dataset as:

```
data/raw/SSDD/
```

---

## 4. Methodology Overview

### 4.1 SAR Image Preprocessing

* Image normalization
* Resizing and formatting
* Noise-aware preprocessing

### 4.2 Quantum Image Representation

* Classical SAR images mapped to quantum states
* Amplitude-based quantum image encoding
* Quantum-inspired feature representation

### 4.3 Hybrid Quantum–Classical Model

* Quantum-encoded image features
* Classical ML/DL classifier
* End-to-end training and inference pipeline

---

## 5. Experimental Setup

* Dataset: SSDD
* Encoding Technique: Amplitude-based quantum image representation
* Evaluation Protocol: Train–test split
* Hardware: Classical simulation environment

---

## 6. Evaluation Metrics

Performance is evaluated using the following metrics:

* Accuracy
* Precision
* Recall
* F1-score

Comparative visualizations include:

* Metric comparison plots
* Precision–Recall curves
* Quantum-inspired vs Classical model comparisons

All results are stored in the `results/` directory.

---

## 7. Results and Analysis

The experimental results demonstrate the effectiveness of **quantum-inspired image representations** for SAR ship detection. Comparative analysis highlights differences in performance trends between classical and quantum-inspired approaches, supporting the feasibility of QIP concepts in remote sensing applications.

📊 Refer to:

```
results/plots/
results/comparisons/
```

---


## 8. Limitations

* Quantum computations are **simulated**, not executed on real quantum hardware
* Scalability is constrained by classical simulation resources
* Results are intended for **research validation**, not production deployment


## 9. Acknowledgements

* SAR Ship Detection Dataset (SSDD)
* Quantum Image Processing research community
* Open-source machine learning and quantum computing frameworks

---

