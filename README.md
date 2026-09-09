# Food-101 Image Classification using Transfer Learning

Food image classification is a challenging task in computer vision, given the great variability of food appearance, lighting conditions, and background clutter. This project explores a robust deep learning approach for classifying images into **101 food categories** from the **Food-101 dataset**.

## 📌 Overview

Transfer learning was applied using three state-of-the-art CNN architectures:
- **EfficientNetB3**
- **ResNet101**
- **DenseNet201**

Each model was fine-tuned on the Food-101 dataset to evaluate its effectiveness in feature extraction and image classification.

## 📊 Results

| Model | Test Accuracy | Notes |
|---|---|---|
| EfficientNetB3 | — | Failed to converge in this setup |
| ResNet101 | — | Failed to converge in this setup |
| **DenseNet201** | **~69.3%** | Best performance, excellent generalization |

The results highlight how **dense connections and feature reuse** in DenseNet architectures are particularly effective for fine-grained image classification tasks like food recognition.

## 📁 Repository Structure
├── notebooks/
│ ├── Food-101_ModelTrainingNotebook.ipynb # Model training (EfficientNetB3, ResNet101, DenseNet201)
│ └── Food-101_ModelComparisonNotebook.ipynb # Model evaluation & comparison
├── report/
│ └── Report.docx / Report.pdf # Full project report
├── presentation/
│ └── Food-101_ModelReportPresentation.pptx / .pdf # Project presentation slides
├── links/ # Additional resources / references

## 📄 Documents

| File | Description |
|------|-------------|
| [Model Training Notebook](notebooks/) | Code for fine-tuning EfficientNetB3, ResNet101, and DenseNet201 on Food-101 |
| [Model Comparison Notebook](notebooks/) | Evaluation and comparison of model performance |
| [Project Report](report/) | Detailed write-up of methodology and results |
| [Presentation Slides](presentation/) | Summary slide deck of the project |

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- Pretrained CNN architectures: EfficientNetB3, ResNet101, DenseNet201
- Food-101 dataset

## 🚀 Getting Started

1. Clone the repository:
```bash
   git clone https://github.com/ninjakashaf/Food-Image-Classification-.git
```
2. Open the notebooks in the `notebooks/` folder using Jupyter or Google Colab.
3. Follow along with the training and comparison workflows.

## 👥 Authors

- Kashaf Nadeem
- Nashrah Ahmad khan
