# 모바일 환경 자전거 도로 이상 탐지 모델
## 해당 프로젝트는 모바일 환경에서 자전거가 도로의 결함이나 장애물등의 위험 요소를 탐지 할 수 있게 경량화 한 모델의 개발을 목적으로 하였습니다.

# 사용 라이브러리
## ultralytics의 yolo11을 기반으로 해당 라이브러리에서 제공하는 모듈을 통해서 yalm 파일을 수정, yolo 구조를 경량화 하였습니다.
## ghost convolution을 기반으로 모델을 재구성 하였습니다.
<img width="845" height="624" alt="KakaoTalk_20250915_010545923" src="https://github.com/user-attachments/assets/e3b37f87-35e6-4784-81b1-d44d29891a87" />

# 코드 설명
## 모델 학습 코드는 custom_yolo.ipynb, 모델 실행 코드는 detect.ipynb 입니다
