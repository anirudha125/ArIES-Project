# Neural Style Transfer Project

## Project Overview
This project implements neural style transfer, a technique that blends the content of one image with the style of another using a convolutional neural network (CNN). The pre-trained VGG-19 model is used to extract content and style features from the images. By minimizing the content and style losses, a new image is generated that combines the content of the content image and the style of the style image.


## Dependencies
The project requires the following libraries and dependencies:

- Python 3.7+
- torch
- torchvision
- Pillow
- numpy
- matplotlib

## Code Summary
1. **FeatureExtractor Class**: Uses the VGG-19 model to extract features.
2. **Image Preprocessing**: Resizes and normalizes images.
3. **Style and Content Loss Calculation**: Computes losses to blend style and content.
4. **Optimization**: Uses the Adam optimizer to update the generated image.

## Reference
https://arxiv.org/pdf/1508.06576
