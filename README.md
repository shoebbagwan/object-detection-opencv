# object-detection-opencv
Simple Object Detection using OpenCV
***Overview
This project demonstrates a basic object detection system using Python and OpenCV.
It leverages background subtraction and contour detection to identify moving objects in a live webcam feed.
Bounding boxes are drawn around detected objects, making it a simple yet effective introduction to computer vision.

*** Features
- Real-time object detection using webcam.
- Background subtraction with cv2.createBackgroundSubtractorMOG2().
- Contour detection to identify moving objects.
- Ignores small movements/noise by setting a minimum contour area.
- Displays bounding boxes around detected objects.

*** Project Structure
object_detection.py   # Main Python script
README.md             # Documentation file



***Requirements
- Python 3.x
- OpenCV library
Install dependencies:
pip install opencv-python



***How to Run
- Clone or download this repository.
- Save the script as object_detection.py.
- Open a terminal/PowerShell and navigate to the project folder:
cd path\to\project
- Run the script:
python object_detection.py



***Usage
- The program will open your default webcam.
- Moving objects will be highlighted with green bounding boxes.
- Press q to quit the program.

***Example Output
Objects in motion will be detected and outlined like this:
[ Webcam feed with bounding boxes around moving objects ]



***Future Improvements
- Add object tracking (e.g., using Centroid Tracking or SORT).
- Integrate YOLO/SSD for advanced detection.
- Save detection logs or video output.
- Extend to vehicle counting or emotion recognition projects.
