# Fashion MNIST Classification using Deep Learning
Fashion MNIST Classification using Deep Learning :-
- A deep learning project that classifies fashion items using the Fashion MNIST dataset with the help of TensorFlow and Keras.

📌 Project Description:- 
This project focuses on building a neural network model to classify grayscale images of clothing into predefined categories. It demonstrates the application of deep learning techniques for image classification tasks and provides a simple yet effective implementation for beginners.

🎯 Objectives
To understand image classification using deep learning
To implement an Artificial Neural Network (ANN) using Keras
To preprocess and normalize image data
To evaluate model performance on unseen data

📊 Dataset Information
The Fashion MNIST dataset is a collection of 70,000 grayscale images (28×28 pixels) categorized into 10 classes:-
Label	Category:
0	T-shirt/top
1	Trouser
2	Pullover
3	Dress
4	Coat
5	Sandal
6	Shirt
7	Sneaker
8	Bag
9	Ankle boot

🧠 Model Architecture
The model is built using a Sequential Neural Network:
Flatten Layer (Input Layer)
Dense Layer (128 neurons, ReLU activation)
Dense Layer (64 neurons, ReLU activation)
Output Layer (10 neurons, Softmax activation)

⚙️ Technologies Used :
Python
TensorFlow
Keras
NumPy
Matplotlib
Jupyter Notebook

📈 Model Performance
The model is trained on 60,000 images and tested on 10,000 images
Achieves good accuracy for basic ANN architecture
Performance can be further improved using CNNs

🔍 Key Features
Data preprocessing and normalization
Label encoding
Model training with validation
Accuracy evaluation
Predictions on test data
