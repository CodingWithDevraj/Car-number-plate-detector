# Car-Number-Plates-Detection

Project Summary: Car Number Plate Detection
This project implements an automatic Car Number Plate Detection System using computer vision and deep learning techniques. It captures vehicle images in real-time or from video sources, detects the license plate region, and extracts the plate number using Optical Character Recognition (OCR).

Key Features
 Real-time vehicle and number plate detection using OpenCV and pre-trained models

 License plate region extraction using contour analysis or YOLO/HAAR-based detection

 OCR for character recognition using Tesseract OCR

 Support for static images, live webcam, or video input

 Modular and clean codebase for easy customization and integration

 Technologies Used
Python, OpenCV

Tesseract OCR

NumPy, Imutils

(Optional) TensorFlow/Keras for training custom plate detection models

 Use Cases
Smart parking systems

Traffic law enforcement

Toll booth automation

Fleet management

## Steps To Run Code
1. Conda Create -p ./venv python=3.9 -y
2. conda activate ./venv

## Requirementx.txt install
Pip install -r requirements.txt

## Run File
python number_plate.py
