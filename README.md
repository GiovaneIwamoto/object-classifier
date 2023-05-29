# OBJECT CLASSIFIER

### INTRODUCTION

Project Overview:

This project focuses on the implementation of an object classifier with various functionalities. The project can be divided into several parts to ensure the successful development and evaluation of the classifier.

Part 1 - Dataset Construction:
The initial step involves constructing a dataset consisting of at least five different objects. Each object should have a minimum of 100 images captured using a mobile phone. These images will serve as the foundation for training and evaluating the object classifier. The dataset will be shared through a Google Drive link, allowing easy access for all project stakeholders. It is essential to ensure correct access sharing to avoid any point deductions.

Part 2.0 - Data Split:
Once the dataset is constructed, it needs to be divided into three separate sets: training, validation, and test sets. While the minimum requirements for the number of classes and examples are specified, there is flexibility to adjust the quantity for individual objects if they present labeling difficulties. This adjustment aims to enhance the overall performance of the classifier.

Part 2.1 - Custom Architecture Training:
In this phase, a custom architecture is designed, featuring a minimum of eight convolutional layers. The training process begins by utilizing the CIFAR100 dataset, a well-known benchmark in computer vision tasks. Once the custom architecture is trained using CIFAR100, it is fine-tuned using the dataset constructed in Part 1. The provided video link offers valuable guidance throughout this process, aiding in the successful implementation of the classifier.

Part 2.2 - Fine-tuning with Pre-trained Models:
This stage involves leveraging the power of pre-trained models available in the PyTorch model repository. Specifically, architectures with less than 10 million parameters are recommended to ensure faster training without compromising performance. The project requires fine-tuning three selected pre-trained architectures. During evaluation, several metrics need to be measured to assess the classifier's performance:

Displaying the training and validation loss curves provides insight into the model's learning progress and helps identify possible overfitting or underfitting issues.
The confusion matrix visually represents the classifier's performance in terms of correctly and incorrectly classified instances across different object classes.
Precision, recall, and F1 scores are crucial evaluation metrics. Measuring these scores, both on a micro and macro level, provides a comprehensive understanding of the classifier's performance across different object classes. The classification_report function from the sklearn library can assist in obtaining these metrics.
By following these outlined steps and evaluating the classifier based on the specified requirements, this project aims to develop a robust and accurate object classifier capable of classifying objects based on the provided dataset.

#### **AUTHOR**

- Giovane Hashinokuti Iwamoto - Computer Science student at UFMS - Brazil - MS

I am always open to receiving constructive criticism and suggestions for improvement in our developed code. I believe that feedback is an essential part of the learning and growth process, and I am eager to learn from others and make my code the best it can be. Whether it's a minor tweak or a major overhaul, I am willing to consider all suggestions and implement the changes that will benefit my code and its users.
