# CNN Built from Scratch - MNIST

This project implements a Convolutional Neural Network (CNN) from scratch using NumPy to classify handwritten digits (2 digits 0 & 1) from the MNIST dataset. No deep learning frameworks like TensorFlow or PyTorch are used, ensuring a thorough understanding of CNN fundamentals.

## Features
- Fully connected neural network with convolutional layers built from scratch
- Forward and backward propagation implemented manually
- Uses the MNIST dataset for training and testing
- Supports batch training with adjustable parameters
- Optimized with gradient descent and backpropagation

## Installation
Clone the repository:
```bash
git clone https://github.com/Angad-2002/CNN_BuiltFromScratch_MNIST.git
cd CNN_BuiltFromScratch_MNIST
```

## Usage
Run the main script to train the CNN model:
```bash
python mnist.py
```

You can modify the hyperparameters in `config.py` before training.

## Dataset
The project uses the MNIST dataset, which consists of 60,000 training and 10,000 testing images of handwritten digits (0-9). The dataset is automatically downloaded when running the training script.

## Contributions
Feel free to fork this repository, raise issues, or submit pull requests.

## License
This project is licensed under the MIT License.

