# Face mask detection and classification

## General information
This repository contains four facemask-oriented Jupyter Notebooks. Run them in Google Colaboratory environment. You need to create a Kaggle account to download datasets (you have to get an API token and place it in *Kaggle* directory in Google Drive). Two notebooks contain code for downloading datasets, the other two enable training and validating networks.

### Convolutional Neural Network
Notebooks whose names begin with *CNN* allow you to perform image classification. Images (RGB 64x64) with human faces are inputs to the network, which classifies them into two classes - with and without a mask. 

### YOLOv5
Notebooks whose names begin with *YOLOv5* allow you to perform object detection with classification. Images with human faces are inputs to the network, which detects faces and classifies them into three classes - with, without a mask and with a mask worn incorrectly. 

### Credits
The notebooks were inspired by [TowardsDataScience](https://towardsdatascience.com/face-mask-detection-using-yolov5-3734ca0d60d8), [this](https://www.kaggle.com/apulkit674/face-mask-detection-cnn) and [this](https://www.kaggle.com/issaouisafa/yolov5-facemask-2021) dataset-related notebooks.

### Author
* **Emilia Szymańska**
