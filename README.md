# YOLO Object Detection 

## 개요
YOLOv8n과 YOLO26n을 활용하여 모델을 학습하고 두 모델의 성능을 비교하였습니다. 또한 학습된 모델을 활용한 객체 탐지 결과 영상을 제작하여 업로드하였습니다.

## 학습 환경
- Google Colab (GPU)
- Ultralytics YOLO
- Epoch: 50
- Image Size: 640×640
- Batch Size: 16

## 학습 모델
- YOLOv8n
- YOLO26n

## 프로젝트 파일
- `models/`: 학습 완료된 모델 가중치
- `videos/`: 객체 탐지 결과 영상
- `notebook/`: 학습 코드
- `results/`: 학습 결과 그래프

## 실험 결과
두 모델 모두 객체 탐지 성능이 향상되는 모습을 보였으며, YOLO26n은 YOLOv8n보다 Recall 및 mAP 지표에서 높은 성능을 기록하였습니다.
