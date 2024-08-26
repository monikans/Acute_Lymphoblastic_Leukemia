# 🩸 Detection and Classification of Acute Lymphoblastic Leukemia (ALL)

This repository presents a comprehensive deep learning approach to detecting and classifying Acute Lymphoblastic Leukemia (ALL) from blood smear images. By leveraging advanced Convolutional Neural Network (CNN) architectures, this project aims to support early diagnosis and treatment decisions with high accuracy.

## 🌟 Table of Contents

- Introduction
- Dataset
- Model Architecture
- Results
- Contributing
- Acknowledgments

## 🧬 Introduction

Acute Lymphoblastic Leukemia (ALL) is a fast-progressing cancer that predominantly affects white blood cells. Early and precise detection is vital for effective treatment. This project automates the classification of blood smear images into normal or ALL-positive categories using state-of-the-art CNN models, offering a robust tool for the medical community.

## 📊 Dataset

The dataset utilized in this project comprises meticulously labeled blood smear images, divided into normal and ALL-positive categories. Extensive pre-processing techniques were applied to enhance image quality and improve the model’s performance.

## 🏗️ Model Architecture

The project employs the following deep learning models to ensure a robust classification process:

- **ResNet-50**: A deep residual network renowned for its accuracy and capability to handle complex patterns.
- **EfficientNet-B3**: An optimized model balancing efficiency and performance, known for its scalable architecture.
- **AlexNet**: A pioneering architecture in the field of CNNs, known for its simplicity and effectiveness.
- **VGG16**: A classic model famous for its straightforward and deep architecture, delivering reliable results.

Each model was fine-tuned and trained using TensorFlow and Keras, with techniques like data augmentation and dropout to prevent overfitting and ensure generalization.

## 📈 Results

The models demonstrated exceptional performance on the test dataset, with key metrics as follows:
- **Accuracy**: 98%
- **Precision**: 97%
- **Recall**: 98%
- **F1-Score**: 97.5%

### Example Predictions

![Sample Predictions]

The model’s predictions exhibit high confidence and accuracy.

## 🤝 Contributing

We welcome and encourage contributions! Whether it’s improving model performance, enhancing documentation, or adding new features, feel free to fork the repository, make your changes, and submit a pull request. Your efforts are highly valued.

## 🙏 Acknowledgments

This project is part of a broader research initiative exploring the application of deep learning in medical diagnostics. We extend our gratitude to the contributors of the dataset and the developers of the open-source tools and libraries that made this work possible.
