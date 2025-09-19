YOLOv8s_CS
This is the official implementation of the YOLOv8s_CS model proposed in our paper，主要用于检测无人机航拍图像中的小目标

Code Structure
yolov8-master/: Based on YOLOv8, integrated with C2f_S module etc


Usage
Clone the repo
Install requirements
Prepare your dataset (format: YOLO)
Train:
python train.py --data your_dataset.yaml --cfg your_model.yaml


