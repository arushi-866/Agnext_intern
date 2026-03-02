# **Core ML & Computer Vision Research**

---

## **Project Description**

This project delivers a **research-driven Computer Vision and Deep Learning platform** focused on:

- Model architecture experimentation  
- Image processing standardization  
- Custom model development  
- Deployment pipelines using **PyTorch** and **TensorFlow Serving**

The platform supports the complete lifecycle:

- Data Collection  
- Image Augmentation  
- Model Architecture Research  
- Training  
- Validation  
- Testing  
- Performance Benchmarking  
- Deployment  
- Monitoring  

The primary objective is to build **high-performance, production-ready computer vision models** while conducting structured research on **custom CNN architectures and transformer-based vision models**.


```plantuml
@startmindmap

title Core ML & Computer Vision Research

skinparam nodesep 20
skinparam ranksep 30
skinparam defaultFontSize 14
scale 0.8

* Core ML & CV Research


** Computer Vision Domains
*** Image Classification
**** Strawberry Quality Detection
**** Tea Leaves Health Classification
*** Image Processing
**** Camera Calibration
**** Image Standardization Pipeline
**** Color Normalization
**** Noise Reduction
*** Object Detection (Future Scope)
**** Bounding Box Prediction
**** YOLO / Custom CNN

** Model Architecture Research
*** CNN Architectures
**** Custom CNN Design
**** Residual Connections
**** Lightweight Models
*** Transformers
**** Vision Transformers (ViT)
**** Hybrid CNN + Transformer
**** Attention Mechanisms
*** Architecture Comparison
**** Accuracy
**** FLOPS
**** Latency
**** Model Size

** Data Engineering
*** Dataset Building
**** Strawberry Dataset
**** Tea Leaves Dataset
*** Image Augmentation
**** Rotation
**** Flipping
**** Brightness / Contrast
**** Gaussian Noise
**** Synthetic Data Generation
*** Train / Validation / Test Split


** Training Pipeline
*** PyTorch Implementation
*** TensorFlow Implementation
*** Hyperparameter Tuning
*** Early Stopping
*** Checkpointing
*** Experiment Tracking

** Testing & Validation
*** Accuracy
*** Precision / Recall
*** F1 Score
*** Confusion Matrix
*** Cross Validation
*** Model Robustness Tests


** Deployment
*** Model Export (ONNX / SavedModel)
*** TF Serving Deployment
*** PyTorch Model Serving
*** Docker Containerization
*** Inference API Setup


** Performance Benchmarks
*** Training Time
*** Inference Latency
*** GPU Utilization
*** Memory Consumption


** Research Goals
*** Compare CNN vs Transformer
*** Improve Tea Leaves Model Accuracy
*** Optimize Image Calibration Pipeline
*** Reduce Inference Time by X%
*** Publish Research Findings (Optional)

@endmindmap
```
---

## Core ML & Computer Vision Research

---

### **Projects Summary**

| **Attribute** | **Detail** |
|---------------|------------|
| **Project Duration** | 20 weeks (2026-03-01 to 2026-07-20) |
| **Objective** | Build a research-driven CV pipeline with custom architectures, transformer exploration, image calibration processing, and production-grade deployment. |
| **Key Deliverables** | Dataset pipelines · Custom CNN architectures · Transformer experimentation · Camera calibration system · Training & testing pipeline · Deployment via TF Serving · Final research report & demo |


```mermaid

gantt
  title Core ML & Computer Vision Research Projects Timeline
  dateFormat  YYYY-MM-DD
  axisFormat  %b %d
  excludes    weekends
  tickInterval 1week

  section Project 1 – Semantic Segmentation of Strawberry
  Dataset Collection & Annotation            :p1a, 2026-03-01, 7d
  Data Cleaning & Preprocessing              :p1b, after p1a, 5d
  Augmentation Pipeline Development          :p1c, after p1b, 5d
  Segmentation Model Architecture (U-Net / Custom) :p1d, after p1c, 10d
  Training & Validation                      :p1e, after p1d, 7d
  Performance Evaluation (IoU, Dice Score)   :p1f, after p1e, 5d
  Project 1 Milestone                        :milestone, m1, after p1f, 0d

  section Project 2 – Tea Leaves Detection (Classification)
  Dataset Structuring & Balancing            :p2a, 2026-04-20, 7d
  Image Standardization & Augmentation       :p2b, after p2a, 5d
  Baseline CNN Implementation                :p2c, after p2b, 7d
  Custom CNN / Transformer Experimentation   :p2d, after p2c, 10d
  Training, Testing & Validation             :p2e, after p2d, 7d
  Model Benchmarking & Optimization          :p2f, after p2e, 5d
  Project 2 Milestone                        :milestone, m2, after p2f, 0d

  section Project 3 – Camera Calibration & Image Standardization
  Calibration Research & Algorithm Study     :p3a, 2026-06-01, 7d
  Implementation (OpenCV Calibration)        :p3b, after p3a, 7d
  Image Normalization Pipeline Development   :p3c, after p3b, 7d
  Validation with Standard Reference Images  :p3d, after p3c, 5d
  Integration with ML Pipeline               :p3e, after p3d, 5d
  Final Testing & Optimization               :p3f, after p3e, 5d
  Project 3 Milestone                        :milestone, m3, after p3f, 0d

```
