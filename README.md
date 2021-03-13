### Object-Localization

A Object Localiztion pipeline based using YOLOv5 as the base model.

![alt text](https://github.com/jaydulera/Object-Localization/blob/main/Performance/test_batch0_pred.jpg "Results")

### Algorithm Used:

- YOLOv5

YOLO is an acronym for “You Only Look Once”, it is considered the first choice for real-time object detection among many computer vision and machine learning experts and this is simply because of it’s the state-of-the-art real-time object detection algorithm in terms of performance(FPS), ease of use(setting up and configurations) and versatility(models can be coverted to serve different devices).

![alt text](https://github.com/jaydulera/Object-Localization/blob/main/Performance/yolov5Overview.jpg "Model Architecture")

### Training & Prediction

The model was trained on Tesla T4 GPUs (Courtesy of Google Colab) for 100 epochs. After training the model was used for predictions and evaluation on 1.8.0+cu101 CPUs. 
The model was tested on 30 different images, this process took about 2.833s for 30 images with an average of 0.094s per image.

![alt text](https://github.com/jaydulera/Object-Localization/blob/main/Performance/time.JPG "Prediction Time")
