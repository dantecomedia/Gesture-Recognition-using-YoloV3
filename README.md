# Gesture-Recognition-using-YoloV3


Clone the Yolo repo from https://github.com/AlexeyAB/darknet and replace the make file with the one in this repo and then install it

Upload the config file obj.data and obj.names to the cfg folder and also replace the yolo-voc.2.0.cfg with the file in this repo.

To create the train.txt and test.txt file , use the train_text.py , assigning the percentage (test%), remaining of which will be used for training.

Upload the train.txt and test.txt in the darknet folder.

To train, download the pretrained weights from https://pjreddie.com/darknet/yolo/ and use the following command

!./darknet detector train cfg/obj.data cfg/yolo-voc.2.0.cfg darknet19_448.conv.23 -dont_show 0

Weights are saved in the backup folder every 100 iterations

Dataset :
https://drive.google.com/drive/u/0/folders/1oI5rVdzMSCgbnbBv8HsM0XUH67K2iR7Z

Gesture_4.zip has 4 classes with annotations
images.zip has 9 classes with annotations
Weight https://drive.google.com/file/d/1R1ChuSU_0x5C5OImzYmxx7BZEQpAeVib/view?usp=sharing

Accuracy : 99.95%
Region Average IOU : 86% 



![alt text](https://github.com/dantecomedia/Gesture-Recognition-using-YoloV3/blob/master/cap4.png)

![alt text](https://github.com/dantecomedia/Gesture-Recognition-using-YoloV3/blob/master/cap2.png)

![alt text](https://github.com/dantecomedia/Gesture-Recognition-using-YoloV3/blob/master/cap3.png)

![alt text](https://github.com/dantecomedia/Gesture-Recognition-using-YoloV3/blob/master/cap.png)

![alt text](https://github.com/dantecomedia/Gesture-Recognition-using-YoloV3/blob/master/cap5.png)

