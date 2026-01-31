# QR Code Generator – Python

A simple Python application that generates a QR (Quick Response) code for the Biox Systems website.

## Encoded URL
https://www.bioxsystems.com/

## Features
- Generates a QR code from a URL
- Saves output as a PNG image
- Uses standard QR formatting for reliable scanning

## Requirements
- Python 3.x
- qrcode library with PIL support

## Installation
pip install qrcode[pil]

## Usage
python qr_generator.py

## Output
bioxsystems_qrcode.png  
Scanning the QR code redirects to the Biox Systems website.

## Project Structure
.
├── qr_generator.py  
├── README.md  
└── bioxsystems_qrcode.png  

## Description
This project demonstrates how Python can be used to generate QR codes by encoding a URL into a two-dimensional, machine-readable format using the qrcode library.
