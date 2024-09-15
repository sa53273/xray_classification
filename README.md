# Lung X-Ray Classification Using Convolutional Neural Networks (CNNs) from Scratch
-- 
Project Description

This project aims to develop a machine learning model that classifies lung X-rays into three categories: COVID-19, pneumonia, and normal. Using Convolutional Neural Networks (CNNs), the model is designed to handle image data with dimensions of 256x256 pixels. The project explores multiple architectures and techniques to achieve optimal performance, including regularization, batch normalization, data augmentation, and bootstrapping.

The dataset used in this project consists of a relatively small number of images, making the task challenging due to the risk of overfitting. To mitigate this, various techniques such as data augmentation, L2 regularization, dropout, and batch normalization have been employed. Additionally, the project explores bootstrapping with intense data augmentation to further improve the model’s robustness and generalization capability.

Key Features

	•	Image Classification: The model classifies lung X-rays into three categories: COVID-19, pneumonia, and normal.
	•	CNN Architecture: The project explores different CNN architectures with multiple convolutional layers, max-pooling layers, and fully connected layers.
	•	Regularization: L2 regularization, dropout, and batch normalization are used to prevent overfitting.
	•	Data Augmentation: Techniques like rotation, width shift, height shift, shear, zoom, and horizontal flip are applied to increase the diversity of the training data.
	•	Bootstrapping: Multiple models are trained using bootstrapped samples to enhance performance and reduce variance.
	•	Evaluation Metrics: Accuracy, precision, recall, and F1-score are used to evaluate model performance.
	•	Overfitting Mitigation: Techniques like lowering the learning rate, early stopping, and increasing batch size are used to stabilize the model<img width="732" alt="Screenshot 2024-09-14 at 8 17 10 PM" src="https://github.com/user-attachments/assets/29a9269a-1349-412c-ba6e-8fb060e37774">
 and improve generalization.

