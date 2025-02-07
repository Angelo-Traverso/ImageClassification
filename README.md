# 🌟 **Image Classification with TensorFlow**

Welcome to the code implementation for image classification using TensorFlow! 🚀

This code demonstrates how to preprocess, train, evaluate, and improve deep learning models for classifying images. The project includes building and comparing multiple CNN architectures, identifying the best model, and addressing overfitting challenges.


## 👤 **Author Information**

- **Name**: Angelo Traverso
- **Module Code**: PDAN8412
- **Due Date**: 2024/11/18

## 🗂️ **Code Structure**

1. **Data Loading and Preprocessing**:  
   - Importing the dataset.  
   - Performing exploratory data analysis (EDA).  
   - Normalizing, augmenting, and splitting the data for training, validation, and testing.  

2. **Model Implementation**:  
   - Building baseline and improved CNN models.  
   - Configuring model layers, activation functions, and loss functions.  
   - Applying dropout and regularization to mitigate overfitting.  

3. **Training and Evaluation**:  
   - Training models on the dataset.  
   - Using metrics like accuracy, F1-score, and confusion matrices to evaluate performance.  
   - Addressing underfitting and overfitting with hyperparameter tuning.  

4. **Visualization and Insights**:  
   - Visualizing training and validation accuracy/loss curves.  
   - Generating confusion matrices and classification reports to interpret results.

4. **Pipelines**:  
   - Visualizing training and validation accuracy/loss curves.  
   - Generating confusion matrices and classification reports to interpret results.
   

---
## 📌 **Purpose of the Code**

The purpose of this code is to:  
- Demonstrate the process of building and refining CNN models for image classification.  
- Provide insights into model performance and generalization.  
- Explore strategies to address overfitting and improve accuracy.

## ❗ **Important to Note before you Begin**
Its important to ensure that all necessary libraries are installed:
- pyspark:      pip install pyspark
- seaborn:      pip install seaborn
- scikit-learn: pip install scikit-learn

- The model testing was only tested in Visual Studio Code and NOT Jupiter Notebook.
- This project was developed using Visual Studio Code.
- This project made use of Python Version 3.11.9.
- In-text referencing is applied to code that was used from an external source, the full bibliography entry is added to the accompanying document.

## 🏃‍♂️‍➡️ **Download and Run**
- Download the folder "AngeloTraverso_ST10081927_PDAN8412_POE"
- Unzip the folder
- Open Visual Studio > File > Open Folder/ Choose Folder > "AngeloTraverso_ST10081927_PDAN8412_POE"
- You can then choose to Run All or just run individual cells using the 'play' button next to each cell


### 🔗 **Dataset Information**

- **Dataset Name**: [Fashion MNIST](https://www.kaggle.com/datasets/zalando-research/fashionmnist)
- **Source**: Kaggle
- **Description**: This dataset contains pixelated grayscale images, where each image is a 28 x 28 image, each encorporating a total of 784 pixels

---

Let's get started by importing the necessary packages for this Image Classification task. Below, you'll find the detailed steps to clean and prepare the data for the Image Classification task! 🎉 🎉

