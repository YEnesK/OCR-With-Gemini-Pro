## Gemini OCR: Document Analysis with Google's Generative AI

This project leverages Google's Gemini AI model to perform Optical Character Recognition (OCR) and document analysis on images, with a focus on Turkish documents. It extracts text, understands context, and provides structured responses in JSON format.

## Features

- Image preprocessing with OpenCV for enhanced OCR accuracy
- Integration with Google's Gemini 1.5 Flash model for advanced document analysis
- Support for Turkish language documents
- Conversion of extracted information to JSON format
- Flexible input prompts for customized analysis

## Requirements

- Python 3.7+
- google-generativeai
- opencv-python
- Pillow

## Setup
1. Install the required packages:

pip install google-generativeai opencv-python Pillow

2. Set up your Google API key in the script:

GOOGLE_API_KEY = "your-api-key-here"

os.environ["GOOGLE_API_KEY"] = GOOGLE_API_KEY

## Key Functions

- get_gemini_response(): Sends the image and prompt to the Gemini model and retrieves the response.
- input_image_setup(): Preprocesses the image using OpenCV, applying grayscale and thresholding for improved OCR.
- main(): Orchestrates the entire process from image input to final response.

## Note

This project is specifically designed for Turkish documents. The prompt and expected output are tailored for Turkish language content.

## Contributor

Yusuf Enes KURT
