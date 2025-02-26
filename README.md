# Steganography Image Encryption & Decryption

This project implements **steganography** to hide and retrieve secret messages within an image using **OpenCV (cv2)**. It allows users to **encrypt** a message into an image and later **decrypt** it using a password.

## Features
- Hide a secret message inside an image.
- Password-protected encryption and decryption.
- Uses pixel manipulation for message embedding.
- Simple command-line interface.

## Technologies Used
- **Python 3**
- **OpenCV (cv2)** – for image processing
- **OS Module** – to open encrypted images

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/steganography.git
   cd steganography
Install dependencies:
pip install opencv-python
Usage
Encrypting a Message

    Place an image (msd.jpg) in the same directory.
    Run the script:

   python steganography.py


    Enter the secret message and a password.
    The script will generate an encrypted image (Encryptedmsg.jpg).

Decrypting a Message

    Run the script again.
    Enter the correct password to retrieve the hidden message.

Limitations

    The program modifies image pixels directly, which may introduce noticeable changes.
    The method used is basic and lacks advanced encryption, making it vulnerable to steganalysis.
    Works best with images with a high number of pixels.

Future Improvements

    Improve security by integrating encryption before embedding messages.
    Support for multiple image formats and larger messages.
    Implement robustness against image modifications like compression.

License

This project is open-source under the MIT License.
