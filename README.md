# MNIST Digit Classifier with Gradio

A simple CNN-based handwritten digit classifier trained on the MNIST dataset using PyTorch,
with an interactive web interface powered by Gradio.

## Features

- CNN model trained on MNIST 
- Interactive Gradio web interface for real-time digit prediction
- Draw digits directly in your browser

## How to Run

### 1. Install dependencies
```bash
pip install -r requirements.txt
```

### 2. Train the model
```bash
python train.py
```

### 3. Launch the interactive interface
```bash
python app.py
```

## Model Architecture

- 2x Convolutional layers with ReLU + MaxPooling
- 2x Fully connected layers
- Optimizer: Adam
- Loss: CrossEntropyLoss

## Results

| Epoch | Loss   | Accuracy |
|-------|--------|----------|
| 1     | 0.1363 | 98.35%   |
| 2     | 0.0416 | 98.85%   |
| 3     | 0.0282 | 98.56%   |
