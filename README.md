# age-gender-detector
This Python script uses OpenCV and deep learning models to detect faces and predict gender and age in images or video streams. It draws bounding boxes around faces and displays predicted gender and age in real-time. It supports live video feed processing and works with pre-trained models for face detection and classification.

## Features
- **Face Detection**: Detects faces in images or video streams with bounding boxes.
- **Gender Prediction**: Predicts whether the person is Male or Female.
- **Age Prediction**: Estimates the person’s age range (e.g., 0-5, 5-10, etc.).
- **Real-Time Processing**: Works with live video, providing predictions in real time.
- **Overlay Information**: Displays predicted gender and age on the detected faces.

## Requirements
- Python 3.x
- OpenCV (`cv2`)
- Pre-trained deep learning models:
  - `opencv_face_detector.pbtxt`, `opencv_face_detector_uint8.pb`
  - `age_deploy.prototxt`, `age_net.caffemodel`
  - `gender_deploy.prototxt`, `gender_net.caffemodel`

1. Clone the Repository: 
  git clone https://github.com/your-username/age-gender-detection.git
  cd age-gender-detection

2. Set Up Python Environment: 
   python --version
3. Install Required Dependencies: 
   python -m venv venv
   pip install opencv-python opencv-python-headless
4. Download the pre-trained models and place them in the project directory:
- [Face detection model](https://github.com/opencv/opencv/tree/master/samples/dnn/face_detector)
- [Age and Gender models](https://github.com/priya-dwivedi/face_and_age_gender_detection)
  
  To run the script on an image:
5. Running the Script: 
    Run on Live Webcam Feed : python detect.py


   




