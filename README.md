# Object-Detection-Using-YOLO-Algorithm

YOLO (You Only Look Once) is an extremely powerful and fast algorithm for object detection.
It is crucial to have a solid understanding of the algorithm beforehand.

References:

1. https://pjreddie.com/media/files/papers/YOLOv3.pdf


Before we begin coding, we need to download some essential YOLO files.

The three files that need to be downloaded are as follows:

1. coco.names
2. yolov3.cfg
3. yolov3.weights

highway.mp4 and main_road.mp4 are used to test highway detection.

The yolo.py is the code to detect the objects in the images.

Ensure that you have numpy and OpenCV installed. If not, you can install them using the following commands:

!pip install numpy
!pip install opencv-python

To run the file, open your command prompt and execute the following command, replacing "images/ipl.jpeg" with the path to your desired image:

python yolo.py --image images/ipl.jpeg

