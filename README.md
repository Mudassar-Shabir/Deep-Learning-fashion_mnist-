# Fashion MNIST Image Classification using TensorFlow & Keras

## 📌 Project Overview

This project demonstrates how to build a Deep Learning model using **TensorFlow** and **Keras** to classify clothing images from the **Fashion-MNIST** dataset.

The goal of this project is to understand the complete Deep Learning workflow, from loading data to training, evaluating, and making predictions with an Artificial Neural Network (ANN).

---

## 📂 Dataset

**Dataset:** Fashion-MNIST

* 60,000 Training Images
* 10,000 Testing Images
* Image Size: 28 × 28 pixels
* Grayscale Images
* 10 Clothing Categories

Classes:

* T-shirt/Top
* Trouser
* Pullover
* Dress
* Coat
* Sandal
* Shirt
* Sneaker
* Bag
* Ankle Boot

---

## 🛠 Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib

---

## 📚 Project Workflow

1. Import required libraries
2. Load the Fashion-MNIST dataset
3. Explore dataset structure
4. Visualize sample images
5. Normalize pixel values
6. Build an Artificial Neural Network (ANN)
7. Compile the model
8. Train the model
9. Evaluate model performance
10. Visualize training accuracy and loss
11. Make predictions on test images

---

## 🧠 Model Architecture

Input Layer

* 28 × 28 Image

↓

Flatten Layer

↓

Dense Layer

* 128 Neurons
* ReLU Activation

↓

Output Layer

* 10 Neurons
* Softmax Activation

---

## ⚙ Model Configuration

Optimizer:

* Adam

Loss Function:

* Sparse Categorical Crossentropy

Evaluation Metric:

* Accuracy

---

## 📊 Results

Training Accuracy:

* Approximately **91%**

Validation Accuracy:

* Approximately **88%**

The model successfully learns to classify Fashion-MNIST images with good accuracy for a simple fully connected neural network.

---

## 📈 Visualizations

The project includes:

* Sample dataset visualization
* Training Accuracy Curve
* Validation Accuracy Curve
* Training Loss Curve
* Validation Loss Curve
* Prediction examples

---

## 📁 Project Structure

```
Fashion-MNIST/
│
├── Fashion_MNIST.ipynb
├── README.md
└── images/ (optional)
```

---

## 🚀 Future Improvements

* Implement Convolutional Neural Networks (CNNs)
* Compare ANN vs CNN performance
* Add confusion matrix
* Calculate precision, recall, and F1-score
* Experiment with different optimizers and architectures

---

## 🎯 Learning Outcomes

Through this project, I learned:

* Fundamentals of Deep Learning
* TensorFlow and Keras workflow
* Data preprocessing
* Neural Network architecture
* Model compilation
* Model training
* Model evaluation
* Image classification
* Performance visualization

---

## 👨‍💻 Author

**Mudassar**

This project is part of my Machine Learning and Deep Learning learning journey.
