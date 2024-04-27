<h1 align="center"> 🛰 Drone-Object Detection 🕹️📡 </h1>
<div align= "center"><img src="https://github.com/Suryachoudhuri003/DroneObjectDetection/blob/main/Default_Drone_Object_Detection_software_detecting_object_in_e_0.jpg" width="600" height="500"/>
</div>
## :innocent: Purpose
The purpose of this project is to develop a system that can detect and track objects from a drone. This system can be used for a variety of purposes, such as:

- Surveillance: The system can be used to monitor a specific area for objects of interest. For example, the system could be used to monitor a construction site for unauthorized personnel.
- Search and rescue: The system can be used to search for missing persons or objects. For example, the system could be used to search for survivors of a natural disaster.
- Delivery: The system can be used to deliver objects to specific locations. For example, the system could be used to deliver medical supplies to a remote location.
- Mapping: The system can be used to map an area and identify objects of interest. For example, the system could be used to map a forest for endangered species.

## PPT and Project Report free support provided ...
If interested, contact me at suryachoudhuri03@gmail.com

## :warning: TechStack/framework used
The project is built using the following technologies:
- Python
- OpenCV
- TensorFlow
- DJI Tello SDK

## :star: Features and Working

The project has the following features:

- Object detection: The project can detect a variety of objects, including people, cars, and animals.
- Object tracking: The project can track the movement of objects over time.
- Drone control: The project can control the drone to follow or avoid objects.

## :star: Working

1. The project works by first capturing images of the environment using the drone's camera. The computer vision algorithm then processes these images to detect     objects. The algorithm identifies objects by comparing the images to a database of known objects. Once an object is detected, the algorithm tracks its movement and updates its position in the database. The drone can then be controlled to follow the object or to avoid it.

2. The main.py file contains the code for the project. The code first imports the necessary libraries, including OpenCV, TensorFlow, and the DJI Tello SDK. It then loads the COCO dataset, which is a large dataset of images that have been labeled with object annotations. The code then creates a computer vision algorithm that can detect objects in images. The algorithm is trained on the COCO dataset.

3. The code then connects to the drone and starts streaming video from the drone's camera. The code then loops forever, detecting objects in the video stream and tracking their movement. The code also controls the drone to follow or avoid objects.

## :file_folder: Dataset

The project uses the COCO dataset for object detection. The COCO dataset is a large dataset of images that have been labeled with object annotations. This dataset is used to train the computer vision algorithm.

## :key: Prerequisites
All the dependencies and required libraries are included in the file <code>requirements.txt</code> [See here](https://github.com/Suryachoudhuri003/DroneObjectDetection/blob/main/requirements.txt)

- Put the following command :
```
$ pip install -r requirements.txt
```

## :heart: Owner
Made by [Surya Choudhuri](https://github.com/Suryachoudhuri003)

## :eyes: License
GNU General Public License © [Surya Choudhuri](https://github.com/Suryachoudhuri003/DroneObjectDetection/blob/main/LICENSE)
