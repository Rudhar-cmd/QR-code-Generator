# QR Code Generator

This Node.js project allows users to input a URL, generate a QR code, and save both the QR code image and the URL in text files.

## Technologies Used

- **Node.js** – JavaScript runtime environment
- **inquirer** – For prompting the user to enter a URL
- **qr-image** – To generate the QR code
- **fs** – Node.js file system module to handle file writing

---

## Project Summary

This is a simple command-line Node.js app that helps users turn any URL into a QR code image. It also saves the original URL to a text file for reference.

It’s ideal for beginners who want to learn how to:

- Work with user input via the command line
- Generate and save QR codes
- Handle file operations in Node.js

---

## Features

- Prompts the user to enter a URL
- Generates a QR code from the entered URL
- Saves the QR code as an image file (`qr_image.png`)
- Saves the URL as plain text in a file (`message.txt`)

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/qr-code-generator.git
