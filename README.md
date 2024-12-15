Finger Counting with MediaPipe and OpenCV

This project uses MediaPipe and OpenCV to detect and count the number of fingers raised in real-time. By leveraging MediaPipe’s hand tracking solution, the system identifies the landmarks of the hand and uses these coordinates to determine whether each finger is open or closed. The count is updated continuously as the user moves their hand, providing instant feedback.

Key Features:
Real-time Hand Detection: Using MediaPipe's hand tracking model, the project detects and processes multiple hands in the frame.
Finger Counting Logic: Based on the position of specific hand landmarks, the system calculates how many fingers are raised, distinguishing between open and closed fingers.
User Interface: A visual representation of the finger count is displayed on the screen, making it easy to track the count during interactions.
Technologies Used:
MediaPipe: For hand landmark detection and tracking.
OpenCV: For real-time image processing and video capture.
Python: For combining and implementing the logic behind finger counting and hand detection.
This project also strengthened my understanding of image processing and helped me apply concepts learned in José Portilla's "Python for Computer Vision with OpenCV and Deep Learning" course. It’s an exciting demonstration of how computer vision can be used for interactive applications.
