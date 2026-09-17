## Explainable AI-Based Brain Tumor Detection Using an Enhanced CNN Architecture

## 1. Project Overview

Brain tumor detection from MRI scans is an important task in medical diagnosis. This project proposes an Explainable AI-based brain tumor detection framework using an enhanced Convolutional Neural Network (CNN) architecture.

The proposed model integrates **Batch Normalization, Convolutional Block Attention Module (CBAM), and Dropout** to improve training stability, focus on important tumor-related regions, and reduce overfitting. **Grad-CAM** is used to provide visual explanations for the model's predictions.

The system classifies brain MRI images into four categories:

* Glioma
* Meningioma
* Pituitary Tumor
* No Tumor

---

## 2. Problem Statement

Traditional CNN-based brain tumor classification models may face problems such as overfitting, limited focus on tumor-specific regions, and lack of interpretability.

Therefore, this project aims to develop an enhanced CNN model that improves classification performance while providing visual explanations of the regions influencing the model's predictions.

---

## 3. Objectives

* Develop a CNN-based brain tumor classification system.
* Classify MRI images into four tumor categories.
* Improve model training using Batch Normalization.
* Use CBAM to focus on important channel and spatial features.
* Apply Dropout to reduce overfitting.
* Use Grad-CAM for visual interpretation of predictions.
* Compare the enhanced CNN with a baseline CNN model.
* Evaluate the models using standard performance metrics.

---

## 4. Proposed Methodology

The proposed system follows these main steps:

1. **Dataset Collection**
   Collect and organize brain MRI images belonging to four classes.

2. **Data Preprocessing**
   Resize and normalize MRI images and prepare them for model training.

3. **Data Augmentation**
   Apply suitable augmentation techniques to improve model generalization.

4. **Baseline CNN Model**
   Develop a conventional CNN model as a baseline for comparison.

5. **Enhanced CNN Model**
   Integrate Batch Normalization, CBAM, and Dropout into the CNN architecture.

6. **Model Training**
   Train the baseline and enhanced CNN models using the prepared MRI dataset.

7. **Model Evaluation**
   Compare model performance using accuracy, precision, recall, F1-score, validation loss, and training time.

8. **Explainability using Grad-CAM**
   Generate heatmaps showing the important regions of MRI images that contribute to the model's prediction.

---

## 5. System Workflow

```text
Brain MRI Dataset
        ↓
Image Preprocessing
        ↓
Data Augmentation
        ↓
Baseline CNN
        ↓
Enhanced CNN
(Batch Normalization + CBAM + Dropout)
        ↓
Model Training
        ↓
Four-Class Classification
        ↓
Performance Evaluation
        ↓
Grad-CAM Visualization
        ↓
Interpretable Prediction
```

---

## 6. Enhanced CNN Architecture

The proposed CNN architecture is enhanced using three important components:

### Batch Normalization

Batch Normalization improves training stability and helps the model converge more effectively.

### CBAM

The Convolutional Block Attention Module (CBAM) combines **channel attention and spatial attention** to help the network focus on important features and tumor-related regions.

### Dropout

Dropout is used as a regularization technique to reduce overfitting and improve the model's ability to generalize to unseen MRI images.

---

## 7. Explainable AI Using Grad-CAM

Grad-CAM (Gradient-weighted Class Activation Mapping) is used to explain the predictions made by the CNN model.

It generates a visual heatmap highlighting the important regions of an MRI image that contribute to the predicted class. This helps make the model's decision more understandable and interpretable.

---

## 8. Classification Classes

| Class           | Description                                                |
| --------------- | ---------------------------------------------------------- |
| Glioma          | Brain tumor originating from glial cells                   |
| Meningioma      | Tumor commonly developing around the brain and spinal cord |
| Pituitary Tumor | Tumor associated with the pituitary gland                  |
| No Tumor        | MRI image without a brain tumor                            |

---

## 9. Technologies Used

* **Programming Language:** Python
* **Deep Learning:** TensorFlow / Keras
* **Image Processing:** OpenCV
* **Data Processing:** NumPy, Pandas
* **Visualization:** Matplotlib
* **Explainable AI:** Grad-CAM
* **Development Environment:** Google Colab / VS Code
* **Version Control:** Git and GitHub

---

## 10. Evaluation Metrics

The performance of the baseline CNN and enhanced CNN will be evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Validation Loss
* Training Time

These metrics will be used to compare the classification performance and training behavior of both models.

---

## 11. Expected Outcome

The proposed system is expected to provide accurate classification of brain MRI images into four categories. The enhanced CNN is designed to improve feature learning and reduce overfitting through Batch Normalization, CBAM, and Dropout.

Grad-CAM visualizations will provide an interpretable explanation of the model's predictions by highlighting important MRI regions.

---

## 12. Project Plan

| Phase   | Work                                            |
| ------- | ----------------------------------------------- |
| Phase 1 | Literature survey and study of existing methods |
| Phase 2 | Dataset collection and preprocessing            |
| Phase 3 | Development of baseline CNN                     |
| Phase 4 | Development of enhanced CNN                     |
| Phase 5 | Model training and evaluation                   |
| Phase 6 | Grad-CAM implementation                         |
| Phase 7 | Comparison and analysis                         |
| Phase 8 | Documentation and final project preparation     |

---

## 13. Repository Structure

```text
ExplainableAI-BasedBrainTumorDetectionusinganEnhancedCNNArchitecture/
│
├── Abstract/
│   └── Abstract.md
│
├── Dataset/
│
├── Models/
│
├── Notebooks/
│
├── Results/
│
├── GradCAM/
│
├── References/
│
├── README.md
│
└── requirements.txt
```

---

## 14. Base Paper

**Title:** *Enhancing Brain Tumor Detection Through Deep Learning and Explainable AI Techniques*

**Year:** 2026

The base paper provides the foundation for studying deep learning-based brain tumor detection and Explainable AI techniques. The proposed project extends the research idea by developing an enhanced CNN architecture using Batch Normalization, CBAM, Dropout, and Grad-CAM.

---

## 15. References

1. *Enhancing Brain Tumor Detection Through Deep Learning and Explainable AI Techniques*, 2026.
2. Selected recent research paper on Explainable AI-based brain tumor detection, 2025.
3. Selected recent research paper on deep learning-based brain tumor classification, 2026.
4. Selected recent research paper on Explainable AI and medical image classification, 2024.

---

## 16. Team Members
1.Udatha Suvarna
2.Sammeta Lokeswari
3.Shaik Heena Thabasum
4.Thotakura Mahesh

---

