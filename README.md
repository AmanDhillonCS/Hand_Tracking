# Hand_Tracking
Hand tracking through cv2 framework to adjust your volume in your pc.
![mediapipeimg](https://google.github.io/mediapipe/images/mobile/hand_tracking_3d_android_gpu.gif)

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
