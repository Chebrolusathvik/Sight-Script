# Image Captioning with VGG16, EfficientNetB7, and LSTM

This repository contains an image captioning model that leverages **VGG16** and **EfficientNetB7** for feature extraction and **LSTM (Long Short-Term Memory)** networks for sequential caption generation. The model is trained and evaluated on the **Flickr8k** dataset, and its performance is assessed using **BLEU scores** along with qualitative analysis of generated captions.

## Sight Script - The Image Captioning

## Project Overview

In this project, we explore the application of deep learning techniques to generate natural language descriptions (captions) for images. The model utilizes a **Convolutional Neural Network (CNN)** for image feature extraction and an **LSTM network** to generate captions based on those features.

### Key Features:
- **VGG16** and **EfficientNetB7** used for extracting image features.
- **LSTM** network employed for generating captions sequentially.
- **Data Augmentation** to improve model generalization and performance on unseen images.
- **Dataset Expansion**: The original **Flickr8k** dataset (8,000 images and 40,000 captions) was augmented using data augmentation techniques to increase the image count to **40,000** and the number of captions to **200,000**.
- Model evaluated on the **Flickr8k dataset** with **BLEU scores** to assess caption accuracy.

## Installation

To run the project, you need the following Python libraries:

- `tensorflow`
- `keras`
- `numpy`
- `matplotlib`
- `PIL`
- `pickle`


You can install the required libraries using `pip`:

```bash
pip install tensorflow keras numpy matplotlib pillow


