﻿# yolov3 pytorch linux
# yolov3 for 红细胞， pytorch实现
该项目是来自https://blog.csdn.net/public669/article/details/98020800
#使用方法Linux
下载后

进行训练
python train.py --data-cfg data/rbc.data --cfg cfg/yolov3-tiny.cfg --epochs 10

进行预测
python detect.py --data-cfg data/rbc.data --cfg cfg/yolov3-tiny.cfg --weights weights/best.pt
