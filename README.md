# Arabic-Character-OCR
# Arabic OCR Character Model

This project aims to develop an Optical Character Recognition (OCR) model specifically designed for recognizing Arabic characters.

## Overview

Arabic OCR is a challenging task due to the complexities of the Arabic script, which includes various ligatures, diacritics, and contextual forms. This model utilizes deep learning techniques to accurately recognize Arabic characters from images.

## Features

- Recognizes Arabic characters from images
- Supports various fonts, styles, and sizes
- Preprocessing pipeline for image enhancement
- Trained on a large dataset of Arabic characters

## Installation

To install the Arabic OCR model, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Download the pre-trained model weights (add link here) and place them in the `models` directory.

## Usage

To use the Arabic OCR model, follow these steps:

1. Import the `ArabicOCR` class from `arabic_ocr.py`.
2. Initialize the OCR model.
3. Load an image containing Arabic text.
4. Call the `recognize_text` method with the image as input to get the recognized text.

Example:

```python
from arabic_ocr import ArabicOCR

# Initialize the OCR model
ocr_model = ArabicOCR()

# Load an image containing Arabic text
image = "example_image.jpg"

# Recognize text in the image
recognized_text = ocr_model.recognize_text(image)

print("Recognized Text:", recognized_text)


#++++++++++++++++++++++++++++++
Arabic OCR Project - By INNOV8
++++++++++++++++++++++++++++++ 
Team:			       
Mohamed Elhaj                  
Ibrahim AlSalimy               
Yousef Khalil		       
Mohammed Zein                  
Safeer Ahamed
Ahmed Alobahi                  
++++++++++++++++++++++++++++++
For The Notebooks, Recommended
To run them using Google Colab
++++++++++++++++++++++++++++++
