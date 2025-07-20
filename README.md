 😀 Real-Time Face and Smile Detection using OpenCV

This project uses OpenCV and Haar Cascade Classifiers to detect human faces and smiles in real time using a webcam. The program draws bounding boxes around detected faces and smiles and displays the live video feed with annotations.


📌 Project Overview

- Captures video from webcam using OpenCV
- Converts video frames to grayscale
- Detects faces using `haarcascade_frontalface_default.xml`
- Detects smiles using `haarcascade_smile.xml` (or custom `smile.xml`)
- Draws rectangles around detected faces and smiles
- Exits when the user presses the `'q'` key


 🛠️ Tech Stack

- Python 3.
- OpenCV
- Haar Cascade Classifier XML files


