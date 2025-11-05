# 🧠 VGG16 Fine-Tuning on MNIST Project

This project demonstrates **transfer learning** by fine-tuning a **pre-trained VGG16 model** on the **MNIST handwritten digits dataset**.  
The dataset is preprocessed to fit the VGG16 input size and used to train, validate, and test the model under various hyperparameter configurations.  
The objective is to maximize the **F1-score** on the validation set while exploring the effect of parameters such as learning rate, batch size, and optimizer type.

---

## 🔹 Project Overview
- Load and preprocess the MNIST dataset (resized to 224×224 and converted to 3 channels)
- Split the dataset into **70% training**, **20% validation**, and **10% testing**
- Fine-tune the **VGG16** architecture by adding a new fully connected classification layer
- Train the model with various hyperparameter settings
- Evaluate model performance using **F1-score** and visualize results

---

## 🛠️ Technologies Used
- Python  
- PyTorch  
- Torchvision  
- NumPy  
- Scikit-learn  

---

## 📂 Project Structure
melika_rezaye_final_project.ipynb # Jupyter Notebook with full implementation
data/ # Automatically downloaded MNIST dataset

---

## 📊 Results
### 🔹 Model Architecture
- Base model: Pre-trained **VGG16** (ImageNet weights)
- Modified final layers for 10-class MNIST classification

### 🔹 Performance Highlights
- Achieved high validation **F1-scores** through fine-tuning
- Demonstrated impact of hyperparameter tuning (learning rate, batch size, optimizer)
- Visualized model predictions and convergence behavior

---

## 🎯 Learning Objectives
- Understand the concept of **transfer learning** and **fine-tuning**
- Learn how to adapt a CNN (VGG16) to a new dataset (MNIST)
- Practice evaluating model performance with **F1-score**
- Explore how different hyperparameters affect convergence and accuracy
