# People Counting

## Overview

The **People Counting** project is designed to count the number of people in a given area using a deep learning model. This solution can be applied in various real-world scenarios such as monitoring the number of visitors in a store, maintaining social distancing in crowded places, or managing occupancy in restricted areas.

This project uses **[YOLOv8](https://github.com/ultralytics/yolov8)** for object detection and **OpenCV** for image processing. The model detects people in real-time using a camera feed and keeps track of the count.

---

## Features

- Real-time people detection.
- Accurate counting using object detection.
- Can be deployed on various platforms such as Jetson Nano, Raspberry Pi, or cloud environments.
- Customizable model based on your environment and needs.

---
   
## Prerequisites

Before you start, ensure you have the following tools installed:

- Docker
- Docker Hub account (for pulling and pushing images)
- Python 3.6+ (for local development)
- OpenCV, PyTorch (for local development, if not using the Docker image)
  
---

## How to Run the Project Using Docker

### 1. Pull the Docker Image

To use the pre-built Docker image, run the following command:

```sh
docker pull lingeswaran2018/people-counting:linga
```

### 2. Run the Docker Container

Once the image is pulled, you can start a container using the following command:

```sh
docker run -it --rm lingeswaran2018/people-counting:linga
```

This will start the application and begin counting people from your webcam or video stream.

---

## 3. How to Run the Project Locally

### Clone the Repository

```sh
git clone https://github.com/lingeswaran2018/Edge_AI_people_counting.git
```



