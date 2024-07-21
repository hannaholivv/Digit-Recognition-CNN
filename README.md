# Handwritten Digit Recognition using CNN with PyTorch

A robust Convolutional Neural Network (CNN) implemented in PyTorch for recognizing handwritten digits with high accuracy.

## 🚀 Highlights

- **93% Overall Accuracy** on test dataset
- Handles 32x32 pixel, 3-channel images
- 10-category classification (digits 0-9)
- Efficient training (~41 minutes on standard hardware)

## 🧠 Model Architecture

The CNN architecture includes:

- 3 Convolutional blocks (each with 2 Conv2D layers, ReLU, BatchNorm, and MaxPool)
- Flatten layer
- 2 Fully connected layers with dropout for regularization

## 📊 Performance

| Metric | Value |
|--------|-------|
| Test Accuracy | 93% |
| Best Training Accuracy | 94.94% |
| Best Validation Accuracy | 92.67% |
| Training Time | ~2454 seconds (40.9 minutes) |

### Individual Digit Accuracies

| Digit | Accuracy |
|-------|----------|
| 0 | 94% |
| 1 | 90% |
| 2 | 95% |
| 3 | 91% |
| 4 | 96% |
| 5 | 93% |
| 6 | 93% |
| 7 | 96% |
| 8 | 93% |
| 9 | 95% |

## 🛠️ Implementation Details

- **Framework**: PyTorch
- **Optimizer**: Adam
- **Learning Rate**: Initial 1e-3 with ReduceLROnPlateau scheduler
- **Loss Function**: CrossEntropyLoss
- **Training**: 20 epochs, batch size of 256

## 📂 Project Structure

digit-recognition-cnn/
- DigitalDigitRecognition.ipynb # Main script for training and evaluation
- data # Dataset directory 
- README.md # Project documentation
