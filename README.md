# Head-Tracking-
This repository contains a Python script that utilizes OpenCV to perform real-time head tracking using a webcam. The script detects and tracks the user's head in the video feed from the webcam.  ## Prerequisites  Before running this project, make sure you have the following: 
- Python 3.6 or higher - OpenCV library installed  ## Installation
1. **Clone the Repository** 
2. **Install Dependencies**
Open a terminal in the project directory and run:

## Usage

To run the head tracking script, navigate to the cloned repository, and execute the following command:

python head_tracker.py

The script will open a window displaying the live video feed from your webcam. Faces detected in the video will be highlighted with rectangles.

## Troubleshooting

### Common Issues

**Webcam Not Accessible**
- Make sure your webcam is properly connected.
- Ensure that no other application is using the webcam.

**OpenCV Installation Issues**
- If you encounter errors related to missing `cv2` module functions, try reinstalling OpenCV:
pip uninstall opencv-python
pip install opencv-python
