# mask-detection

This project is provided as a requirement of a weekly project for the bootcamp BD and AI from Coding dojo and SDA.

## Motivation:

The issue of wearing face coverings in public comes up frequently these days. In public areas of significant community-based transmission, social distancing measures are difficult to maintain. Wearing the masks can be used for either protection of healthy persons or to prevent onward transmission or both. There are a lot of technical interventions that help detect whether people are wearing masks or not. Here we use the deep learning model to detect the wearing of masks in public places.

## The structure of the project:


### Finding a dataset : 
 this project done using this[] https://www.kaggle.com/datasets/andrewmvd/face-mask-detection  dataset from Kaggel 

### Preprocessing : 
To shorten the time,  using the preprocessing from this notebook https://www.kaggle.com/code/rohitgadhwar/face-mask-detection-yolov5


### Model training : 
Yolov7 (You Only Look Once version 7) is a real-time object detector currently revolutionizing the computer vision industry with its incredible features. The official YOLOv7 provides unbelievable speed and accuracy compared to its previous versions. YOLOv7 weights are trained from scratch using the COCO dataset. The model can perform real-time object detection for images and videos. It can be utilized directly or through a fine-tuning process. The training was with 2 batches and 50 epochs. 
Note: the size of the model is greater than 100MB, so this is the the link of it on google drive:
https://drive.google.com/file/d/1R8bgHduTuOtIN2jWhX5C-q8J2QHFoqx4/view?usp=sharing
