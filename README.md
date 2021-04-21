# borderdefense

There are two different algorithms where we trained tested the raw dataset. for limited amount of hardware resourses transfer based learning used where I downloaded pre-trained network layers tranied the raw datasets according to them and finally found discision layer. My project was to find out which algorithm works better in a real-time situation. 

there are Two algorithm here to run 

# Single Shot Multibox detector

run the demo
for image file
> python image.py 

and for video file
> python video.py


# You only look once

run the demo video

>python detect_video.py --weights ./checkpoints/yolov4-416 --size 416 --model yolov4 --video ./data/video/videobsf.mp4 --output ./detections/results.avi
