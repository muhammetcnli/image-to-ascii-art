# ASCII Art Converter

This Python script converts an image file to ASCII art. The resulting ASCII art is saved to a text file.

## Usage

1. Install the `PIL` library:

    ```
    pip install pillow
    ```

2. Rename your image to "my-image" and replace it with the allready given image.

3. Use the `asciiConvert` function to convert an image to ASCII art:

    ```python
    from PIL import Image

    def asciiConvert(image, type, saveas, scale):
        # Function content...

    if __name__ == '__main__':
        asciiConvert("my-image.jpg", "jpg", "ascii-art.txt", "3")
    ```
