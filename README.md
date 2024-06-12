# PRODIGY_CS_02
# 🖼️ Image Encryption Tool using Pixel Manipulation

## 📜 Overview
This project implements a simple image encryption and decryption tool using pixel manipulation. 
The tool allows users to load an image, apply encryption by swapping pixel values based on a user-provided key,
and then decrypt the image using the same key.

## 📚 Theoretical Explanation

### 🔒 Image Encryption
Image encryption is a method of transforming an image to make it unintelligible to unauthorized users. This can be achieved through various techniques such as pixel manipulation, where the pixels of the image are rearranged or altered based on a key. The key ensures that only users with the correct key can decrypt and access the original image.

### 🛡️ Cybersecurity Concepts
- **Encryption:** Protects the image data from unauthorized access by converting it into an unreadable format.
- **Decryption:** Converts the encrypted data back to its original format using the correct key.
- **Key:** A piece of information that determines the functional output of a cryptographic algorithm. In this case, it is used to control the pixel swapping pattern.

## 📝 Prerequisites
- Basic understanding of Python programming.
- Knowledge of image processing and GUI development with Tkinter.

## 💻 Software Requirements
- Python 3.x
- Libraries: `numpy`, `PIL` (Pillow), `tkinter`

## 🖥️ Hardware Requirements
- A computer with at least 2GB of RAM.
- Any operating system that supports Python 3.x.

## 🛠️ Tech Stack
- **Programming Language:** Python
- **Libraries:** NumPy, Pillow, Tkinter

## 🚀 How to Execute the Program

1. **Clone the Repository:**
    ```bash
   git clone <repository-directory> (https://github.com/trupti-K-ghenand/PRODIGY_CS_02)
   cd <repository-directory>
   ```

2. **Install the Required Libraries:**
   ```bash
   pip install numpy pillow
   ```

3. **Run the Program:**
   ```bash
   python `task2_imageEncryption.ipynb`
   ```

4. **Usage Instructions:**
   - Click on "Load Image" to select an image file.
   - Enter an integer key for encryption.
   - Click "Encrypt Image" to encrypt the loaded image.
   - Click "Decrypt Image" to decrypt the previously encrypted image using the same key.

## 📄 Code Details Overview

### `task2_imageEncryption.ipynb`

#### Imports
```python
import tkinter as tk
from tkinter import filedialog, messagebox
from PIL import Image, ImageTk
import numpy as np
import os
```
- `tkinter`: For creating the GUI application.
- `PIL` (Pillow): For image processing.
- `numpy`: For numerical operations and pixel manipulation.

#### Functions
- `generate_swap_pattern(key, length)`: Generates a pseudo-random swap pattern based on the key.
- `pixel_swap_encrypt(image_path, key)`: Encrypts the image by swapping its pixels based on the generated pattern.
- `pixel_swap_decrypt(image_path, key)`: Decrypts the image by reversing the pixel swapping.
- `load_image()`: Loads an image file selected by the user.
- `display_image(image)`: Displays the loaded or processed image on the canvas.
- `encrypt_image()`: Handles the encryption process.
- `decrypt_image()`: Handles the decryption process.
- `get_key()`: Retrieves and validates the key entered by the user.

#### GUI Setup
- **Main Window**: The root window is set up with a title and dimensions.
- **Canvas**: Used to display images.
- **Labels and Entry**: For user input of the encryption key.
- **Buttons**: For loading the image, encrypting, and decrypting.


## Thanks👏
Thank you for using and contributing to this repository! I sincerely appreciate your interest and hope you find the Caesar Cipher programs helpful for your cryptography learning journey.

## Contribute🤝

Welcome all contributions to enhance these programs and expand their capabilities.

To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push them to your branch.
4. Open a pull request describing your changes.

✅Please ensure your code adheres to the existing style and includes appropriate documentation and tests.

🛡️Secure coding!🛡️

