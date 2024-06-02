# HeidiSQL Password Retriever

This project provides a simple web application to retrieve passwords saved in HeidiSQL. It allows users to decrypt and copy the encoded password from the HeidiSQL settings file.

## Features

- Decrypt encoded passwords from HeidiSQL settings
- Copy decrypted password to clipboard
- User-friendly interface

## How to Use

To use the HeidiSQL Password Retriever:

1. Open HeidiSQL and select `File > Export Settings` to dump settings into a text file.
2. Open the exported text file and search for `Servers["Your Saved Configuration name"].Password`.
3. Copy and paste the encoded password from the HeidiSQL settings file into the "Encoded Password" field in the web application.
4. Follow the instructions to retrieve and copy the decrypted password.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/heidisql-password-retriever.git

## Author
Md Wali Mosnad Ayshik