# QR-code-Generator
This Node.js project allows users to input a URL, generate a QR code, and save both the QR code image and the URL in text files. It leverages the following npm packages:  inquirer: For prompting the user to enter a URL.  qr-image: To generate a QR code from the URL.  fs (File System): To save the QR code image and the URL in separate files.

Project Summary : 

This is a simple Node.js project that helps users turn any URL into a QR code image through the command line. It also saves the original URL to a text file for reference. It's a great starting point for learning how to work with user input, generate QR codes, and handle files using Node.js.

What This Project Does

Prompts the user to enter a URL.

Generates a QR code from the entered URL.

Saves the QR code as an image file (qr_image.png).

Saves the URL as plain text in a file (message.txt).

Technologies Used

Node.js – JavaScript runtime environment

inquirer – For asking the user to input a URL

qr-image – To generate the QR code

fs – Node.js file system module to handle file writing

<img width="661" height="160" alt="Screenshot 2025-10-19 at 1 08 15 PM" src="https://github.com/user-attachments/assets/32fdd7eb-562f-4718-b10d-24e9083cc93a" />

You'll be asked to enter a URL. After entering it:

A file named qr_image.png will be created with the QR code.

A file named message.txt will be created with the URL you entered.

<img width="283" height="201" alt="Screenshot 2025-10-19 at 1 09 11 PM" src="https://github.com/user-attachments/assets/f911a427-84a9-4b24-b968-6eb7709d9755" />

