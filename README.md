# Air_drawing

This is a project that enbles you to draw just by waving your finger in air. I built this air canva using the python library openCV. Here Hand detection and tracking is used to draw the object. An algorithm for the same is also stated afterwords.

You can draw by using your  1st finger , and if you want not to draww the move hand by joing thumb and theb finger.

### Algorithm 
1. Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)
1. Prepare the canvas frame and put the respective ink buttons on it.
1. Adjust the values of teh mediapipe intilization to detect one hand only.
1. Detect teh landmarks by passing the RGB frame to the mediapipe hand detector
1. Detect the landmarks, find the forefinger coordinates and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)
1. Finally draw the points stored in array on the frames and canvas .


### Requirements

Make sure you have following libraries in your environment before running, If not run below command in command window to install all the reuired python libraries.

```bash
  pip install -r requirements.txt
```
    
