# caesar-cipher-algorithm
 "A simple implementation of the Caesar Cipher encryption algorithm."

 Caesar Cipher Encryption & Decryption Tool

Description

This Python program allows users to encrypt and decrypt text using the Caesar Cipher algorithm. Users can input a message and a shift value to perform encryption and decryption.

Features

Encrypts a given message using a shift-based substitution method.

Decrypts a previously encrypted message by reversing the shift.

Supports both uppercase and lowercase letters.

Keeps non-alphabetic characters unchanged.

How It Works

The program shifts each letter of the input text by a specified number of positions in the alphabet. For decryption, it shifts the letters back by the same amount.

Usage

Requirements

Python 3.x installed on your system.

Running the Program

Clone this repository or download the caesar_cipher.py file.

Open a terminal or command prompt and navigate to the project directory.

Run the script:

python caesar_cipher.py

Enter the required inputs when prompted:

Choose encryption (E) or decryption (D).

Enter the message to process.

Provide the shift value (a number).

View the encrypted or decrypted output.

Example

Do you want to (E)ncrypt or (D)ecrypt? e
Enter the message: Hello World
Enter the shift value: 3
Output: Khoor Zruog

Notes

Shift values greater than 26 cycle back through the alphabet.

The program maintains spaces, punctuation, and numbers unchanged.

License

This project is open-source and available under the MIT License.

Author
JUJJAVARAPU APARNA


