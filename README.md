# Age and Gender Detection using OpenCV

## Overview

Age and Gender Detection is a computer vision project that uses Deep Learning and OpenCV to predict the approximate age group and gender of a person from an image or webcam feed.

The system first detects faces in the input image and then applies pre-trained neural network models to estimate gender and age categories. The project demonstrates the practical application of Deep Learning in facial analysis and real-time computer vision.

---

## Features

* Real-time face detection using OpenCV DNN
* Gender prediction (Male/Female)
* Age group prediction
* Webcam support
* Image-based prediction
* Easy to run and lightweight implementation

---

## Technology Stack

* Python
* OpenCV
* Deep Neural Networks (DNN)
* Caffe Pre-trained Models

---

## Project Structure

```
Age-Gender-Detection/
│
├── detect.py
├── opencv_face_detector.pbtxt
├── opencv_face_detector_uint8.pb
├── age_deploy.prototxt
├── age_net.caffemodel
├── gender_deploy.prototxt
├── gender_net.caffemodel
├── README.md
└── .gitignore
```

---

## Models Used

This project uses pre-trained Deep Learning models for:

* Face Detection
* Age Classification
* Gender Classification

The age prediction classes are:

* 0-2 Years
* 4-6 Years
* 8-12 Years
* 15-20 Years
* 25-32 Years
* 38-43 Years
* 48-53 Years
* 60-100 Years

The gender prediction classes are:

* Male
* Female

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/Age-Gender-Detection.git
cd Age-Gender-Detection
```

### Install Dependencies

```bash
pip install opencv-python
```

---

## Usage

### Predict Age and Gender from an Image

```bash
python detect.py --image image.jpg
```

### Predict Age and Gender using Webcam

```bash
python detect.py
```

Press **Ctrl + C** to stop the webcam stream.

---

## Sample Output

```
Gender: Male
Age: 25-32 Years
```

---

## Applications

* Smart Surveillance Systems
* Demographic Analysis
* Retail Customer Analytics
* Human-Computer Interaction
* Audience Measurement
* Educational Computer Vision Projects

---

## Future Improvements

* Improve prediction accuracy using modern CNN architectures
* Support multiple faces simultaneously
* Deploy as a web application
* Add emotion detection
* Add face recognition functionality

---

## Disclaimer

The predicted age is an approximate age range and may vary depending on image quality, lighting conditions, facial expressions, pose, and other environmental factors.

---

## License

This project is intended for educational and learning purposes.
