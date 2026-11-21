# Skin Disease Classification Using EfficientNet-B0

A deep learning image classification project that uses transfer learning with a pretrained EfficientNet-B0 model to classify skin disease images into 23 categories.

## Overview

Skin disease image classification is an important research area in computer vision and medical image analysis.

This project uses a pretrained EfficientNet-B0 architecture with transfer learning and fine-tuning to classify skin images into 23 different categories.

The model is developed using PyTorch and includes image augmentation and class-imbalance handling techniques.

## Project Highlights

- Uses a pretrained EfficientNet-B0 model.
- Applies transfer learning and fine-tuning.
- Supports classification across 23 categories.
- Uses image augmentation during training.
- Handles class imbalance using class weighting and WeightedRandomSampler.
- Evaluates performance using accuracy, precision, recall, and F1-score.

## Dataset

| Dataset | Number of Images |
|---|---:|
| Training dataset | 15,557 |
| Test dataset | 4,002 |
| Training subset | 13,223 |
| Validation subset | 2,334 |
| Total classes | 23 |

The training data was divided into training and validation subsets.

## Model Architecture

**EfficientNet-B0**

EfficientNet-B0 is a convolutional neural network designed to achieve a balance between model size and computational efficiency.

This project uses ImageNet-pretrained weights and applies transfer learning to adapt the model for skin disease image classification.

## Techniques Used

- Transfer Learning
- Fine-Tuning
- Image Augmentation
- Class Weighting
- WeightedRandomSampler
- Multi-class Image Classification

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Scikit-learn
- Pillow (PIL)

## Model Performance

### Validation Results

| Metric | Score |
|---|---:|
| Accuracy | 43.44% |
| Macro F1-Score | 40.08% |

### Test Results

| Metric | Score |
|---|---:|
| Accuracy | 43.70% |
| Macro Precision | 39.52% |
| Macro Recall | 41.56% |
| Macro F1-Score | 39.85% |

The results indicate that the model is an experimental classifier and has scope for further improvement.

## Project Workflow

1. Load and explore the skin disease image dataset.
2. Preprocess images and apply data augmentation.
3. Split the training data into training and validation subsets.
4. Load pretrained EfficientNet-B0 weights.
5. Apply transfer learning and fine-tuning.
6. Handle class imbalance using class weighting and WeightedRandomSampler.
7. Evaluate the model using classification metrics.

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY
```

Install the required libraries:

```bash
pip install torch torchvision numpy scikit-learn pillow
```

## How to Run

1. Open the Jupyter Notebook included in this repository.
2. Update the dataset directory paths according to your environment.
3. Install the required dependencies.
4. Run the notebook cells in sequence.
5. Train and evaluate the classification model.

## Future Improvements

- Improve classification performance through better data preprocessing.
- Experiment with advanced architectures.
- Tune hyperparameters and augmentation strategies.
- Improve class-wise performance on underrepresented categories.
- Explore model explainability techniques such as Grad-CAM.

## Disclaimer

This project is intended strictly for educational and research purposes. It is an experimental image classifier and is **not a medical diagnostic tool**. Its predictions must not be used for medical decisions.

## Author

**Satya**
