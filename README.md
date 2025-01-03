# **UNet Neural Network for Oxford-IIIT Pet Dataset** 🐾🐕🐈

This repository contains the implementation of an enhanced UNet architecture for semantic segmentation on the Oxford-IIIT Pet dataset. The model is trained for pixel-wise segmentation of pet images, accurately detecting object boundaries.

### Key Features:
- **Improved UNet Architecture**: Additional encoder and decoder blocks, increased base channels, and optimized connections for better segmentation performance.  
- **Dataset**: The Oxford-IIIT Pet dataset, containing images and annotations of various pet breeds. 🐶🐱  
- **High Accuracy**: Achieves high pixel-level accuracy through meticulous training and evaluation.  
- **Efficient Storage**: Predictions are saved as `torch.uint8` tensors, significantly reducing memory usage.  

### Results:  
- **Test Set Accuracy**: After 30 epochs of training with 5 up and down blocks, the model achieved a pixel-level accuracy of **0.8986**. 🎯✨  

---

### Repository Contents:

- **model.py**: Implementation of the UNet architecture with customizable parameters.
- **train.py**: Script for training the model with detailed logging of accuracy and losses.
- **evaluate.py**: Tools for evaluating the model on the test set.
- **dataset.py**: Dataset preprocessing and augmentation pipelines.
- **predictions.pt**: Example predictions generated by the model.

---

This repository allows easy training and evaluation of the UNet model on the challenging task of image segmentation using the Oxford-IIIT Pet dataset.
