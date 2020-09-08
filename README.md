# Face Detection using Yolov5

Dataset used: [Widerface](http://shuoyang1213.me/WIDERFACE/)

Processed data ready in Yolov5 format is made public and uploaded to my Kaggle profile

Dataset Link: https://www.kaggle.com/rocky03/wider-face-in-yolov5-format

# Train the program

Change the paths to the images in `face.yaml`

Run using the command,

`python train.py --img [image size] --batch [batch size] --epochs [epochs] --data face.yaml --cfg models/[model_file]`


