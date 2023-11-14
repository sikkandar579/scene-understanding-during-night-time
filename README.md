# scene-understanding-during-night-time
Computer vision is used for the construction of meaningful description of physical objects from the obtained scenes.
It is of two types day-time vision and night-time vision.
In day-time the objects and its features can be extracted, but as a consequence of very low-light intensity it becomes difficult for the system to detect the objects and its features.
In this work we mainly focus on the night vision system to improve the safety and security of people.
In the videos obtained from IR-cameras, which are of low light intensity, research is more oriented towards enhancement of image, whereas the real challenge lies in object detection.
Due to lack of benchmark datasets at night-time, research pertaining to this field has been superficial.
There are many popular public object datasets such as PASCAL VOC[4,5], ImageNet[6,7], Microsoft COCO[8] and Exclusively Dark (ExDARK), which played a vital role in the object detection and recognition in low light environment.
so we provided our own dataset taken from cctv cameras.
we used yolov1,yolov2,yolov3 and yolov7 for object detection.

software's required:
1) roboflow for annotation
2) google colab

Objects identified in this project:
1) male
2) female
3) car
4) bike
5) bicycle
6) van
