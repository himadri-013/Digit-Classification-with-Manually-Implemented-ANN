# **🔹Handwritten Digit Classification using a Manually Implemented ANN**

This project implements a simple **Multi Layer Perceptron(MLP) from scratch** using Python to classify **handwritten digits**. The neural network is trained on preprocessed image data and includes a **single hidden layer**. The objective is to demonstrate how an ANN works internally—without relying on libraries like TensorFlow or PyTorch.

## 🧠 Features

- Fully manual implementation (no high-level ML frameworks)
- One hidden layer with size = 128
- Forward propagation
- Backpropagation with gradient descent
- Evaluation on test data
- Preprocessing of handwritten image data and classification of them

---
## 🗃️ Dataset

The model is trained on :

- **MNIST** dataset of hand written digits


## 🔹Preprocessing for training & testing includes:

- Resizing (e.g., 28x28)
- Normalization : pixel values scaled to (0, 1)
- Flattening 2D images to 1D input vectors

## 🔹Preprocessing for real-life prediction includes:

- Grayscale conversion
- Resizing (e.g., 28x28)
- Normalization : pixel values scaled to (0, 1)
- Flattening 2D images to 1D input vectors

## 📁 Project Structure
<br>├── sample_images_for_predictions/
<br>   &nbsp;&nbsp;&nbsp;&nbsp; └── image 1
<br>   &nbsp;&nbsp;&nbsp;&nbsp; └── image 2
<br>   &nbsp;&nbsp;&nbsp;&nbsp; └── image 3
<br>   &nbsp;&nbsp;&nbsp;&nbsp; └── image 4
<br>   &nbsp;&nbsp;&nbsp;&nbsp; └── image 5
<br>├── src/
<br>   &nbsp;&nbsp;&nbsp;&nbsp; └── module_ann.ipynb
<br>   &nbsp;&nbsp;&nbsp;&nbsp; └── data_processing.ipynb
<br>   &nbsp;&nbsp;&nbsp;&nbsp; └── Model_training_testing.ipynb
<br>   &nbsp;&nbsp;&nbsp;&nbsp; └── Predictions.ipynb
<br>├── README.md
<br>├── requirements.txt



