# YOLOv8-Object-Detection-in-Video
This repository demonstrates how to use YOLOv8 for object detection in video using Python within an Anaconda environment.<br>
  The project leverages the Ultralytics YOLOv8 model to detect objects frame-by-frame in a video.
# Features
Detect objects in video files using the YOLOv8 model.<br>
Visualize detected objects with bounding boxes and class labels.
# Requirements
Before running the code, ensure you have Anaconda installed on your system.<br>
Install Anaconda: If you don't have it yet, you can download and install Anaconda from [here](https://docs.anaconda.com/anaconda/install/windows/). <br>
Create a new Anaconda environment for the project using anaconda prompt(Administrator mode):<br>
`conda create -n yolov8-env python=3.8`<br>
Activate the environment:<br>
`conda activate yolov8-env`<br>
Install the required dependencies:<br>
`Conda install pytorch torchvision torchaudio cpuonly –c pytorch`
#YOLOv8 Installation
Make sure you have the latest version of YOLOv8 from Ultralytics.<br>
`pip install ultralytics`
#Running the Code in anaconda prompt.
`Yolo task=detect mode=predict model=yolov8n.pt source =“path”`<br>
,change path to your video or image path.




