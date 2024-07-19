# Digital Digit Recognition using CNN with PyTorch

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-1.x-orange.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

A robust Convolutional Neural Network (CNN) implemented in PyTorch for recognizing handwritten digits with high accuracy.

## 🚀 Highlights

- **93% Overall Accuracy** on test dataset
- Handles 32x32 pixel, 3-channel images
- 10-category classification (digits 0-9)
- Efficient training (~56 minutes on standard hardware)

## 🧠 Model Architecture

The CNN architecture includes:

- 3 Convolutional blocks (each with 2 Conv2D layers, ReLU, BatchNorm, and MaxPool)
- Flatten layer
- 2 Fully connected layers with dropout for regularization

## 📊 Performance

| Metric | Value |
|--------|-------|
| Test Accuracy | 93% |
| Best Training Accuracy | 95.07% |
| Best Validation Accuracy | 93.07% |
| Training Time | ~3341 seconds (55.7 minutes) |

### Individual Digit Accuracies

| Digit | Accuracy |
|-------|----------|
| 0 | 96% |
| 1 | 91% |
| 2 | 95% |
| 3 | 91% |
| 4 | 96% |
| 5 | 92% |
| 6 | 94% |
| 7 | 95% |
| 8 | 93% |
| 9 | 94% |

## 🛠️ Implementation Details

- **Framework**: PyTorch
- **Optimizer**: Adam
- **Learning Rate**: Initial 1e-3 with ReduceLROnPlateau scheduler
- **Loss Function**: CrossEntropyLoss
- **Training**: 20 epochs, batch size of 256

## 🔧 Setup and Usage

1. Clone the repository:
