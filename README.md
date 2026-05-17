# Part 2: Computer Vision Problem Formulation and CNN Prototype

## Overview
Build a CNN to classify product surface images into 4 defect categories: normal, scratch, dent, stain.

## Dataset
Images in images/ folder organized by class. labels.csv maps filenames to labels.

## Folder Structure
```
part-2-cnn-computer-vision/
├── README.md
├── notebook.ipynb
├── requirements.txt
├── labels.csv
├── images/
│   ├── normal/
│   ├── scratch/
│   ├── dent/
│   └── stain/
├── sample_predictions/
│   └── prediction_outputs.png
└── results/
    ├── accuracy_loss_curves.png
    └── confusion_matrix.png
```

## CNN Concepts
- **Convolution:** Filter slides over image detecting edges/textures
- **Pooling:** Reduces spatial size, retains key features
- **ReLU:** Non-linear activation, avoids vanishing gradients
- **CNNs vs FF-NN:** CNNs preserve 2D structure and share weights — much better for images

## Business Use Case
Manufacturing quality inspection — automatically flag defective products on a production line.

## How to Run
```
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```
