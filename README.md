# DROWSINESS_DETECTION_SYSTEM_FOR_DRIVERS


```markdown
# Drowsiness Detection System

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)

This project implements a drowsiness detection system that uses computer vision and machine learning techniques to monitor a person's eye state and alert them in case of drowsiness.

## Table of Contents

- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
  - [Dataset](#dataset)
  - [Installation](#installation)
- [Usage](#usage)
  - [Data Preparation](#data-preparation)
  - [Model Training](#model-training)
  - [Real-Time Drowsiness Detection](#real-time-drowsiness-detection)
- [Results](#results)


## Project Overview

This project utilizes computer vision libraries like OpenCV and deep learning framework TensorFlow to create a drowsiness detection system. It includes the following main components:

- Data preprocessing and sorting of eye images into "open" and "closed" categories.
- Building and training a custom deep learning model using InceptionV3 architecture.
- Real-time webcam-based drowsiness detection with an alarm trigger.
- Model evaluation and performance analysis.

## Getting Started

### Dataset

Download the drowsiness dataset from [here](http://mrl.cs.vsb.cz/eyedataset) and unzip it using the following command:

```bash
unzip drowsiness_dataset.zip
```

### Installation




```

1. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

### Data Preparation

Organize your dataset by placing open-eye images in the `open_eyes` folder and closed-eye images in the `closed_eyes` folder.

### Model Training

1. Split the dataset into train and test sets:

```bash
python split_data.py
```

2. Train the drowsiness detection model:

```bash
python train_model.py
```

### Real-Time Drowsiness Detection

Run the real-time drowsiness detection:

```bash
python real_time_detection.py
```

## Results

Include a description of the results obtained from your model, including accuracy, precision, recall, and any visualizations.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please feel free to submit a pull request.


