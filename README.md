# Driver-Drowsiness
It provides an alert alarm and an alert message when the driver falls asleep. 

Dependencies :
  - OpenCV
  - Mediapipe
  - Scipy
  - Playsound
  - Pyttsx3

Usage
- Run the `drowsiness.py` script
- Ensure that your webcam is connected and positioned correctly to capture your face.
- The application will display a live video feed with facial landmarks drawn on the screen.
- If the system detects drowsiness based on the aspect ratio of your eyes, it will trigger an alert sound and a spoken warning message.
- Press 'q' to exit the application.

Features :

- Real-time drowsiness detection using facial landmarks.
- Customizable detection parameters to adjust sensitivity.
- Audio and visual alerts to warn the driver.
- Lightweight and easy to integrate with existing systems.

Acknowledgments :

  Special thanks to the contributors of OpenCV, Mediapipe, and other libraries used in this project.
  This project is inspired by the need for improved road safety measures.
  We appreciate feedback and contributions from the open-source community to make this project better.
