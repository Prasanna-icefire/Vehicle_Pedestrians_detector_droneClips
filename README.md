# Vehicle_Pedestrians_detector_droneClips
I have successfully trained custom weights to detect pedestrians/Cars/Busses/motors...etc from drone video clips!

![](https://raw.githubusercontent.com/Prasanna-icefire/Vehicle_Pedestrians_detector_droneClips/master/darknet/predictions.jpg)


Go ahead and download the weights I have trained from:
https://www.dropbox.com/s/ashde9hjwfefm4i/yolo-obj_best.weights?dl=0

Paste these weights into the backup folder under darknet

After this make open the darknet_video.py and set the input video path.....Make sure it is a drone footage.
See the results and enjoy.

You might want to first make the darknet folder. Make the necessary changes in the make file,and execute make


For the dataset I used VisDrone's Data to train the model.


https://www.dropbox.com/s/w0t148ig7us67es/res.avi?dl=0
The above link is the result of how detections are haooening in videos
