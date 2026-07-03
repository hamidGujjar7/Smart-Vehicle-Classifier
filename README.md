# Smart-Vehicle-Classifier
VehicleNet is a deep learning–based image classification system designed to recognize and classify road vehicles into four categories: Car, Motorcycle, Truck, and Van. The project uses the EfficientNet-B3 architecture with transfer learning to achieve high classification accuracy while maintaining computational efficiency.

The dataset consists of balanced vehicle images, with approximately 200 images per class, collected from multiple sources and preprocessed to remove corrupted, duplicate, and low-quality images. Data augmentation techniques such as horizontal flipping, random rotation, zooming, and contrast adjustment are applied during training to improve the model's ability to generalize and reduce overfitting.

The EfficientNet-B3 backbone, pretrained on ImageNet, is used as a feature extractor. A custom classification head with Global Average Pooling, Batch Normalization, Dropout, and Dense layers is added for four-class prediction. The model is trained using the AdamW optimizer, Cross-Entropy Loss with label smoothing, learning rate scheduling, and early stopping to improve convergence and prevent overfitting.

This project demonstrates the complete deep learning workflow, including dataset preparation, preprocessing, data augmentation, transfer learning, model training, evaluation, and performance analysis. It also serves as a practical comparison of modern convolutional neural network architectures for vehicle image classification.

Features
Multi-class vehicle classification
Four vehicle categories (Car, Motorcycle, Truck, Van)
EfficientNet-B3 transfer learning
Image preprocessing and dataset cleaning
Real-time data augmentation
Overfitting reduction using Dropout and Label Smoothing
AdamW optimizer with learning rate scheduling
High validation accuracy
TensorFlow/Keras implementation
GPU training support (Google Colab)
Technologies Used
Python
TensorFlow / Keras
EfficientNet-B3
NumPy
Matplotlib
OpenCV
Google Colab
CUDA GPU (Colab)
