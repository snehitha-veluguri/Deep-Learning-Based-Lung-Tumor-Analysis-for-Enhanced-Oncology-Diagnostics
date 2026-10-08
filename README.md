# Deep Learning-Based Lung Tumor Analysis for Enhanced Oncology Diagnostics

## Project Overview

This project uses deep learning and medical image classification techniques to analyze histopathological images of lung and colon tissues. A **ResNet-50** convolutional neural network is used to classify images into different tissue and cancer categories.

The project focuses on applying image preprocessing, data augmentation, transfer learning, model training, and evaluation techniques to support automated analysis of histopathological images.

## Objective

The main objective of this project is to develop a deep learning-based image classification model capable of identifying different types of lung and colon tissue from histopathological images.

The project demonstrates how deep learning can be applied to medical image analysis and assist in the classification of cancer-related tissue images.

## Dataset

The project uses the **Lung and Colon Cancer Histopathological Images** dataset.

The dataset contains five classes:

1. Lung Benign Tissue
2. Lung Adenocarcinoma
3. Lung Squamous Cell Carcinoma
4. Colon Adenocarcinoma
5. Colon Benign Tissue

The prepared dataset contains approximately **25,000 images**, with around **5,000 images per class**.

## Technologies Used

* Python
* TensorFlow
* Keras
* ResNet-50
* OpenCV
* NumPy
* Augmentor
* Jupyter Notebook

## Methodology

The project follows these major steps:

### 1. Data Collection

Histopathological images of lung and colon tissues were collected from the Lung and Colon Cancer Histopathological Images dataset.

### 2. Data Preparation

The images were organized according to their respective classes. Image preprocessing and preparation techniques were applied before training the deep learning model.

### 3. Image Preprocessing

The images were resized and normalized to make them suitable for the deep learning model.

Data augmentation was also applied to increase the diversity of the training images and improve model generalization.

### 4. Model Development

A **ResNet-50** architecture was used for image classification.

The model uses transfer learning to extract important visual features from histopathological images and classify them into the five target categories.

### 5. Model Training

The model was trained using:

* **Input image size:** 224 × 224
* **Optimizer:** Adam
* **Loss function:** Categorical Cross-Entropy
* **Activation:** Softmax
* **Architecture:** ResNet-50

### 6. Model Evaluation

The trained model was evaluated using classification performance metrics to determine its ability to correctly identify the different tissue classes.

## Model Performance

The ResNet-50 model achieved approximately **92.4% classification accuracy** in the project.

For comparison, other deep learning architectures evaluated in the project included:

| Model     | Accuracy |
| --------- | -------: |
| ResNet-50 |    92.4% |
| VGG-16    |      87% |
| U-Net     |      85% |

**ResNet-50 provided the best classification performance among the evaluated models.**

## Project Workflow

```text
Histopathological Images
          ↓
    Data Preparation
          ↓
 Image Preprocessing
          ↓
   Data Augmentation
          ↓
    ResNet-50 Model
          ↓
      Model Training
          ↓
     Model Evaluation
          ↓
   Tissue Classification
```

## Project Structure

```text
Deep-Learning-Based-Lung-Tumor-Analysis-for-Enhanced-Oncology-Diagnostics/
│
└── lung_colon_using_ResNetai.ipynb
```

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/snehitha-veluguri/Deep-Learning-Based-Lung-Tumor-Analysis-for-Enhanced-Oncology-Diagnostics.git
```

### 2. Navigate to the project directory

```bash
cd Deep-Learning-Based-Lung-Tumor-Analysis-for-Enhanced-Oncology-Diagnostics
```

### 3. Install the required libraries

```bash
pip install tensorflow keras opencv-python numpy augmentor jupyter
```

### 4. Open the notebook

```bash
jupyter notebook lung_colon_using_ResNetai.ipynb
```

Run the notebook cells sequentially to reproduce the preprocessing, model training, and evaluation workflow.

## Key Learning Outcomes

Through this project, I gained practical experience in:

* Deep learning for medical image classification
* Convolutional neural networks
* Transfer learning using ResNet-50
* Image preprocessing and normalization
* Data augmentation
* TensorFlow and Keras
* Model training and evaluation
* Classification of histopathological images

## Future Enhancements

* Develop a web-based interface for image classification.
* Experiment with additional pretrained deep learning architectures.
* Improve model performance through hyperparameter tuning.
* Add detailed classification reports and confusion matrices.
* Deploy the trained model as an application for research and educational purposes.

## Disclaimer

This project is developed for **educational and research purposes**. It is not intended to replace professional medical diagnosis or clinical decision-making.
