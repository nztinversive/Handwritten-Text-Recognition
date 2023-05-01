# Handwritten Text Recognition

This repository contains a Python script for recognizing handwritten text in images using the TrOCR model from the Hugging Face Transformers library.

## Dependencies

- Python 3.6 or higher
- [Pillow (PIL)](https://pillow.readthedocs.io/en/stable/)
- [Transformers](https://huggingface.co/transformers/) library by Hugging Face

To install the required packages, run:


pip install pillow transformers
Usage
Place the images you want to process in the data folder. The script supports .jpg, .jpeg, and .png formats.
Run the script:

python main.py
The script will process each image in the data folder and save the recognized text to a separate .txt file named <image_name>_output.txt.
Example
Input image (testphoto4.jpeg):

Example Image

Output text file (testphoto4_output.txt):


This is an example
of handwritten text.
Model
The script uses the microsoft/trocr-large-handwritten model from the Hugging Face Model Hub. You can find more information about the model here.

License
This project is open-source and available under the MIT License.
