# Hand_Tracking
Hand tracking through CV2 framework and MediaPipe libray to adjust your volume in your pc.

![mediapipeimg](hand.gif)

## For Developers
* MediaPipe Library
**Hand Landmark Model**
After the palm detection over the whole image the subsequent hand landmark model performs precise keypoint
localization of 21 3D hand-knuckle coordinates inside the detected hand regions via regression, that is direct coordinate prediction.
The model learns a consistent internal hand pose representation and is robust even to partially visible hands and self-occlusions.
For accuracy model used 30,000 real-world images with 21 3D coordinates, as shown below.
![img](https://google.github.io/mediapipe/images/mobile/hand_landmarks.png)

## For Users
* You will need an active camera connected to pc or a webcam.
* Ideal to run this program in PyCharm
* Note: Users will need Python 3.9 to 3.7 as MediaPipe does not support 
