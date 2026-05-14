# Facial Emotion Recognition using CNN

## 📖 Introduction

This project focuses on building a Deep Learning model for Facial Emotion Recognition using the FER-2013 dataset. The model is developed using Convolutional Neural Networks (CNNs) to classify human facial expressions into seven different emotions. The system analyzes grayscale facial images and predicts the corresponding emotion with high accuracy.

---

## 🎯 Objective

The main objective of this project is to develop an emotion detection system capable of identifying facial expressions such as:

* Angry
* Disgust
* Fear
* Happy
* Neutral
* Sad
* Surprise

---

## 💾 Dataset

The project uses the FER-2013 dataset, which contains:

* 48×48 pixel grayscale facial images
* 24,400 total images
* 22,968 training images
* 1,432 testing images

The faces are centered and aligned to maintain consistency across the dataset.

---

## 🛠 Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Google Colab

---

## ⚙️ Preprocessing

To improve model performance and prevent overfitting, the following preprocessing techniques were applied:

* Image rescaling
* Width and height shifting
* Horizontal flipping
* Data augmentation
* Batch generation using `ImageDataGenerator`

---

## 🧠 CNN Model Architecture

The CNN model includes:

* Multiple Conv2D layers
* MaxPooling layers
* Batch Normalization
* Dropout layers
* Fully Connected Dense layers
* Softmax output layer for emotion classification

The model was trained using the Adam optimizer and categorical cross-entropy loss function.

---

## 📊 Model Evaluation

The model performance was evaluated using:

* Training Accuracy
* Validation Accuracy
* Loss Curves
* Emotion Prediction on Test Images

The trained model successfully predicts facial emotions from unseen images.

---

## 🚀 Features

* Real-time facial emotion classification
* Deep learning-based image recognition
* Data augmentation for improved generalization
* Visualization of training and validation performance

---

## 📌 Future Improvements

* Improve accuracy using transfer learning
* Add real-time webcam emotion detection
* Deploy as a web application
* Optimize model performance for mobile devices

---

## 📷 Output

The model predicts emotions such as Happy, Sad, Angry, Surprise, etc., from facial images and displays the detected emotion.

---

## 📚 Conclusion

This project demonstrates the effectiveness of CNNs in image classification and facial emotion recognition tasks. By combining preprocessing, augmentation, and deep learning techniques, the model achieves reliable emotion detection performance and can be extended for real-time AI applications.
