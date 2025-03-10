# Stamp-and-Signature-differentiator
Overview
This project utilizes computer vision techniques to detect and separate text, signatures, and stamps from scanned documents or 
images. The system processes grayscale images to identify and highlight these elements, making it useful for automating document verification and analysis.

Features:
Text Detection: Uses adaptive thresholding and morphological operations to identify and remove text regions.
Signature Detection: Excludes text and isolates handwritten signatures based on density, aspect ratio, and irregular shape.
Stamp Detection: Identifies solid, near-square stamps using connected component analysis.
Output Generation: Highlights detected signatures in green and stamps in red on the original image.

Tools & Technologies Used:

Programming Language: Python
Libraries:
OpenCV (Image Processing)
NumPy (Matrix Operations)
skimage (Connected Component Analysis, Region Properties)
