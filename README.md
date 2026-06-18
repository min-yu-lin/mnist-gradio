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
| 1     | 0.1382 | 98.40%   |
| 2     | 0.0427 | 98.32%   |
| 3     | 0.0291 | 98.62%   |
| 4     | 0.0212 | 99.00%   |
| 5     | 0.0173 | 99.00%   |
