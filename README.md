# QR Code Generator

![image](https://github.com/fixmanish/qr-code-generator-js/assets/131751286/693ba8d0-1069-48b7-bb89-0b7a66eba177)

![image](https://github.com/fixmanish/qr-code-generator-js/assets/131751286/4972ad28-db96-4e03-b306-492b3ae33e5d)

📚 This is a simple Node.js project that generates a QR code for a given URL using the following npm packages:

1. **inquirer**: A powerful command-line interface (CLI) user interface library for Node.js. It provides an easy way to prompt and receive user inputs in the terminal.

2. **fs**: The built-in 'fs' module in Node.js allows you to work with the file system. In this project, it is used to write the generated QR code image to a file.

3. **qr-image**: A package that enables the generation of QR codes in Node.js. It provides an easy-to-use API to generate QR codes based on the given content.

## How to Run

To run the QR code generator, follow these steps:

First type 'cd' then rag the downloaded file to your Visual  studio codee editor's console to get the path of file directly
⚠ You will havr to install node packages by the command 'node i inquirer qr-image' 

1. Make sure you have Node.js installed on your machine.

2. Clone this repository to your local machine.

3. Navigate to the project directory in your terminal.

4. Install the required dependencies by running the following command:

   ```
   npm install
   ```

5. Run the application using the following command:

   ```
   node index.js
   ```

6. You will be prompted to enter the URL for which you want to generate a QR code.

7. After entering the URL, the application will generate a QR code and save it to a file called `qrcode.png` in the project directory.

## Example Usage

1. Run the application by typing `node index.js` in the terminal.

2. Enter the URL for which you want to generate a QR code, such as `https://example.com`.

3. The application will generate a QR code and save it to the `qrcode.png` file.

4. Open the `qrcode.png` file to see the generated QR code.

## Dependencies

This project uses the following npm packages:

- [inquirer](https://www.npmjs.com/package/inquirer)
- [fs](https://nodejs.org/api/fs.html)
- [qr-image](https://www.npmjs.com/package/qr-image)

## Credits

This project was completed as part of the Full Stack Web Development course by Angela Yu on Udemy.

🎉 Enjoy generating QR codes with ease!
