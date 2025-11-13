# 🌟 A Region-Aware Multi-Modal Framework for Pedestrian Attribute Recognition  
### *Official Repository for the Springer LNCS Chapter (2025)*  
### https://link.springer.com/chapter/10.1007/978-3-032-04968-1_4

<p align="center">
  <img src="docs/figures/example_par_result.jpg" width="750" />
</p>

---

## 📘 About the Paper

This repository contains the code and experimental resources for the paper:

> **A Region-Aware Multi-Modal Framework for Pedestrian Attribute Recognition via CLIP and Graph Neural Networks**  
> *Mudasir Hussain, Daw-Tung Lin*  
> *In: Advances in Computer Vision, Pattern Recognition, and AI Systems (LNCS), Springer, 2025.*

🔗 **Springer Link:**  
https://link.springer.com/chapter/10.1007/978-3-032-04968-1_4

---

## 🚀 Summary of Our Contribution

Pedestrian Attribute Recognition (PAR) is essential for intelligent surveillance, multi-camera tracking, and human-centered video analytics. Traditional CNN-based PAR pipelines often fail to capture small, localized regions and inter-attribute dependencies.

Our paper introduces a **Region-Aware Multi-Modal Framework** that integrates:

### 🔹 1. CLIP-based Global Visual–Textual Alignment  
We use CLIP to extract semantically aligned image–text representations that generalize well even with limited training.

### 🔹 2. Region-Sensitive Human Part Extraction  
We emphasize discriminative regions (upper body, lower body, accessories) to capture small-scale attributes such as bags, hats, sleeves, colors, etc.

### 🔹 3. Graph Neural Networks for Attribute Reasoning  
An Attribute Relation Graph (ARG) models dependencies between attributes, improving consistency and reducing contradictions.

### 🔹 4. Multi-Modal Fusion  
We combine CLIP embeddings, regional features, and graph-based reasoning for robust attribute prediction.

---

## 📊 Key Results

Our framework improves PAR performance on major benchmarks:

| Dataset | mA | Accuracy | F1 | AUC |
|--------|----|----------|----|-----|
| **RAPv2** | ↑ | ↑ | ↑ | ↑ |
| **PA-100K** | ↑ | ↑ | ↑ | ↑ |

(*Add your actual numbers here*)

---

## 🧩 Repository Structure

