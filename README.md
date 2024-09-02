# 🧠 CNN Architectures: LeNet Implementation

Welcome to the **CNN Architectures** repository! 🎉 This project demonstrates how to implement and train a classic Convolutional Neural Network (CNN) architecture known as **LeNet** using TensorFlow and Keras. 

## 📑 Table of Contents

- [Introduction](#introduction)
- [LeNet Model Architecture](#lenet-model-architecture)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## 🔍 Introduction

The LeNet architecture, developed by Yann LeCun in the late 1990s, is one of the earliest and most famous convolutional neural networks. It was primarily designed for handwritten and machine-printed character recognition tasks. In this repository, we provide a simple implementation of the LeNet architecture using TensorFlow/Keras.

## 🏛️ LeNet Model Architecture

LeNet consists of the following layers:

1. **Input Layer**: Accepts a grayscale image of size 32x32.
2. **Convolutional Layer 1**: 32 filters of size 5x5 with 'tanh' activation.
3. **Pooling Layer 1**: Max Pooling of size 2x2.
4. **Convolutional Layer 2**: 64 filters of size 5x5 with 'tanh' activation.
5. **Pooling Layer 2**: Max Pooling of size 2x2.
6. **Flatten Layer**: Converts the 2D matrix to a vector.
7. **Dense Layer**: Fully connected layer with 128 neurons and 'tanh' activation.
8. **Output Layer**: A single neuron with 'sigmoid' activation for binary classification.

The model is suitable for tasks like digit classification using the MNIST dataset, but it can also be adapted for other image classification tasks.

## 🛠️ Requirements

To run the code in this repository, you need the following Python packages:

- `TensorFlow` >= 2.0
- `numpy`
- `matplotlib`
- `Jupyter Notebook` or `Jupyter Lab` (to run `.ipynb` files)

## 📥 Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/cnn-architectures.git
   cd cnn-architectures
   ```

2. **Create a virtual environment and activate it**:

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages**:

   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage

To run the LeNet model:

1. **Open Jupyter Notebook**:

   ```bash
   jupyter notebook CNN_Architectures.ipynb
   ```

2. **Run all cells** to train the LeNet model on your dataset.

### 📊 Training and Evaluation

The notebook provides detailed steps for:
- Data preprocessing and augmentation
- Building the LeNet model
- Compiling and training the model
- Evaluating the model performance

Feel free to modify the model architecture or hyperparameters to better suit your specific dataset and task.

## 🤝 Contributing

We welcome contributions to enhance this project! If you have any suggestions or improvements, please:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## 📧 Contact

For any questions or suggestions, feel free to open an issue or contact us directly!

Happy coding! 🚀
