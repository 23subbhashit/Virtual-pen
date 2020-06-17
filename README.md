# Virtual-pen
This repository is based in creating a virtual pen using Opencv.
Procedure:
* Find the HSV range for your color using tracker.py.HSV stands for Hue-Saturation-Value. It is actually a type of color plane representation (like RGB, YCbCr etc.). It is a device independent color representation format: The HSV color representation is useful to detect specific color types, e.g.: skin color, fire color etc.
* After finding your hsv value,press the s key to save that as .npy file(penrange.npy)
* Using that .npy file we can can write anything virtually using draw.py.
* Press c to clear everything in the frame and canvas.


![ezgif com-video-to-gif](https://user-images.githubusercontent.com/43717493/84901912-b8966300-b0c9-11ea-8a5f-27efa48b1d99.gif)
