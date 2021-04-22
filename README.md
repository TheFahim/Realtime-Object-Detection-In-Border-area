# borderdefense

There are two different algorithms where we trained tested the raw dataset. for limited amount of hardware resourses transfer based learning used where I downloaded pre-trained network layers tranied the raw datasets according to them and finally found discision layer. My project was to find out which algorithm works better in a real-time situation. 

there are Two algorithm here to run 

# Single Shot Multibox detector (SSD)

run the demo
for image file
```
python image.py 
```
and for video file
```
python video.py
```

# You only look once (YOLO)

run the demo video
```
python detect_video.py --weights ./checkpoints/yolov4-416 --size 416 --model yolov4 --video ./data/video/videobsf.mp4 --output ./detections/results.avi
```

run image
```
python detect.py --weights ./checkpoints/custom-416 --size 416 --model yolov4 --images ./data/images/car.jpg
```

# Reuslt 
in the end YOLO came up with more detections but less accuracy and SSD came up with less detections and more accuray

**YOLO detection**
![detection1](https://user-images.githubusercontent.com/36739976/115660938-86473900-a35e-11eb-8f46-23abb6b2ec05.png)

**SSD detection**
![image](https://user-images.githubusercontent.com/36739976/115661345-21d8a980-a35f-11eb-997b-5b31b5e32dd2.png)


# Requirements 

You must have a decent gpu to have fair amout of real-time output in these systems. there are a few pre-required depecdencies that must have on your system such as

- numpy
- imagecv
- tensorflow
- tensorflow onject detection API
- lxml
- tdqm
- absl-py
- matplotlib
- pillow

to install tensorflow object-detection API please fllow the link [here](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html)
