# tomato-leaf-disease-detection-transfer-learning
Deep learning-based tomato leaf disease detection using ResNet50, EfficientNet, ViT, and ensemble learning.
## Overview
This project focuses on detecting tomato leaf diseases using deep learning and transfer learning techniques. The system classifies tomato leaf images into multiple disease categories using advanced CNN and transformer-based architectures.

The project implements ResNet50, EfficientNet, and Vision Transformer (ViT) models and combines them using ensemble learning techniques to improve prediction accuracy.

The system is designed to support precision agriculture by enabling early disease detection and reducing crop loss.

## Features
- Tomato leaf disease classification using deep learning
- Transfer learning using pretrained models
- Ensemble learning for improved accuracy
- Handling class imbalance using focal loss and oversampling
- Data augmentation for better generalization
- Confusion matrix and accuracy analysis
- Scope for future IoT integration


## Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Deep Learning
- CNN
- Transfer Learning
- Ensemble Learning



## Models Used
- ResNet50
- EfficientNet
- Vision Transformer (ViT)



## Dataset
Dataset used:
Tomato Leaf Disease Dataset
## Dataset Information
The dataset contains tomato leaf images belonging to multiple disease categories and healthy leaves.

The images are organized into different folders based on disease type.

Dataset Characteristics:
- Multi-class image classification dataset
- Contains healthy and diseased tomato leaves
- Used for supervised deep learning training
- Includes visually similar disease classes
- Imbalanced class distribution handled using augmentation and oversampling

Classes include:
- Tomato Healthy
- Bacterial Spot
- Early Blight
- Late Blight
- Leaf Mold
- Septoria Leaf Spot
- Spider Mites
- Target Spot
- Mosaic Virus
- Yellow Leaf Curl Virus

Dataset Source:
https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf

## Data Preprocessing
- Image resizing
- Normalization
- Data augmentation
- Class balancing
- Oversampling techniques

## Training Techniques
- Transfer Learning
- Fine-tuning pretrained layers
- Focal Loss
- Ensemble Prediction
- Weighted Sampling



## Results
| Model | Accuracy |
|-------|-----------|
| ResNet50 | 97.2% |
| EfficientNet | 98% |
| ViT | 97% |
| Ensemble Model | 99% |



## Future Improvements
- Real-time disease detection
- Mobile application deployment
- IoT-based smart farming integration
- Cloud-based monitoring dashboard

## Author
Nishandini S

LinkedIn:
https://www.linkedin.com/in/nishandinisel/
