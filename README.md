# Classifying-Industrial-Equipments-Images-

## Overview
This project implements a Convolutional Neural Network (CNN) model to automatically classify industrial equipment images as defective or non-defective. Built using TensorFlow and Keras, this solution provides a robust framework for quality control in manufacturing environments.

## Features
- Real-time image data augmentation
- Custom CNN architecture optimized for defect detection
- Comprehensive model evaluation and visualization
- Production-ready model export
- Batch processing capabilities

## Requirements
- Python 3.7+
- TensorFlow 2.0+
- NumPy
- Matplotlib
- scikit-learn

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/industrial-defect-classification.git

# Navigate to the project directory
cd industrial-defect-classification

# Install required packages
pip install -r requirements.txt
```

## Usage

### Data Preparation
Place your dataset in the following structure:
```
data/
├── defective/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
└── non-defective/
    ├── image1.jpg
    ├── image2.jpg
    └── ...
```

### Training
```python
# Update the data directory path in the code
data_dir = 'path/to/your/dataset'

# Run the training script
python src/train.py
```

### Model Architecture
The CNN model consists of:
- 3 Convolutional layers with ReLU activation
- MaxPooling layers for dimensional reduction
- Dense layers for classification
- Binary output with sigmoid activation


## Model Performance
The model is evaluated using:
- Training and validation accuracy
- Loss curves
- Classification report with precision, recall, and F1-score
- Real-time performance metrics during training

## Visualization
The project includes visualization tools for:
- Training history
- Model performance metrics
- Confusion matrix
- Sample predictions

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
