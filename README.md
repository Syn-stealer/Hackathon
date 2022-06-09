

# 🎬 Syn-stealer Aiffelthon Project

**모두의 연구소 AIFFEL**
<br>```본 프로젝트는 기존에 SIM2REAL이라는 기업이 함께 참여하여 제안한 과업 주제로 진행되어야 했으나, 한정된 시간과 기업 측의 협조 등의 문제를 고려하여 연구 주제와 방향을 새롭게 하였음을 미리 알립니다.```
<br>

## 🚦 팀 소개
<img src="https://user-images.githubusercontent.com/96896676/166176230-16a667b6-6d43-47c3-9337-eae2c504a9d9.png" width="500">

🌟 주연은 아니지만 관객들에게 주연처럼 주목을 받는 **신 스틸러(Scene stealer)** 처럼<br>실제 데이터만큼이나 좋은 성능을 보여주어 주목을 받을 수 있는 **합성 데이터(Synthetic data)** 에 관한 연구를 진행하고자 합니다.
<br>
<br>

## 👥 구성원
|직책|이름|역할|
|:--:|:--:|:--:|
|팀장|문덕종|프로젝트 리딩, 논문 서치, 데이터 전처리 및 가공, 모델 리서치 및 학습|
|팀원|권세현|논문 서치, 데이터 수집, 모델 리서치 및 학습|
|팀원|김봉경|논문 서치, 데이터 분석 및 가공, 모델 리서치 및 학습|


<br><br>
## 💻 프로젝트 개요
### 🔹 기간
- 2022.04.25~2022.06.09

### 🔹 내용
```
합성데이터가 모델 학습과 성능에 어떤 영향을 끼치는지 알아보기 위해
Object Detection 모델 중 대표적인 세 가지 모델인 YOLOv5, RetinaNet, EfficientDet을 사용하여
실제 데이터와 합성 데이터의 여러 조합을 학습시키고 모델별, 데이터셋 별 검출 성능을 비교해본다.
```



### 🔹 데이터셋
- [KITTI](http://www.cvlibs.net/datasets/kitti/)
- [VKITTI2](https://europe.naverlabs.com/research/computer-vision/proxy-virtual-worlds-vkitti-2/)
- [AI Hub 자율주행 Dataset](https://aihub.or.kr/aidata/8007)

<br>

## ✔︎ 진행 과정
|순서|내용|기간|
|:--:|:--:|:--:|
|미니프로젝트|논문 서치, Baseline 모델 구현|4/25 ~ 5/3|
|Phase1|거리가 있는 객체 탐지에 대한 성능 향상을 위한 연구|5/4 ~ 5/15|
|Phase2|가려진 객체 탐지에 대한 성능 향상을 위한 연구|5/16 ~ 5/26|
|Phase3|소형 객체 탐지에 대한 성능 향상을 위한 연구|5/27 ~ 6/7|

<br>

## 🌟 최종 결과

[최종결과](https://github.com/Syn-stealer/Hackathon/blob/main/%EC%B5%9C%EC%A2%85%20%EC%97%B0%EA%B5%AC%20(Phase3)/%EC%B5%9C%EC%A2%85%20%EA%B2%B0%EA%B3%BC/Readme.md)

<br><br>
## 📃 References Models
- [YOLOv5](https://github.com/ultralytics/yolov5) <br>
- [RetinaNet](https://keras.io/examples/vision/retinanet/)<br>
- [EfficientDet](https://github.com/google/automl/tree/master/efficientdet)
