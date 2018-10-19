Install Opencv module & Numpy

pip install opencv-python

pip install numpy


Capture the video

      cap=cv2.VideoCapture(0)

If video not capture may be your camera not working will show the error .

To write the video in your local directory use VideoWriter 
      
      out=cv2.VideoWriter('myvideo.avi',cv2.VideoWriter_fourcc('M','J','P','G'),10,(640,480))

Captuer the video 

Now your video will save into your local directory . (Check it) . 
