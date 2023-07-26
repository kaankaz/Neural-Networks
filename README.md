# Deep-Learning


"Intelligent Waste Classifier: Advanced CNN Architectures for Next-Generation Recycling with Deep Learning and Custom Datasets"

This project aims to revolutionize recycling processes through an intelligent waste classifier, utilizing advanced Convolutional Neural Networks (CNNs) and custom datasets to achieve 84% cross-validation accuracy in recyclable waste classification (plastic, glass, paper, metal)

- Assembled a balanced custom dataset of 120 images (30 per class) for multi-class image classification of recyclable waste (plastic, glass, paper, metal)
- Established a baseline Convolutional Neural Network (CNN) model using TensorFlow Keras, incorporating data augmentation, L2 regularization, dropouts, and additional layers to enhance performance, achieving 64% cross-validation accuracy
- Integrated residual connections into the upgraded CNN model, further improving cross-validation accuracy to 79%
- Leveraged the pre-trained VGG16 model for transfer learning, fine-tuning, and customizing the top layer to achieve 84% cross-validation accuracy for the specific classification task
- Employed TensorFlow Keras API with ImageDataGenerator for efficient and flexible training, validation, and testing data handling and augmentation
