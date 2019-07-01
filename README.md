# Detect-video-by-SSD
the main code is from https://github.com/balancap/SSD-Tensorflow, environment requirement is the same. &  I change some code  to detect video

in SSD-Tensorflow/notebook we add three new. py file called ssd_camera.py,visualization.py ,visualization_camera.py  as as shown above; Comparing to complex structure of the code, what you need to edit is only ssd_camera.py, you can understand it easily.

I get some idea from a CSDN bolg, but I can't use cv2.videoCapture in my computer. So I change to use imageio to get the singele image from video.

Of course the color is a little bit strange because of "RGB" or "BGR", and add a tracker can make it effect better, I will add it later;


