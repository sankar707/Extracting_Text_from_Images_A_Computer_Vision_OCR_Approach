**OCR Text Extraction Project**

This project focuses on extracting text from images using Optical Character Recognition (OCR). By leveraging image preprocessing techniques and OCR engines such as Tesseract, the system identifies and converts printed or handwritten text from images into machine-readable format. The model currently achieves an accuracy of approximately 70–75%, depending on image clarity, lighting conditions, font style, and noise levels.

**Features**

Extracts text from images with moderate accuracy (70–75%).

Supports common image formats like JPG, PNG, and TIFF.

Includes preprocessing steps such as grayscale conversion, thresholding, and noise reduction.

Easily customizable for improved accuracy with additional preprocessing or model tuning.

**Tech Stack**

Python

Tesseract OCR / EasyOCR

OpenCV for image preprocessing

**How It Works**

Input image is preprocessed (resize, remove noise, threshold).

The OCR engine runs on the processed image.

Extracted text is returned or saved for further use.
