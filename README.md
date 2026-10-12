# 📊 Datasets

This project uses two industrial visual-inspection datasets to cover both **surface defects** and **structural/logical anomalies**.

---

## 1. MVTec LOCO AD

**MVTec LOCO AD (Logical Constraints Anomaly Detection)** is an industrial anomaly-detection dataset developed by **MVTec, Germany**.

The dataset was created specifically for evaluating computer-vision systems in **real-world-inspired industrial inspection scenarios**. It contains both **structural anomalies** such as scratches, dents, and contamination, and **logical anomalies** such as missing or incorrectly positioned components.

### Dataset Statistics

| Feature | Details |
|---|---|
| **Source** | MVTec, Germany |
| **Total Images** | 3,644 |
| **Categories** | 5 industrial categories |
| **Training Images** | 1,772 |
| **Validation Images** | 304 |
| **Test Images** | 1,568 |
| **Anomaly Types** | Structural + Logical |
| **Annotations** | Pixel-precise ground truth |

### What it is used for

MVTec LOCO AD is used in this project to detect:

- Scratches and dents
- Surface contamination
- Missing components
- Incorrect component positions
- Incorrect assembly / logical anomalies
- Other deviations from the expected product structure

The dataset contains images of distinct physical objects captured for industrial inspection scenarios, with anomaly-free training/validation images and anomalous test images. :contentReference[oaicite:0]{index=0}

**Official Source:** [MVTec LOCO AD](https://www.mvtec.com/research-teaching/datasets/mvtec-loco-ad)

---


## 🔗 Dataset Source Summary

| Dataset | Where the Data Comes From | Main Purpose |
|---|---|---|
| **MVTec LOCO AD** | MVTec industrial inspection scenarios, Germany | Structural + logical anomaly detection |


**MVTec LOCO AD → "Is the product structurally and logically correct?"**

**KolektorSDD2 → "Does the product have a visible surface defect?"**
