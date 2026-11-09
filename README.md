# CODEPLANT · AI 이미지 처리 실습

인공지능 기초와 컴퓨터 비전 강의의 실습 노트북입니다. 배지를 누르면 Google Colab에서 바로 열립니다.
설치할 것은 없고, Google 계정과 인터넷만 있으면 됩니다.

| 순서 | 실습 | 내용 | 열기 |
|---|---|---|---|
| 1 | MNIST와 CNN 분류 | 손글씨 숫자로 CNN 학습 · 오답/혼동 행렬/특징 맵 분석 · 한 가지만 바꾸는 실험 · 내 손글씨 예측 | [![Colab에서 열기](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kimhaneul050126-cmyk/codeplant-ai-vision-lab/blob/main/01_MNIST_CNN_실습.ipynb) |
| 2 | YOLO 객체 탐지 | 사진 속 물체의 종류·위치·점수 읽기 · 기준 점수 바꾸기 · 탐지 결과를 RC카 명령(w/x)으로 · 화면 신호등 | [![Colab에서 열기](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kimhaneul050126-cmyk/codeplant-ai-vision-lab/blob/main/02_YOLO_객체탐지_실습.ipynb) |

## 사용 방법
1. 위 표의 **Open in Colab** 배지를 누릅니다.
2. 상단의 **Drive에 사본 저장**을 눌러 내 사본으로 작업합니다. (원본은 바뀌지 않습니다)
3. 위에서부터 셀을 차례로 실행합니다 (`Shift + Enter`).

## 참고
- MNIST 실습의 실험 구성은 [Hwk040319/MJY-ML](https://github.com/Hwk040319/MJY-ML)의 `02_cnn_theory_mnist.ipynb`를 참고해 Keras로 옮겼습니다.
- YOLO 실습은 [Ultralytics](https://docs.ultralytics.com) 패키지와 COCO로 사전 학습된 모델을 사용합니다.
