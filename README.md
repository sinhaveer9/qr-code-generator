# QR Code Generator

## Overview

QR Code Generator is a Python project I developed to explore how information can be converted into QR codes using programming.

The program takes a predefined URL and generates a QR code that can be scanned to access the corresponding webpage. I built this project to gain practical experience working with Python libraries and understand how simple programs can automate everyday tasks.

## Technologies Used

- **Python:** Used to write the program and control the QR code generation process.
- **qrcode:** A Python library used to encode a URL into a QR code.
- **Pillow (PIL):** Used as an image-processing dependency to generate and save the QR code image.

## Key Features

- Converts a URL into a scannable QR code.
- Allows the QR code's box size and border width to be adjusted in the source code.
- Supports customization of foreground and background colors.
- Automatically saves the generated QR code as a PNG image.
- Uses a simple Python script that can be modified to generate QR codes for different URLs.

## Sample Output

The following QR code was generated using the Python script.

![QR Code generated using Python](youtube_qr.png)

## How It Works

The program begins by defining a URL that will be encoded into a QR code.

It creates a `QRCode` object using the qrcode library, with specified settings for the QR code version, box size, and border width.

The URL is added to the QR code object, and the library generates the QR code pattern. The program then creates an image using black foreground and white background colors.

Finally, the generated QR code is saved as `youtube_qr.png`.

## Installation and Usage

### 1. Clone the repository

```bash
git clone https://github.com/sinhaveer9/qr-code-generator.git
```

### 2. Open the project directory

```bash
cd qr-code-generator
```

### 3. Install the required library

```bash
python3 -m pip install "qrcode[pil]"
```

### 4. Run the program

```bash
python3 generate_qr.py
```

The program creates a PNG image named `youtube_qr.png` in the project directory.

To generate a QR code for a different website, change the `website_link` variable in `generate_qr.py` and run the script again.

## What I Learned

Developing this project helped me understand how Python can be used to generate practical outputs from simple inputs.

I learned how to work with an external library, configure a QR code object, modify image settings, and save generated files.

I also gained a better understanding of how changing parameters such as box size, border width, and image colors affects the output.

This project encouraged me to explore how programming can simplify repetitive tasks and create useful tools.

## Author

**Veer Sinha**

GitHub: [sinhaveer9](https://github.com/sinhaveer9)

This project is part of my independent learning in Python programming and computer science.
