# Cryptographic Algorithms Application

## Overview
This application provides a graphical user interface (GUI) for performing various cryptographic operations, including RSA encryption/decryption, Caesar cipher, Vigenère cipher, combined Caesar+RSA and Vigenère+RSA methods, and image encryption/decryption. The application is built using Python with the `tkinter` and `customtkinter` libraries for the GUI, and it includes mathematical operations for cryptographic algorithms.

## Features
1. **RSA Encryption/Decryption**:
   - Generate RSA keys using prime numbers.
   - Encrypt and decrypt text using RSA algorithm.
   - Display detailed arithmetic steps for key generation.

2. **Caesar Cipher**:
   - Encrypt and decrypt text using the Caesar cipher method.
   - Specify a shift value for the cipher.

3. **Vigenère Cipher**:
   - Encrypt and decrypt text using the Vigenère cipher method.
   - Provide a key for the cipher.

4. **Combined Methods**:
   - **Caesar + RSA**: Encrypt text with Caesar cipher and then RSA, or decrypt with RSA followed by Caesar.
   - **Vigenère + RSA**: Encrypt text with Vigenère cipher and then RSA, or decrypt with RSA followed by Vigenère.

5. **Image Encryption/Decryption**:
   - Encrypt images using RSA and pixel shuffling.
   - Decrypt images using the corresponding keys.
   - Save encrypted/decrypted images and keys.

6. **User-Friendly Interface**:
   - Tabbed layout for easy navigation between different cryptographic methods.
   - Help buttons for guidance on each tab.
   - Light/Dark theme toggle for customization.

## Installation
1. Ensure you have Python installed (version 3.7 or higher recommended).
2. Install the required libraries using pip:
   ```bash
   pip install tkinter customtkinter pillow numpy
