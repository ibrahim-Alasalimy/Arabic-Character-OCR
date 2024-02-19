# Arabic-Character-OCR
## Arabic OCR Character Model

This project aims to develop an Optical Character Recognition (OCR) model specifically designed for recognizing Arabic characters.

## Overview

Arabic OCR is a challenging task due to the complexities of the Arabic script, which includes various ligatures, diacritics, and contextual forms. This model utilizes deep learning techniques to accurately recognize Arabic characters from images.

## Features

- Recognizes Arabic characters from images
- Supports various fonts, styles, and sizes
- Preprocessing pipeline for image enhancement
- Trained on a large dataset of Arabic characters

## Usage

To use the Arabic OCR model, we recommend the usage of Google Colab for easier execuation and faster data processing

## System Design

Our OCR system integrates DCNNs for feature extraction and Bi-LSTM RNNs for sequence understanding. This concise approach excels in accurate Arabic character recognition for efficient handwritten OCR.

## Data Preprocessing

In data preprocessing, we optimize images by cropping unnecessary black space, resizing to 64x32 pixels (with added padding if needed), and skeletonizing for sharper letter outlines. This ensures a uniform and refined dataset, emphasizing morphological similarities despite varying handwriting styles.

## Dataset

We have used a dataset of 70,000 Arabic images, equally divided among the 28 letters. This diverse set captures various handwriting styles, guiding adjustments in the OCR pipeline for enhanced performance.
This is the dataset we used: https://www.kaggle.com/datasets/mahmoudreda55/arabic-letters-numbers-ocr
this datasets include every version of the arabic letter. For example, a letter at the beginning, middle, and at the end.

## Modeling

We Have used a neural network with CNNs for feature extraction and Bi-LSTM RNNs for sequence understanding. CNNs use two layers with batch normalization and ReLu activation, processing 64x32-pixel images. The output then flows into a single Bidirectional-LSTM with 256 units, enhancing the network's ability to capture dependencies. This streamlined architecture is optimized for precise Arabic character recognition in handwritten word images, preventing overfitting with a dropout layer.

## Result

The OCR model achieved an impressive accuracy of 97.5%, demonstrating its proficiency in accurately recognizing diverse handwritten Arabic characters. 

## Future Improvements

In the future, potential improvements could focus on enhancing the segmentation model to achieve more effective word-to-letter segmentation. Fine-tuning the segmentation process, perhaps through the exploration of advanced techniques or additional training data, may lead to improved accuracy in isolating individual letters within handwritten Arabic words. This refinement would contribute to further optimizing the overall OCR system, ensuring a more precise and comprehensive recognition of characters in diverse handwriting styles.

## Special Thanks

Special thanks to Hana Medhat for their invaluable resources, which greatly aided us in completing our work. Your expertise and generosity in sharing knowledge are truly appreciated.

