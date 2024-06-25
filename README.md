# QR-Code-Generator
This project is a simple QR code generator that prompts the user for a URL, generates a QR code image from the URL, and saves both the QR code image and the URL to files. It is implemented using Node.js and utilizes the inquirer package for user input, the qr-image package for QR code generation, and the fs package for file system operations.
Sure! Here’s a template for your project description on GitHub:


## Features

- Prompts the user to input a URL.
- Validates the URL input.
- Generates a QR code image from the provided URL.
- Saves the QR code image as `qr_img.png`.
- Writes the provided URL to a text file named `URL.txt`.

## Installation

To run this project, you need to have [Node.js](https://nodejs.org/) installed. Then, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/qr-code-generator.git
    cd qr-code-generator
    ```

2. Install the required packages:
    ```bash
    npm install
    ```

## Usage

Run the script using Node.js:
```bash
node your_script_name.js
```

Follow the on-screen prompt to input the URL. The QR code image will be saved as `qr_img.png`, and the URL will be saved to `URL.txt`.

## Dependencies

- [inquirer](https://www.npmjs.com/package/inquirer): For interactive command-line user interfaces.
- [qr-image](https://www.npmjs.com/package/qr-image): For generating QR code images.
- [fs](https://nodejs.org/api/fs.html): Node.js file system module for file operations.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.


