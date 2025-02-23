# ObjectDetection

## Overview
ObjectDetection is a real-time object detection system that utilizes deep learning models to identify and classify objects in images and video streams. It leverages OpenCV and pre-trained DNN models to provide accurate and efficient object detection.

## Features
- **Real-Time Object Detection:** Detects objects in images and video streams.
- **Pre-trained DNN Models:** Supports YOLO, MobileNet-SSD, and other popular models.
- **Bounding Box Visualization:** Draws bounding boxes around detected objects.
- **Multi-Class Classification:** Identifies and labels multiple object classes.
- **Live Camera Feed Integration:** Processes frames from a webcam or external video sources.

## Technologies Used
- **Programming Language:** Python
- **Deep Learning Frameworks:** TensorFlow, OpenCV, DNN module
- **Models Supported:** YOLO, MobileNet-SSD, COCO dataset

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/shivamcy/ObjectDetection.git
   ```
2. Navigate to the project folder:
   ```sh
   cd ObjectDetection
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the object detection script:
   ```sh
   python detect.py --model yolov3
   ```

## Usage
- To detect objects in an image:
  ```sh
  python detect.py --image path/to/image.jpg
  ```
- To process a live webcam feed:
  ```sh
  python detect.py --webcam
  ```
- To use a different model:
  ```sh
  python detect.py --model mobilenet-ssd
  ```

## Contribution
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Make your changes and commit: `git commit -m 'Added new feature'`
4. Push to your fork: `git push origin feature-branch`
5. Create a pull request.



