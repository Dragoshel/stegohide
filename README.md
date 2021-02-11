# Stegohide desktop utility for embedding secret messages into jpeg images

## Uses

* For embedding use the 'encode' followed by the path of the image and your message at the end.
    
    Example:
    ```sh
    python3 stegohide.py encode ~/MOCK_DIR/MOCK_IMAGE.JPEG "Your secret message here"
    ```
    
    Note: This use creates an image called encoded.png in the directory you are working in.
    
* For decoding information out of the modified image, use the 'decode' flag followed by the path to your embedded image.
    
    Example:
    ```sh
    python3 stegohide.py decode ~/MOCK_DIR/MOCK_ENCODED_IMAGE.JPEG
    ```
