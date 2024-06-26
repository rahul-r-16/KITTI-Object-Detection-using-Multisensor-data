# KITTI Object Detection using Multisensor

This project demonstrates object detection using multisensor data (LiDAR and camera) from the KITTI dataset. The project leverages data from the KITTI Vision Benchmark Suite and uses machine learning techniques to detect objects in the environment.

##Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [License](#license)

## Introduction

The KITTI Object Detection using Multisensor project aims to perform object detection using data from multiple sensors, specifically LiDAR and cameras. This approach provides more robust and accurate detection by combining the strengths of different sensor modalities.

## Dataset

The project uses the KITTI dataset, which provides raw data from a variety of sensors mounted on a moving platform. You can download the dataset from the following link:

[Download KITTI Calibration Data](https://s3.eu-central-1.amazonaws.com/avg-kitti/raw_data/2011_10_03_calib.zip)

## Features

- Utilizes both LiDAR and camera data for object detection.
- Implements state-of-the-art machine learning models for detection.
- Provides visualization of detection results.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- TensorFlow or PyTorch (depending on the model used)
- Matplotlib
- pykitti (for loading KITTI dataset)

## Installation

1. Clone the repository
2. Install the required packages

## Usage

**1. Download and extract the KITTI dataset**: Download the dataset from the provided link and extract it into a directory.

**2. Run the Jupyter Notebook:** The main implementation is in the Jupyter Notebook `kitti_object_detection_lidar.ipynb`.

**3. Load the dataset:** Modify the dataset path in the notebook to point to the location where you extracted the KITTI dataset.

**4. Train and evaluate the model:** Follow the steps in the notebook to train and evaluate the object detection model.

