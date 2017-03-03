# Local Binary Patterns implementation using Python 3

`Local Binary Pattern (LBP)` is a simple yet very efficient texture operator which labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number. 
[Click here to learn more.](http://www.scholarpedia.org/article/Local_Binary_Patterns "Local Binary Pattern (LBP)")

Moreover, I also added a pattern code for two bins only to compare the result of LBP and two bin pattern.

## Packages Used
The program is coded using Windows 10 (64 bit) operating system with Python version 3.5.2.

The following packages are necessary to run the program:

Package | Version | Installation
--- | --- | ---
**OpenCV** | 3.2.0 | `pip install opencv-python`
**Numpy** | 1.11.3 | `pip install numpy`
**Matplotlib** | 1.5.3 | `pip install matplotlib`

## Image Used
![alt Lena Söderberg](https://raw.githubusercontent.com/arsho/local_binary_patterns/master/lenna.jpg)
* [Click to download original image of Lena Söderberg](https://raw.githubusercontent.com/arsho/local_binary_patterns/master/lenna.jpg "Lena Söderberg")

### Output of `lbp.py`
The output consists of the gray scale image, LBP representation image and LBP histogram.
![alt output of lbp](https://raw.githubusercontent.com/arsho/local_binary_patterns/master/screenshot/lbp_output.png)

### Output of `two_bin.py`
The output consists of the gray scale image, Two Bin representation image and Two Bin histogram.
![alt output of lbp](https://raw.githubusercontent.com/arsho/local_binary_patterns/master/screenshot/two_bin_output.png)

### References
* [Local Binary Patterns with Python & OpenCV](http://www.pyimagesearch.com/2015/12/07/local-binary-patterns-with-python-opencv/ "Local Binary Patterns with Python & OpenCV")
* [Local Binary Patterns Wiki](https://en.wikipedia.org/wiki/Local_binary_patterns "Local Binary Patterns Wiki")

***

### Feel free to contribute for improvement.