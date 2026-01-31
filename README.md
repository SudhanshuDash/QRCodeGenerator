This project is a simple Python application that generates a QR (Quick Response) code for the website https://www.bioxsystems.com/

The program uses the Python qrcode library to encode the URL into a two-dimensional, machine-readable format and outputs the QR code as a PNG image file.

Requirements

Python 3.x

qrcode library with PIL support

How to Run

Install the required library:

pip install qrcode[pil]


Run the Python script:

python qr_generator.py

Output

Generates a QR code image named bioxsystems_qrcode.png

Scanning the QR code redirects to the Biox Systems website
