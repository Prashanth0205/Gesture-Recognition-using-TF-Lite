# Gesture Recognition using TF Lite

This project focuses on gesture recognition using accelerometer and gyroscope data. The dataset comprises gestures such as 'down_to_up' and 'forward_clockwise'. After preprocessing, including normalization and splitting into training and testing sets, a deep learning model is built using TensorFlow and Keras. The model architecture consists of dense layers with ReLU activation. Following training and evaluation, the model is converted to TensorFlow Lite, facilitating deployment on resource-constrained devices while maintaining high accuracy.

## About

This repository contains the code and data for a gesture recognition project using accelerometer and gyroscope data. Key contents include:

- [gesture60_8_.csv](link_to_gesture60_8_.csv): The original dataset containing accelerometer and gyroscope readings.
- [gesture60_8_normalized.csv](link_to_gesture60_8_normalized.csv): The dataset normalized for training machine learning models.
- [gestureTinyModel.h5](link_to_gestureTinyModel.h5): A trained TensorFlow model for gesture recognition.
- [iot_gesture_final.ipynb](link_to_iot_gesture_final.ipynb): Jupyter Notebook containing the main code for the project, including data preprocessing, model training, and evaluation.

This project aims to recognize various gestures using sensor data, offering potential applications in IoT and human-computer interaction.
