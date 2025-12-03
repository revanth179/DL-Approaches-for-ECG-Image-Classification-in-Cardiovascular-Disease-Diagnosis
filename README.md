# ❤️ Customized CNN Architecture for ECG Image-Based Classification of Cardiovascular Diseases
### 📄 *Published in IEEE SSITCON 2024 | Deep Learning | Medical Image Classification*

**🔗 IEEE Paper Link:** https://ieeexplore.ieee.org/document/10796798/  
This repository contains the implementation, code, architecture diagrams, and documentation for our IEEE-published work on classifying cardiovascular diseases using **ECG images** through a customized Xception-based Convolutional Neural Network.

---

# 📸 Project Preview  


### **ECG Sample**
<img width="1032" height="757" alt="image" src="https://github.com/user-attachments/assets/d705f3c1-b3c2-4e44-9c99-19927168759e" />

### **ECG Preprocessing Workflow**  
<img width="760" height="619" alt="image" src="https://github.com/user-attachments/assets/faf70f63-37d4-40b9-8e36-2e79c8a61fc5" />

### **Customized Xception Architecture Flowchart**  
<img width="897" height="194" alt="image" src="https://github.com/user-attachments/assets/29640c89-6496-4fec-9ee0-59860abc346f" />


### **ROC Curve for All Classes**  
<img width="749" height="581" alt="image" src="https://github.com/user-attachments/assets/82e8c5bb-3d5d-449f-946e-b777bf70d513" />

---

# 🔍 1. Overview

Cardiovascular diseases remain the leading cause of mortality worldwide.  
Traditional ECG signal-based analysis loses crucial **spatial and structural patterns**.

To overcome this, our research:

- Converts ECG *signals into images*
- Applies deep-learning-based classification
- Introduces a **customized Xception CNN architecture**  
- Achieves superior accuracy compared to existing approaches

📌 According to the paper (Page 1–2) :contentReference[oaicite:4]{index=4}, the method preserves spatial-temporal ECG features better than raw signal models.

---

# ⭐ 2. Key Contributions

✔ Designed a **CNN architecture customized from Xception**, optimized for ECG image feature extraction  
✔ Built a complete **ECG preprocessing pipeline**: cropping, grayscale conversion, normalization, augmentation  
✔ Extracted deep features and trained ML classifiers (OneVsRest, Passive-Aggressive, Ridge, MLP, SGD, Decision Tree)  
✔ Achieved **98.43% accuracy**, the highest among compared models  
✔ Demonstrated superiority of **image-based ECG learning** over raw-signal approaches  

---

# 📂 3. Dataset

As described in Page 3 of the paper :contentReference[oaicite:5]{index=5}, the dataset consists of **800+ ECG images** across 4 cardiovascular conditions:

- **Myocardial Infarction**
- **Abnormal Heartbeat**
- **History of MI**
- **Normal**

---

# 🧠 4. Proposed Architecture

This research introduces a **Customized Xception-based Convolutional Neural Network (CNN)** specifically designed for ECG image classification.  
The architecture preserves spatial wave patterns (P-wave, QRS complex, T-wave) that often get lost in normal 1D ECG signal processing.

---

## 🩺 4.1 ECG Image Processing Workflow  

### 🔧 Preprocessing Steps:
- ECG image collection  
- Resizing  
- Cropping  
- Grayscale conversion  
- Data normalization  
- Data augmentation  
- Feeding into the customized Xception model  

---

# 📈 5. Experimental Results

The customized Xception model achieved **state-of-the-art accuracy** in classifying ECG images into four cardiovascular disease categories.  


| Model Name                    | Accuracy (%) |
| ----------------------------- | ------------ |
| **Customized Xception Model** | **98.43%**   |
| GAN-LSTM                      | 97.8%        |
| XGBoost                       | 92.0%        |
| VGG-16                        | 88.16%       |

# 🤖 6. Classifier Results (After Xception Feature Extraction)

After extracting deep ECG features using the customized Xception architecture, multiple machine learning classifiers were evaluated.

# 📌 6.1 Classifier Performance Table

| Classifier               | Accuracy | Precision | Recall | F1-Score |
| ------------------------ | -------- | --------- | ------ | -------- |
| **OneVsRest Classifier** | **0.81** | 0.77      | 0.76   | 0.76     |
| **Passive Aggressive**   | **0.81** | 0.78      | 0.78   | 0.78     |
| MLP Classifier           | 0.79     | 0.80      | 0.76   | 0.76     |
| Ridge Classifier         | 0.79     | 0.80      | 0.79   | 0.79     |
| SGD Classifier           | 0.78     | 0.75      | 0.76   | 0.75     |
| Decision Tree            | 0.75     | 0.75      | 0.75   | 0.73     |

---

# 🧠 7. Key Observations

✔ **Deep Feature Extraction Works Extremely Well**  
Xception-derived features significantly boost ML classifier performance, outperforming raw image and raw signal approaches.

✔ **Best Results from OneVsRest & Passive-Aggressive**  
Both algorithms achieved **81% accuracy**, striking a balance between speed and precision.

✔ **Decision Tree Performs Least Effectively**  
This indicates that ECG image complexity requires more advanced, non-linear models.

✔ **Hybrid DL + ML Pipeline is Highly Effective**  
Deep Xception features + traditional ML classifiers provide faster inference with strong accuracy.

✔ **Xception Remains the Strongest Model**  
Its architecture captures detailed spatial ECG patterns, making it superior to traditional CNNs and machine learning models.

---

## 🔗 Connect With Me

👨‍💻 **Revanth**  
🌐 LinkedIn: www.linkedin.com/in/revanthsaikumarmanyam  
💻 GitHub: https://github.com/revanth179 
