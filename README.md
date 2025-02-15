# AICTE-Edunet-Steganography-Project

This project implements a simple *image steganography, a technique for hiding secret messages inside digital images. The system modifies pixel values to encode and retrieve hidden messages securely. Additionally, it includes **password protection* for enhanced security.


## Requirements

Ensure you have the following installed before running the scripts:

- Python 3.x
- OpenCV (`cv2`)

Install dependencies using:
```bash
pip install opencv-python
```

## Usage

### Encryption
1. Run encryption.py:
bash
python encryption.py

2. Enter the secret message.
3. Provide a passcode for encryption.
4. The script embeds the message into image.png and saves it as encryptedImage.png.

### Decryption
1. Run decryption.py:
bash
python decryption.py

2. Enter the correct passcode to retrieve the hidden message.
3. The hidden message will be extracted and displayed.

## Note
- The image should have enough pixels to store the message.
- If an incorrect passcode is provided, decryption will fail.
## License
This project is open-source and available for use and modification.
