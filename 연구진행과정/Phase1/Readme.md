# yolov5 1차 실험

- 가설 및 목표 : 모델 학습 cycle 한번 돌려보기
- 이미지 인풋 사이즈 : 640
- 배치 사이즈 : 16
- 모델 : YOLOv5s
- 에포크 : 300
- 데이터 종류 : KITTI
- 데이터 개수 : 7481
- 데이터 변형여부 : 없음
- 테스트 데이터셋 : 없음 (그냥 val = train으로 진행후 해당 데이터셋에 예측. 시각화된 bbox를 놓고 정성적으로 판단)
- 결과 : 모델 학습 성공. 그러나 작은 객체 대부분이 DontCare로 탐지되어 DontCare 라벨 제외 필요

```bash
# YOLOv5 모델 가져오기
$ git clone https://github.com/ultralytics/yolov5.git
```

```bash
# KITTI 전체 데이터 학습 (YOLOv5s 모델)
$ python train.py --img 640 --batch 16 --epochs 300 --data kitti.yaml --weights yolov5s.pt
```

라벨 1

![val_batch0_labels.jpg](./yolov5_1/val_batch0_labels.jpg)

val pred 1

![val_batch0_pred.jpg](./yolov5_1/val_batch0_pred.jpg)

라벨 2

![val_batch1_labels.jpg](./yolov5_1/val_batch1_labels.jpg)

val pred 2

![val_batch1_pred.jpg](./yolov5_1/val_batch1_pred.jpg)

label 3

![val_batch2_labels.jpg](./yolov5_1/val_batch2_labels.jpg)

val pred 3

![val_batch2_pred.jpg](./yolov5_1/val_batch2_pred.jpg)

![labels.jpg](./yolov5_1/labels.jpg)

![confusion_matrix.png](./yolov5_1/confusion_matrix.png)
