# Garbage Classification using Deep Learning

## Project Description
This project aims to classify garbage into categories using deep learning techniques. The dataset used consists of images of garbage grouped into 5 categories: `cardboard`, `glass`, `metal`, `paper`, and `plastic`. Models are built using pre-trained architectures such as MobileNet or DenseNet121 to improve classification accuracy.

## Key Features
- Data Preprocessing**: Resizing, image augmentation (rotation, affine transformation, noise), and normalization.
- **Model Architecture**: Using pre-trained models (MobileNet/DenseNet121) with the addition of custom layers.
- Model Training**: Implementation of callbacks such as `EarlyStopping` and `ReduceLROnPlateau` for training optimization.
- Model Evaluation**: Analysis using confusion matrix and classification report.

