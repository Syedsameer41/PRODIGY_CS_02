# Pixel Manipulation Image Encryption Tool

A basic image encryption and decryption tool created as part of the Prodigy InfoTech Cyber Security Internship.

## Features

- Upload an image
- Display the image on HTML Canvas
- Manipulate RGB pixel values
- Encrypt image pixels using a mathematical operation
- Decrypt the encrypted image
- Preserve the Alpha channel
- Save the processed image as a PNG file

## How It Works

The tool reads the image pixel data in RGBA format.

Each pixel contains:

- R — Red
- G — Green
- B — Blue
- A — Alpha / Transparency

For encryption, the RGB values are modified using:

Encrypted = (Original + Key) % 256

For decryption:

Decrypted = (Encrypted - Key + 256) % 256

The Alpha value is kept unchanged.

## Technologies Used

- HTML
- JavaScript
- Canvas API
- ImageData API
- Blob API

## How to Use

1. Select an image.
2. Click **Encrypt Image**.
3. The image pixels are modified.
4. Click **Decrypt Image** to reverse the operation.
5. Click **Save Image** to save the processed image.

## Internship Task

- Internship: Prodigy InfoTech Cyber Security Internship
- Task: Task 02 — Pixel Manipulation
- Language: JavaScript

## Note

This project is an educational pixel-manipulation exercise and is not intended to provide secure cryptographic protection for sensitive data.

## Author

Syed Sameer
