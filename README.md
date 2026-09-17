## Explainable AI-Based Brain Tumor Detection Using an Enhanced CNN Architecture

Project Overview
Brain tumor detection from Magnetic Resonance Imaging (MRI) plays a critical role in early clinical diagnosis. Standard CNNs often suffer from overfitting, lack of attention to localized tumor regions, and a black-box nature that hinders clinical trust.
To overcome these challenges, this project introduces an **enhanced CNN architecture** featuring:
- **Batch Normalization** for training stability and accelerated convergence.
- **CBAM (Convolutional Block Attention Module)** for channel-wise and spatial feature enhancement.
- **Dropout Regularization** to prevent overfitting and improve generalization.
- **Grad-CAM (Gradient-weighted Class Activation Mapping)** to generate visual activation maps highlighting regions responsible for model decisions.
The network classifies input brain MRI scans into **4 classes**:
1. **Glioma Tumor**
2. **Meningioma Tumor**
3. **Pituitary Tumor**
4. **No Tumor**
---
## 🏗️ Architecture Overview
                +------------------------+
                  |   Input Brain MRI      |
                  +-----------+------------+
                              |
                              v
                  +------------------------+
                  |  Image Preprocessing   |
                  +-----------+------------+
                              |
                              v
                  +------------------------+
                  |  Enhanced CNN Backbone |
                  |   - Conv2D + ReLU      |
                  |   - Batch Normalization|
                  |   - CBAM (Channel/Space|
                  |   - Dropout & Pooling  |
                  +-----------+------------+
                              |
        +---------------------+---------------------+
        |                                           |
        v                                           v

---

---

## ✨ Key Features

- **High Precision Classification**: Accurate multi-class detection across 4 primary MRI scan categories.
- **Attention Mechanism (CBAM)**: Dynamically focuses spatial and channel feature maps on pathologically relevant tumor areas.
- **Overfitting Protection**: Incorporates strategic Dropout layers and Batch Normalization for robust cross-validation.
- **Visual Interpretability**: Grad-CAM heatmaps enable radiologists to visually verify prediction logic.
- **Benchmark Evaluation**: Complete evaluation framework tracking Accuracy, Precision, Recall, F1-Score, Validation Loss, and Training Time.

---

## 📁 Repository Layout

---

## 🚀 Getting Started

### 1. Prerequisites
Ensure you have **Python 3.8+** installed along with `pip`. GPU access (CUDA) is recommended for faster training and gradient computation.

### 2. Clone the Repository
```bash
git clone https://github.com/your-username/brain-tumor-xai-detection.git
cd brain-tumor-xai-detection
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Linux / macOS:
source venv/bin/activate

pip install -r requirements.txt

Evaluation Metrics
Models are benchmarked using standard classification performance metrics:

Accuracy: Overall classification accuracy across all 4 target classes.
Precision: Proportion of positive identifications that were correct.
Recall (Sensitivity): Proportion of actual positives identified correctly.
F1-Score: Weighted harmonic mean of precision and recall.
Validation Loss: Loss convergence indicator during epoch training.
Training Time: Efficiency assessment compared against baseline CNNs.

References
S. Pereira et al., "Brain Tumor Segmentation Using Convolutional Neural Networks in MRI Images," IEEE TMI, 2016.
S. Woo et al., "CBAM: Convolutional Block Attention Module," ECCV, 2018.
S. Ioffe & C. Szegedy, "Batch Normalization: Accelerating Deep Network Training," ICML, 2015.
N. Srivastava et al., "Dropout: A Simple Way to Prevent Neural Networks from Overfitting," JMLR, 2014.
R. R. Selvaraju et al., "Grad-CAM: Visual Explanations from Deep Networks via Gradient-Based Localization," ICCV, 2017.
M. T. H. Khan et al., "Explainable CNN for Brain Tumor Detection," Brain Informatics, 2025.
A. Kumar et al., "Boosting Brain Tumor Detection with Optimized ResNet and Explainability," Scientific Reports, 2026.
A. Krizhevsky et al., "ImageNet Classification with Deep CNNs," NeurIPS, 2012.
B. Menze et al., "The Multimodal Brain Tumor Image Segmentation Benchmark (BraTS)," IEEE TMI, 2015.
D. Chicco & G. Jurman, "The Advantages of the Matthews Correlation Coefficient over F1 Score," BMC Genomics, 2020.
M. A. Rahman et al., "Enhancing Brain Tumor Detection Through Deep Learning and Explainable AI," Scientific Reports, 2026.
🏫 Academic Attribution
Institution: Vasireddy Venkatadri Institute of Technology (VVIT)
Department: Department of CSE - Artificial Intelligence & Machine Learning
Batch ID: AIML – C16
Project Category: Research Oriented
Project Guide: Mrs. K. Sushma
Project Team Members
Regd. No.	Student Name
23BQ1A61E2	Udatha Suvarna
23BQ1A61C2	Sammeta Lokeswari
24BQ5A6115	Shaik Heena Tabasum
24BQ5A6140	Thotakura Mahesh

