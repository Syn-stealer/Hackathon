# yolov5 1차 자료

```bash
# YOLOv5 모델 가져오기
$ git clone https://github.com/ultralytics/yolov5.git
```

```bash
# KITTI 전체 데이터 학습 (YOLOv5s 모델)
$ python [train.py](http://train.py/) --img 640 --batch 16 --epochs 300 --data kitti.yaml --weights [yolov5s.pt](http://yolov5s.pt/)
```

라벨 1

![val_batch0_labels.jpg](yolov5%201%E1%84%8E%E1%85%A1%20%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%202f7680bae68e4491ad21a9e17845db4f/val_batch0_labels.jpg)

val pred 1

![val_batch0_pred.jpg](yolov5%201%E1%84%8E%E1%85%A1%20%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%202f7680bae68e4491ad21a9e17845db4f/val_batch0_pred.jpg)

라벨 2

![val_batch1_labels.jpg](yolov5%201%E1%84%8E%E1%85%A1%20%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%202f7680bae68e4491ad21a9e17845db4f/val_batch1_labels.jpg)

val pred 2

![val_batch1_pred.jpg](yolov5%201%E1%84%8E%E1%85%A1%20%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%202f7680bae68e4491ad21a9e17845db4f/val_batch1_pred.jpg)

label 3

![val_batch2_labels.jpg](yolov5%201%E1%84%8E%E1%85%A1%20%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%202f7680bae68e4491ad21a9e17845db4f/val_batch2_labels.jpg)

val pred 3

![val_batch2_pred.jpg](yolov5%201%E1%84%8E%E1%85%A1%20%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%202f7680bae68e4491ad21a9e17845db4f/val_batch2_pred.jpg)

![labels.jpg](yolov5%201%E1%84%8E%E1%85%A1%20%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%202f7680bae68e4491ad21a9e17845db4f/labels.jpg)

![confusion_matrix.png](yolov5%201%E1%84%8E%E1%85%A1%20%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%202f7680bae68e4491ad21a9e17845db4f/confusion_matrix.png)