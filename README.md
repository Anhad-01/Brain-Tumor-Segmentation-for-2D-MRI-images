# Brain Tumor Segmentation on 2D MRI Scans

This project implements a U-Net-based deep learning model for segmenting brain tumors in 2D MRI images.

## Dataset

- **Source**: [LGG MRI Segmentation Dataset](https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation)
- **Description**: The dataset contains 3,929 image-mask pairs of low-grade glioma MRI scans.

## Preprocessing

- Converted images to grayscale
- Resized images to 256×256
- Normalized pixel values

## Model Architecture

- **Base Model**: U-Net
- **Loss Function**: Binary Cross-Entropy Loss (BCE)
- **Activation Function**: Sigmoid
- **Optimizer**: Stochastic Gradient Descent (SGD)
- **Learning Rate**: 0.01
- **Batch Size**: 16
- **Epochs**: 20

## Evaluation Metrics

- **Accuracy**: 0.9974
- **Dice Score**: 0.8759
- **Precision**: 0.8799
- **Recall**: 0.8677
- **F1-Score**: 0.8720
