# QR_code_project

This project is a *command-line QR code generator* built using *Node.js*. It prompts the user to enter a URL, generates a corresponding QR code image, and saves both the QR image and the entered URL locally.

##  Features

* Interactive *CLI input* using inquirer
* Generates a *QR code image* from a user-provided URL
* Saves the QR code as a .png file
* Stores the entered URL in a .txt file
* Simple, lightweight, and beginner-friendly Node.js project

##  Technologies & Packages Used

* *Node.js*
* *inquirer* – For command-line user input
* *qr-image* – To generate QR codes
* *fs (File System)* – Native Node.js module for file operations

##  Project Structure


├── index.js
├── qr_img.png      // Generated QR code image
├── URL.txt         // Saved user input
├── package.json
└── README.md


##  Installation

1. Clone the repository:

   bash
   git clone https://github.com/your-username/qr-code-generator.git
   

2. Navigate to the project directory:

   bash
   cd qr-code-generator
   

3. Install dependencies:

   bash
   npm install
   

##  Usage

Run the application using:

bash
node index.js


* Enter a valid URL when prompted.
* A QR code image (qr_img.png) will be generated.
* The entered URL will be saved in URL.txt.

##  Purpose

This project is ideal for:

* Learning Node.js basics
* Understanding npm packages
* Practicing file handling with fs
* Building CLI-based applications
