ASCII Art Converter
Overview
This Python script converts an image into ASCII art. It resizes the image to a specified scale and replaces each pixel with an ASCII character based on its brightness level.

Requirements
Python 3.x
Pillow (Python Imaging Library)
Installation
Clone this repository or download the ascii_converter.py file.
Install Pillow library using pip:
Copy code
pip install Pillow
Usage
Import the asciiConvert function from ascii_converter.py into your Python script.
Call the asciiConvert function with the following parameters:
image: Path to the input image file.
type: File format of the input image (e.g., "jpg", "png").
saveas: Path to save the ASCII art file.
scale: Scaling factor for resizing the image (larger values create smaller ASCII art).
Example:

python
Copy code
from ascii_converter import asciiConvert

asciiConvert("my-image.jpg", "jpg", "ascii-art.txt", "3")
Notes
The script converts each pixel's brightness to an ASCII character based on predefined brightness ranges. You can modify these ranges in the script for different ASCII representations.
Experiment with different scaling factors (scale parameter) to achieve desired ASCII art size and detail.
License
This project is licensed under the MIT License - see the LICENSE file for details.
