# Steganography

This project implements Image Steganography, a technique for hiding secret messages inside images using Python. The hidden message can be retrieved only using the correct passcode.  

## How It Works  
1. **Encryption (Hiding a Message)**  
   - A secret message is embedded into an image file by modifying pixel values.  
   - The message is stored in a way that does not distort the image visibly.  
   - A passcode is required for decryption.  

2. **Decryption (Extracting the Hidden Message)**  
   - The encoded image is processed to extract the original hidden message.  
   - The correct passcode must be entered to reveal the message.  
