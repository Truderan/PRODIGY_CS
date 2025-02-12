Image Encryption & Decryption Tool

A simple Python-based tool that encrypts and decrypts images using XOR encryption. This tool allows users to securely obfuscate images and later restore them using the same key.

✨ Features

✅ Encrypts any PNG, JPG, or JPEG image using a user-defined key.
✅ Decrypts encrypted images back to their original form.
✅ Uses XOR encryption, a simple yet effective bitwise operation.
✅ Works on Windows, Mac, and Linux with Python 3 installed.

📌 How It Works

This tool applies XOR (Exclusive OR) encryption on each pixel of an image using a key (a number between 1-255). Since XOR is reversible, applying the same operation again restores the original image.

Encryption: Encrypted Pixel = Original Pixel ⊕ Key
Decryption: Decrypted Pixel = Encrypted Pixel ⊕ Key
Reminder: The same key must be used for both encryption and decryption!

🚀 Installation Prerequisites

Ensure you have Python 3 installed along with the required library:

(sh)
pip install pillow numpy

Run the script and follow the on-screen prompts:

(sh)
python image_encryptor.py

🛠 Troubleshooting

❌ File Not Found?
✔️ Ensure you provide the correct file path.
✔️ If the image is in the same directory, just enter the filename.

❌ Wrong Decryption Output?
✔️ Make sure you use the same key used for encryption.

❌ Invalid Key?
✔️ Enter a number between 1-255 when prompted.

📜 License

This project is open-source under the MIT License. Feel free to modify and improve it!

💡 Future Improvements

🚀 Add support for stronger encryption methods (AES, RSA).
🚀 Implement GUI version for easier use.
🚀 Improve error handling for better user experience.

🙌 Credits
Created by Falobi Akinwunmi, inspired by basic cryptography principles.
