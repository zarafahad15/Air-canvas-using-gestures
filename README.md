Air Canvas using Hand Gestures

Overview

Air Canvas is a computer vision–based project that allows users to draw in the air using hand gestures. It uses a webcam to detect hand movements and maps different gestures to drawing actions such as drawing, color selection, erasing, and clearing the canvas. The project is built using Python, OpenCV, and MediaPipe.

⸻

Features
	•	Draw using index finger movement
	•	Stop drawing using two-finger gesture
	•	Erase using fist gesture
	•	Select colors using on-screen buttons
	•	Clear the canvas using gesture
	•	Save drawing as an image file
	•	Real-time hand tracking

⸻

Technologies Used
	•	Python
	•	OpenCV
	•	MediaPipe
	•	NumPy

⸻

Requirements

Install the required Python libraries using pip:

pip install opencv-python mediapipe numpy


⸻

How to Run the Project
	1.	Connect a webcam to your system.
	2.	Save the Python code as air_canvas.py.
	3.	Open a terminal in the project folder.
	4.	Run the program:

python air_canvas.py


⸻

Controls and Gestures

Gesture	Action
Index finger up	Draw
Index + middle finger up	Selection mode
Fist (no fingers up)	Eraser
Finger touching top bar	Color selection / Clear
Press S key	Save drawing
Press Q key	Quit application


⸻

Project Working

The webcam captures live video frames. MediaPipe detects hand landmarks and identifies finger positions. Based on the number of fingers raised, the system switches between drawing mode, selection mode, and eraser mode. Drawing is done on a virtual canvas which is merged with the live video feed.

⸻

Output
	•	Real-time drawing on screen
	•	Saved images stored as PNG files in the project directory

⸻

Applications
	•	Touch-free drawing
	•	Interactive learning tools
	•	Gesture-based user interfaces
	•	Computer vision mini projects

⸻

Future Enhancements
	•	Add more colors and brush sizes
	•	Improve gesture accuracy
	•	Multi-hand support
	•	Voice control integration
