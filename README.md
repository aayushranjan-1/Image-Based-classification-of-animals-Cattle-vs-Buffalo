🐄 Image-Based classification of animals cattle vs buffalo
# 🐄 Image-Based Classification of Animals: Cattle vs Buffalo

This project is a deep learning-based image classification system developed for automatic cattle and buffalo identification using image processing and transfer learning techniques. The system helps classify animals into two categories — Cow and Buffalo — from images using CNN and advanced deep learning models.

This capstone project was developed as part of the final-year B.Tech Computer Science curriculum at Lovely Professional University under the guidance of Anchal Kaundal. The project demonstrates the practical implementation of Convolutional Neural Networks (CNN), Transfer Learning, Attention Mechanisms, and Computer Vision in real-world agricultural and livestock applications :contentReference[oaicite:0]{index=0}.

---

## 📌 Project Objective

The main objective of this project is to build an intelligent image-based binary classification system that can accurately identify whether the input animal image belongs to a Cow or a Buffalo.

Traditional livestock identification is time-consuming and requires expert knowledge. This system automates the process using Artificial Intelligence and Deep Learning.

The project aims to:

- Reduce manual effort in livestock identification
- Improve classification accuracy using deep learning
- Support livestock management and agricultural decision-making
- Apply transfer learning for faster and more efficient model training
- Enable future deployment on edge devices and smart farming systems

---

## 🧠 Models Used

This project uses multiple deep learning models for comparative analysis:

### 1. Custom Baseline CNN
A traditional Convolutional Neural Network built from scratch and trained completely on the project dataset.

### 2. MobileNetV2 (Transfer Learning)
A lightweight and highly efficient pretrained CNN model used for faster training and better accuracy.

### 3. ResNet50 (Transfer Learning)
A deep residual network used to solve vanishing gradient problems and improve feature extraction.

### 4. CNN with Morphological Feature Fusion
A hybrid model combining deep learning features with handcrafted features like HOG, aspect ratio, solidity, and spatial extent.

### 5. Attention-Based CNN with CBAM
The proposed advanced model using Convolutional Block Attention Module (CBAM) for channel attention and spatial attention to improve classification performance :contentReference[oaicite:1]{index=1}.

---

## 🚀 Technologies Used

### Programming Language
- Python

### Development Platform
- Google Colab

### Libraries Used
- PyTorch
- Torchvision
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn
- Seaborn
- icrawler

### Version Control
- GitHub

---

## 📊 Dataset

The dataset consists of real-world outdoor images of cows and buffaloes collected from web sources and farm environments.

### Dataset Characteristics

- Binary classification dataset
- Two classes: Cow and Buffalo
- Outdoor farm images
- Images with natural lighting variations
- Background noise, shadows, occlusion, and real-world complexity

The dataset was cleaned by removing:

- low-resolution images
- corrupted files
- indoor zoo images
- studio-quality artificial images
- images containing human privacy-sensitive information :contentReference[oaicite:2]{index=2}

---

## ⚙ Project Workflow

Start  
↓  
Dataset Collection  
↓  
Data Cleaning & Preprocessing  
↓  
Image Resizing & Normalization  
↓  
Train-Test Split  
↓  
Model Training (5 Architectures)  
↓  
Validation & Evaluation  
↓  
Grad-CAM Visualization  
↓  
Final Prediction  
↓  
End

---

## 📈 Performance Evaluation

The project evaluates models using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- Validation Loss
- Inference Time
- Grad-CAM Heatmaps

These metrics help compare all five models fairly under the same testing conditions :contentReference[oaicite:3]{index=3}.

---

## 📁 Repository Structure

Image-Based-classification-of-animals-Cattle-vs-Buffalo/

├── capstone.ipynb  
├── README.md  
├── requirements.txt  
├── Project_Report.pdf  
├── sample_outputs/  
│   ├── accuracy_graph.png  
│   ├── confusion_matrix.png  
│   ├── prediction_result.png  
│   └── gradcam_result.png  
│  
└── dataset_info.txt

---

## 📌 Future Scope

This project can be further improved by:

- Real-time cattle detection using live camera input
- Mobile application for farmers
- Raspberry Pi deployment for smart farms
- Integration with IoT livestock monitoring systems
- Multi-class breed classification
- Vision Transformer implementation
- EfficientNet-based optimization

---

## 🎓 Academic Relevance

This project demonstrates practical implementation of:

- Deep Learning
- CNN
- Transfer Learning
- Computer Vision
- Attention Mechanisms
- Explainable AI (Grad-CAM)
- Smart Agriculture Applications

It is highly relevant for:

- Final Year Major Project
- Placement Portfolio
- Resume Projects
- GitHub Showcase
- Technical Interviews

---

## 👨‍💻 Developed By

Ayush Ranjan  
B.Tech – Computer Science Engineering  
Lovely Professional University  
Final Year Capstone Project

---

## 🙏 Acknowledgement

I would like to express sincere gratitude to my project guide, Anchal Kaundal, for her valuable mentorship, continuous support, and expert guidance throughout this project. Her technical insights and constructive feedback played a major role in the successful completion of this work :contentReference[oaicite:4]{index=4}.

---

## ⭐ Conclusion

This project successfully demonstrates how Deep Learning, Transfer Learning, and Attention-Based Neural Networks can solve real-world agricultural problems.

The system provides an efficient and accurate method for Cow vs Buffalo classification, reducing dependency on manual observation and improving livestock management processes.

This project reflects the growing importance of AI-driven solutions in modern agriculture and precision farming.
