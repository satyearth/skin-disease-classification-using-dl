# Skin Disease Classification Using EfficientNet-B0

A deep learning image classification project that uses transfer learning with a pretrained **EfficientNet-B0** model to classify skin disease images into 23 different categories.

## 🔗 Project Notebook

**Kaggle Notebook:** [Skin Disease Classification Using Deep Learning](https://www.kaggle.com/code/satyearth/skin-disease-classification-using-dl)

The complete implementation, training process, and evaluation are available in the Kaggle Notebook.

## 📌 Overview

Skin disease image classification is an important research area in computer vision and medical image analysis.

This project uses a pretrained EfficientNet-B0 architecture with transfer learning and fine-tuning to classify skin images into 23 different categories.

The model is developed using PyTorch and incorporates image augmentation and class-imbalance handling techniques to improve classification performance.

## ✨ Project Highlights

- Uses a pretrained EfficientNet-B0 model.
- Applies transfer learning and fine-tuning.
- Supports classification across 23 categories.
- Uses image augmentation during training.
- Handles class imbalance using class weighting and WeightedRandomSampler.
- Evaluates performance using accuracy, precision, recall, and F1-score.

## 📂 Dataset

| Dataset | Number of Images |
|---|---:|
| Training dataset | 15,557 |
| Test dataset | 4,002 |
| Training subset | 13,223 |
| Validation subset | 2,334 |
| Total classes | 23 |

The original training dataset was divided into training and validation subsets.

## 🧠 Model Architecture

### EfficientNet-B0

EfficientNet-B0 is a convolutional neural network designed to achieve a balance between model size and computational efficiency.

This project uses ImageNet-pretrained weights and applies transfer learning to adapt the model for skin disease image classification.

## ⚙️ Techniques Used

- Transfer Learning
- Fine-Tuning
- Image Augmentation
- Class Weighting
- WeightedRandomSampler
- Multi-class Image Classification

## 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Scikit-learn
- Pillow (PIL)
- Kaggle Notebooks

## 📊 Model Performance

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

The results indicate that the model is an experimental classifier with opportunities for further improvement.

## 🔄 Project Workflow

1. Load and explore the skin disease image dataset.
2. Preprocess images and apply data augmentation.
3. Split the training data into training and validation subsets.
4. Load pretrained EfficientNet-B0 weights.
5. Apply transfer learning and fine-tuning.
6. Handle class imbalance using class weighting and WeightedRandomSampler.
7. Evaluate the model using classification metrics.

## 🚀 How to Run

This project is implemented using Kaggle Notebooks, so no local installation is required.

1. Open the [Kaggle Project Notebook](https://www.kaggle.com/code/satyearth/skin-disease-classification-using-dl).
2. Sign in to your Kaggle account.
3. Click **Copy & Edit** to create your own editable version.
4. Ensure the required dataset is attached to the notebook.
5. Run the notebook cells sequentially.
6. Train and evaluate the EfficientNet-B0 model.

## 🔮 Future Improvements

- Improve classification performance through better data preprocessing.
- Experiment with advanced deep learning architectures.
- Tune hyperparameters and augmentation strategies.
- Improve class-wise performance on underrepresented categories.
- Explore model explainability techniques such as Grad-CAM.

## ⚠️ Disclaimer

This project is intended strictly for educational and research purposes. It is an experimental image classifier and **not a medical diagnostic tool**. Its predictions must not be used for medical decisions.

## 👨‍💻 Author

**Satya**

[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-blue?logo=kaggle)](https://www.kaggle.com/code/satyearth/skin-disease-classification-using-dl)
