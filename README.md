# OBJECT CLASSIFIER

### OVERVIEW

This project focuses on the implementation of an object classifier with various functionalities. The project can be divided into several parts to ensure the successful development and evaluation of the classifier.

### FEATURES

**Part 1.0 - Dataset Construction:**

The initial step involves constructing a dataset consisting of at least five different objects. Each object should have a minimum of 100 images. These images will serve as the foundation for training and evaluating the object classifier. The dataset should be shared through a Google Drive link with the aim of connecting easily with Google Colab.

**Part 2.0 - Data Split:**

Once the dataset is constructed, it needs to be divided into three separate sets: `training`, `validation`, and `test` sets. While the minimum requirements for the number of classes and examples are specified, there is flexibility to adjust the quantity for individual objects if they present labeling difficulties. This adjustment aims to enhance the overall performance of the classifier.

**Part 2.1 - Custom Architecture Training:**

Created a custom architecture design, featuring an eight convolutional layers. The training process begins by utilizing the CIFAR100 dataset, a well-known benchmark in computer vision tasks. Once the custom architecture is trained using CIFAR100, it is fine-tuned using the dataset constructed in Part 1.0.

**Part 2.2 - Fine-tuning with Pre-trained Models:**

This stage involves leveraging the power of pre-trained models available in the PyTorch model repository. Specifically, architectures with less than 10 million parameters were used to ensure faster training without compromising performance (MOBILENET_V3_SMALL, SHUFFLENET_V2_X0_5, SQUEEZENET1_0).

Displaying the training and validation loss curves provides insight into the model's learning progress and helps identify possible overfitting or underfitting issues.
The confusion matrix visually represents the classifier's performance in terms of correctly and incorrectly classified instances across different object classes.
Precision, recall, and F1 scores are crucial evaluation metrics. Measuring these scores, both on a micro and macro level, provides a comprehensive understanding of the classifier's performance across different object classes.

By following these outlined steps and evaluating the classifier based on the specified requirements, this project aims to develop a robust and accurate object classifier capable of classifying objects based on the provided dataset.

### **CONCLUSION**

The classifier.ipynb file contained in this repository has been trained and fine-tuned based on five classes. The number of epochs for the learning described in the code is relatively low, resulting in insufficient data accuracy. It is recommended to dedicate more processing power and time to achieve a more efficient object classifier. This way, both the loss functions and the confusion matrix will be more indicative of the training process.

Regarding the dataset, the training, validation, and test sets were assigned a ratio of 70-15-15 images, respectively. Increasing the quantity and variety of data certainly contributes to obtaining a better classifier for both the fine-tuned custom cifar100 model and pre-trainned pytorch architectures.

#### **AUTHOR**

- Giovane Hashinokuti Iwamoto - Computer Science student at UFMS - Brazil - MS

I am always open to receiving constructive criticism and suggestions for improvement in our developed code. I believe that feedback is an essential part of the learning and growth process, and I am eager to learn from others and make my code the best it can be. Whether it's a minor tweak or a major overhaul, I am willing to consider all suggestions and implement the changes that will benefit my code and its users.
