# Gesture-Recognition-using-YoloV3


Clone the Yolo repo from https://github.com/AlexeyAB/darknet and replace the make file with the one in this repo and then install it

Upload the config file obj.data and obj.names to the cfg folder and also replace the yolo-voc.2.0.cfg with the file in this repo.

To create the train.txt and test.txt file , use the train_text.py , assigning the percentage (test%), remaining of which will be used for training.

Upload the train.txt and test.txt in the darknet folder.

To train, download the pretrained weights from https://pjreddie.com/darknet/yolo/ and use the following command

!./darknet detector train cfg/obj.data cfg/yolo-voc.2.0.cfg darknet19_448.conv.23 -dont_show 0

Weights are saved in the backup folder every 100 iterations


