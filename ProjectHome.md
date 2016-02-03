These scripts add functionality to the Tesseract OCR engine by automating some tasks and by preprocessing images with other utilities such as imagemagick. The script receives an image and returns a string. The goal of the script is to be able to process many variations of files automatically while inputting as few options as possible.

Usage:
The script can be called from other python scripts and the testing script allows using it from the command line (assuming you have python installed). See the wiki for more information.

Added functionality to Tesseract:
OCRing of color images

What it does:
The script takes a TIFF image, converts it to grayscale, passes it to Tesseract and then returns a string.

What it will do:
OCR multipage TIFF images.
OCR PDF images.

These scripts are written by and are used on ABillionBillion.com. A Billion Billion offers free document management and free OCR for everyone.