# AI-Virtual-Painter
An application that enables one to virtually paint in the air using their fingers. It is developed in python using Open Cv and MediaPipe

- OpenCV (for image processing and drawing)
- Mediapipe (for Hand Tracking)

## Prerequisites:
- You should install python version 3.7 or more
- Import all modules required for the project using this command
```
pip install <module name>
```

## Features :
* Can draw on your System screen based on your Index finger movement
* Can track your hand in real-time

### Working :
* This project is a use case of Hand Tracking technology. 
* As soon as the user shows up his hand in the camera the application detects it & draws a bounding box around the hand.
* If User shows only Index Finger than he/she is in drawing mode.
* To Select different color or eraser from the top of Canvas, User must select it by taking his both Index and Middle finger together at the top of icon.
 
 ![Ai-Virtual-Painter_f](https://user-images.githubusercontent.com/78357575/123515066-b808b300-d6b3-11eb-8082-97a67f5493c9.jpg)

