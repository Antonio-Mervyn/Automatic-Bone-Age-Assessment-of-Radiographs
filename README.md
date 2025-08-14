# Automatic Bone Age Assessment of Radiographs

This project implements a deep learning–based system for **automatic bone age estimation** from hand and wrist radiographs. The goal is to assist radiologists and pediatricians by providing quick, objective, and consistent bone age predictions.

---

##  Repository Contents

| File | Description |
|------|-------------|
| **Determining Skeletal Age Using Deep Learning (3).pptx** | Presentation slides summarizing the project’s objectives, methodology, and results. |
| **Gradient Descent.ipynb** | Jupyter notebook containing the core implementation — data preprocessing, model training, and evaluation. |
| **Minor Project Report.docx** | Detailed project report covering background, methodology, dataset description, experiments, results, and conclusion. |
| **Minor Project SRS - Team 13 (1).pdf** | Software Requirements Specification document outlining functional and non-functional requirements. |
| **Model.zip** | Trained deep learning model saved for inference. |
---

##  Problem Statement

Bone age assessment is an important diagnostic process in pediatrics for evaluating a child’s growth and development. Traditionally, this is done manually by comparing radiographs against standardized reference atlases such as the **Greulich and Pyle** method.  
This project automates the process using **Convolutional Neural Networks (CNNs)**, reducing manual effort and increasing accuracy and reproducibility.

---

## ⚙️ Approach

- **Data Input**: Hand/wrist radiograph images from publicly available datasets.
- **Model Architecture**: A CNN-based regression model optimized using gradient descent.
- **Training & Evaluation**: Implemented in the `Gradient Descent.ipynb` notebook, including:
  - Data preprocessing and augmentation
  - Model training on labeled radiograph images
  - Evaluation using Mean Absolute Error (MAE) and visualization of predictions
- **Deployment Artifact**: The trained model is stored in `Model.zip` for re-use without retraining.

---
