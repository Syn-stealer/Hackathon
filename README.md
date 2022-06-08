

# 🎬 Syn-stealer Hackathon Project

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
합성데이터가 모델 학습과 성능에 어떤 영향을 끼치는지 알아보기 위해<br>
Object Detection 모델 중 대표적인 세 가지 모델인 YOLOv5, RetinaNet, EfficientDet을 사용하여 <br>실제 데이터와 합성 데이터의 여러 조합을 학습시키고 모델별, 데이터셋 별 검출 성능을 비교



### 🔹 데이터셋
- [KITTI](http://www.cvlibs.net/datasets/kitti/)
- [VKITTI2](https://europe.naverlabs.com/research/computer-vision/proxy-virtual-worlds-vkitti-2/)
- [AI Hub 자율주행 Dataset](https://aihub.or.kr/aidata/8007)

<br>

## ✔︎ 진행 과정
추후 추가 예정

<br><br>
## 📃 References
|제목|분류|비고|
|:--|:--:|--|
|[Training Deep Networks with Synthetic Data](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/3a5f1dc2-4ac7-4ab8-ac30-2a0e3673ede7/Training_Deep_Networks_with_Synthetic_Data.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220502%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220502T023835Z&X-Amz-Expires=86400&X-Amz-Signature=931102fc38d0be955c1c82015141f794bbeb6182d8da8c0beb288d51822a38c5&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Training%2520Deep%2520Networks%2520with%2520Synthetic%2520Data.pdf%22&x-id=GetObject)|논문||
|[자율주행 차량의 학습 데이터 자동 생성 시스템 개발](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/d05d19ec-9059-478b-b494-21b7dfc1a8f4/MoraiSim.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220502%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220502T024007Z&X-Amz-Expires=86400&X-Amz-Signature=8dff1fadb2049a797743040bbcba52d9c41389700b8d6d089ed6af1a8000c8e2&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22MoraiSim.pdf%22&x-id=GetObject)|논문||
|[Realistic Blur Synthesis for Learning Image Deblurring](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/a1fa4ac3-3053-4f70-9644-9109d2ac596a/Realistic_Blur_Synthesis_for_Learning_Image_Deblurring.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220502%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220502T024047Z&X-Amz-Expires=86400&X-Amz-Signature=b17b4e44dbba6ecdd052db8b82e68d97bb86efd9140875a79752df931fd06903&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Realistic%2520Blur%2520Synthesis%2520for%2520Learning%2520Image%2520Deblurring.pdf%22&x-id=GetObject)|논문||
|[Stereo R-CNN based 3D Object Detection for Autonomous Driving](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/a69707ab-d159-420b-8775-94884805b58f/Stereo_R-CNN_based_3D_Object_Detection_for_Autonomous_Driving.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220502%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220502T024124Z&X-Amz-Expires=86400&X-Amz-Signature=b1eab9761497a0c3ae9523ffaa0d4d606c9055a18abef043339269e4d21c047d&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Stereo%2520R-CNN%2520based%25203D%2520Object%2520Detection%2520for%2520Autonomous%2520Driving.pdf%22&x-id=GetObject)|논문||
|[S2R-DepthNet: Learning a Generalizable Depth-specific Structural Representation](https://arxiv.org/pdf/2104.00877v2.pdf)|논문||
