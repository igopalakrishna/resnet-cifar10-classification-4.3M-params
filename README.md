# ResNet-18 CIFAR-10 Image Classification (5M Params)

A deep learning project implementing **ResNet-18** for **CIFAR-10 image classification** using **PyTorch**.  
The model is trained **from scratch**, keeping the number of parameters **under 5 million**, and achieves **94%+ validation accuracy**.  
This repository includes **data preprocessing, training, evaluation, inference, and visualizations**.

---

## **Project Overview**
This project builds and trains a **ResNet-18 model** on **CIFAR-10**, with the following features:
- **Custom ResNet-18 architecture** with **skip connections**.
- **Data Augmentation** (Rotation, Cropping, Flipping, Color Jitter).
- **Training & Evaluation** with accuracy/loss visualization.
- **Optimized Training** using **SGD, Learning Rate Scheduling**.
- **Inference Pipeline** for generating predictions on test images.
- **Model Checkpointing** for reuse and deployment.
- **Visualization of Training Graphs**.

## 📌 **Repository Structure**
```plaintext
📦 resnet-cifar10-classification-5M-params
│── 📄 .gitattributes         # Git LFS settings
│── 📄 README.md              # Project documentation
│── 📄 readme.html            # Additional documentation (HTML format)
│── CIFAR-10 Dataset Files (Stored in the root directory)
│   ├── batches.meta
│   ├── cifar_test_nolabel.pkl
│   ├── test_batch
│   ├── data_batch_1
│   ├── data_batch_2
│   ├── data_batch_3
│   ├── data_batch_4
│   ├── data_batch_5
