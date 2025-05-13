# Traffic-Sign-Classification

This project implements a Traffic Sign Classification model using a Convolutional Neural Network (CNN) architecture. The model is trained on the “valentynsichkar/traffic-signs-preprocessed” dataset, which consists of traffic sign images of size 32x32 pixels with three RGB channels. The project is developed using Python, leveraging TensorFlow and Keras for deep learning.

Key Techniques and Workflow:
	•	Data Loading and Preprocessing:
	    -> The preprocessed dataset is loaded in the form of pickle files.
	    -> The images are reshaped to a consistent format of (32, 32, 3) using NumPy.
	    -> The labels are one-hot encoded using TensorFlow’s to_categorical() method.
	•	CNN Architecture:
	    -> Built using TensorFlow’s Keras API.
	    -> Includes a combination of Convolutional (Conv2D), Pooling (MaxPooling2D), Dropout, and Dense layers.
	    -> Regularization techniques like Dropout and Batch Normalization are used for better generalization.
	• Training and Evaluation:
	    -> The model is trained using the Adam optimizer with a learning rate scheduler for efficient training.
	    -> Evaluation metrics include accuracy, with performance measured on the test set.
	•	Performance Optimization:
	    -> Adaptive learning rate scheduling to ensure stable convergence.

This project demonstrates the effective use of CNNs for multi-class image classification in a traffic sign recognition context.
