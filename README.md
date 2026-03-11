# MNIST Digit Classifier - MLP

Implementation of a Multilayer Perceptron (MLP) neural network using TensorFlow/Keras to classify handwritten digits from the MNIST dataset.

## Technologies

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## Dataset

MNIST dataset containing 70,000 grayscale images of handwritten digits (0–9).

Image size: 28x28 pixels.

## Model Architecture

- Input layer: 784 neurons (flattened 28x28)
- Dense layer: 256 neurons (ReLU)
- Dropout: 0.2
- Dense layer: 128 neurons (ReLU)
- Dropout: 0.2
- Output layer: 10 neurons (Softmax)

## Training

- Optimizer: Adam
- Loss: Categorical Crossentropy
- Epochs: 10
- Batch size: 128

## Result

Test accuracy: ~98%

## Run

```bash
python mlp_mnist.py
