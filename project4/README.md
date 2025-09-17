# Handwritten Character Recognition with CNN (EMNIST)

This project demonstrates the implementation of a **Convolutional Neural
Network (CNN)** for handwritten character recognition using the **EMNIST
(Balanced) dataset**.\
The goal is to build a baseline CNN, track experiments with **Weights &
Biases (wandb)**, and improve performance through **hyperparameter
tuning**.

------------------------------------------------------------------------

## 🔹 Project Overview

-   Load and preprocess EMNIST dataset (train, validation, test)\
-   Build a baseline CNN model (convolution, pooling, fully connected
    layers)\
-   Train the model and evaluate accuracy\
-   Integrate **wandb** for experiment tracking (loss/accuracy curves)\
-   Perform **hyperparameter tuning** with wandb sweeps (learning rate,
    optimizer, batch size, dropout, etc.)\
-   Visualize model performance (accuracy, loss curves, confusion
    matrix)

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   Python\
-   PyTorch\
-   torchvision\
-   Matplotlib\
-   scikit-learn\
-   wandb (Weights & Biases)

------------------------------------------------------------------------

## 📂 Project Structure

    main.py              # Training script with wandb integration
    models.py            # CNN model definition
    utils.py             # Helper functions (plotting, evaluation)
    README.md            # Project documentation
    data/                # EMNIST dataset (downloaded automatically)

------------------------------------------------------------------------

## 📊 Results

🔹 **Baseline CNN**\
- Achieved moderate accuracy (\~XX%) on test set\
- Provided starting point for tuning

🔹 **After Hyperparameter Tuning**\
- Accuracy improved to \~YY%\
- Validation curves showed better generalization\
- Confusion Matrix highlighted classes with most confusion

------------------------------------------------------------------------

## 🎯 Learning Objectives

-   Understand how to preprocess and train CNNs on handwritten character
    datasets\
-   Learn to integrate **wandb** for experiment tracking and
    visualization\
-   Explore the impact of hyperparameters (learning rate, optimizer,
    dropout, filters) on CNN performance\
-   Practice evaluating classification models with accuracy, loss
    curves, and confusion matrices
