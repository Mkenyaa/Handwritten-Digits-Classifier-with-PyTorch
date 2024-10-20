# Handwritten Digits Classifier with PyTorch

A deep learning project that implements a neural network to classify handwritten digits using the MNIST dataset and PyTorch framework.

## Project Overview

This project demonstrates the implementation of a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset. The model is built using PyTorch and achieves high accuracy in digit classification tasks.

## Features

- Implementation of CNN architecture using PyTorch
- Training and evaluation on the MNIST dataset
- Data preprocessing and augmentation techniques
- Model performance visualization
- Easy-to-follow Jupyter notebook implementation

## Requirements

```
pytorch>=1.7.0
torchvision>=0.8.1
numpy>=1.19.2
matplotlib>=3.3.2
jupyter>=1.0.0
```

## Installation

1. Clone this repository:
```bash
git clone https://github.com/Mkenyaa/Handwritten-Digits-Classifier-with-PyTorch.git
cd Handwritten-Digits-Classifier-with-PyTorch
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter notebook:
```bash
jupyter notebook MNIST_Handwritten_Digits-STARTER.ipynb
```

2. Follow the notebook cells to:
   - Load and preprocess the MNIST dataset
   - Build and train the CNN model
   - Evaluate model performance
   - Make predictions on new images

## Model Architecture

The implemented CNN model consists of:
- Convolutional layers for feature extraction
- Pooling layers for dimensional reduction
- Fully connected layers for classification
- ReLU activation functions
- Dropout for regularization

## Dataset

The MNIST dataset contains 60,000 training images and 10,000 testing images of handwritten digits (0-9). Each image is a 28x28 pixel grayscale image.

## Results

The model achieves:
- Training accuracy: ~99%
- Validation accuracy: ~98%
- Test accuracy: ~98%

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The MNIST dataset providers
- PyTorch documentation and community
- Deep learning researchers and practitioners

## Author

[Mkenyaa](https://github.com/Mkenyaa)

## Contact

For any queries or suggestions, please open an issue in the repository.
=======
