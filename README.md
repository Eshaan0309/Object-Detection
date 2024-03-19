# Object Detection

Object_Detection
[ultralytics==8.0.0]
Features
Object Tracks
Different Color for every track
Video/Image/WebCam/External Camera/IP Stream Supported
Train YOLOv8 on Custom Data
https://chr043416.medium.com/train-yolov8-on-custom-data-6d28cd348262
Steps to run Code
Clone the repository
https://github.com/nitin17082002/Object_Detection.git
Goto cloned folder
cd yolov8-object-tracking
Install the ultralytics package
pip install ultralytics==8.0.0
Do Tracking with mentioned command below
#video file
python yolo\v8\detect\detect_and_trk.py model=yolov8s.pt source="test.mp4" show=True

#imagefile
python yolo\v8\detect\detect_and_trk.py model=yolov8m.pt source="path to image"

#Webcam
python yolo\v8\detect\detect_and_trk.py model=yolov8m.pt source=0 show=True

#External Camera
python yolo\v8\detect\detect_and_trk.py model=yolov8m.pt source=1 show=True
Output file will be created in the working-dir/runs/detect/train with original filename
Results
YOLOv8s Object Tracking	YOLOv8m Object Tracking
	
References
https://github.com/abewley/sort
https://github.com/ultralytics/ultralytics
