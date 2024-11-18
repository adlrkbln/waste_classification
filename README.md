# Waste Classification Using ResNet

This repository contains a Google Colab notebook that implements a ResNet-based model for waste classification. The project utilizes transfer learning with ResNet18 to classify waste images into 30 categories. The notebook is designed for easy execution and reproducibility within the Colab environment.


## **Features**
- **End-to-End Notebook**: From data preprocessing to model training, evaluation, and deployment—all in one place.
- **Transfer Learning**: Uses ResNet18 pretrained on ImageNet for efficient training on the waste dataset.
- **Interactive Visualizations**: Includes plots of training metrics and sample predictions.


## **How to Use**

### **1. Open the Notebook in Google Colab**
Click the link below to open the notebook:
[Google Colab Notebook Link](#https://colab.google/)

### **2. Setup Environment**
The notebook automatically handles environment setup, including installing required libraries.

### **3. Dataset**
The dataset is downloaded and processed directly within the notebook. Ensure you execute the dataset download cells as instructed in the notebook.

### **4. Train the Model**
Run the training cells to fine-tune the ResNet18 model for waste classification.

### **5. Evaluate the Model**
Evaluate the model performance and visualize results with provided metrics and confusion matrices.

### **6. Make Predictions**
Test the model on custom images by uploading them directly to the notebook.

## **Results**
- **Test Accuracy**: 84%.
- **Precision, Recall, F1-Score**: Detailed metrics provided within the notebook.

## **Notebook Overview**
The notebook includes the following sections:
1. **Introduction**: Overview of the project and problem statement.
2. **Setup**: Environment setup and library installations.
3. **Data Processing**: Dataset download, preprocessing, and augmentation.
4. **Model Training**: Transfer learning using ResNet18.
5. **Evaluation**: Detailed metrics and visualizations.
