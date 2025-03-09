# Steganography

Steganography is a Python-based application that allows users to hide and retrieve secret text messages within image files using the Least Significant Bit (LSB) method.

## Features

- Hide a secret text message inside an image (PNG or JPG format).
- Retrieve hidden messages from an image.
- Save the modified image with the hidden message.
- User-friendly GUI built with Tkinter.

## Requirements

Make sure you have the following dependencies installed:

  **pip install pillow stegano**

## How To Use

- Run the Data-hide.py script:
  **python Data-hide.py**
- Click Open Image to select an image file.
- Enter the secret message in the text box.
- Click Hide Data to encode the message into the image.
- Click Save Image to save the modified image.
- Click Show Data to retrieve the hidden message from the image.
