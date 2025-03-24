# Object Detection using SSD Model

This project uses the SSD (Single Shot MultiBox Detector) model for object detection on a custom dataset with classes such as car, chair, and lamp post.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [License](#license)

## Introduction
This project implements an object detection system using the SSD model with a custom dataset. The model is trained to detect objects like cars, chairs, and lamp posts in images.

## Dataset
The dataset consists of images and their corresponding annotations (in XML format) for the following classes:
- Car
- Chair
- Lamp Post

The dataset is stored in the `data` folder. If you want to use your own dataset, please refer to the code in `dataset.py` for how to modify it.

## Installation
Clone the repository:
```bash
git clone https://github.com/your-username/object-detection-ssd.git
cd object-detection-ssd
