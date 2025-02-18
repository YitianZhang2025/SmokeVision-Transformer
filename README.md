# **Dynamic Smoke Recognition Network (DSRN)**
**Multi-Scale Spatial Fusion Transformer with Attention Refinement for Smoke Detection**

## **Overview**
Smoke detection is a critical component of fire prevention systems, requiring accurate and timely identification of smoke patterns in complex and dynamic environments. Traditional smoke detection approaches often suffer from false positives, delayed detection, and environmental variability.

The **Dynamic Smoke Recognition Network (DSRN)** is a novel deep learning framework designed for **real-time smoke detection** in diverse environments. It leverages **multi-scale spatial fusion** and **transformer-based attention mechanisms** to enhance detection accuracy, reduce false alarms, and improve robustness across different conditions.

## **Key Features**
**Multi-Scale Spatial Fusion** – Extracts fine-grained local details and global smoke patterns.  
**Transformer-Based Attention Refinement** – Enhances feature learning for robust smoke detection.  
**Context-Aware Optimization Strategy (CAOS)** – Integrates domain-specific data augmentation and temporal consistency constraints.  
**Indoor & Outdoor Adaptability** – Effectively detects smoke under challenging environmental conditions.  
**Superior Performance** – Achieves state-of-the-art results on benchmark datasets and real-world scenarios.  

## **Architecture**
The **DSRN framework** consists of the following key components:
1. **Multi-Scale Feature Extraction:** Captures smoke patterns at different scales.
2. **Hierarchical Transformer-Based Attention:** Refines feature representations for accurate smoke recognition.
3. **Temporal Consistency Constraints:** Ensures stable detection across video frames.
4. **Context-Aware Optimization Strategy (CAOS):** Enhances generalization and robustness using domain-specific augmentation.

## **Installation & Setup**
### **Prerequisites**
Ensure you have the following dependencies installed:
```bash
pip install torch torchvision transformers opencv-python numpy matplotlib
