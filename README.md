# DL-Pilot-Project

# 포트폴리오 프로젝트 모음

이 저장소에는 다양한 YOLO 신경망 활용 파일럿 프로젝트가 포함되어 있습니다. 각 프로젝트는 실시간 객체 탐지, 추적, 분석 등을 목표로 합니다.

---

## 프로젝트 목록

### 1. 유동인구 카운트 YOLO 영상 파일럿 프로젝트
- **프로젝트 설명**: YOLO 모델을 사용하여 영상 속 유동인구를 실시간으로 감지하고, 입장 및 퇴장 수를 카운트하는 시스템.
- **주요 기능**: 사람 객체 탐지, 입장 및 퇴장 카운팅, 누적 인원 계산.
- **관련 주피터 노트북**:
  - [구글 코랩 주피터 노트북](https://colab.research.google.com/drive/1RBH0rg7P-2Zty5SsS6-5Spmb1fbjbHXw?usp=sharing)
- **관련 링크**:
  - [YOLO 모델 다운로드](https://github.com/ultralytics/yolov5)
  - [OpenCV 공식 문서](https://docs.opencv.org/)
- **시연 이미지**:  
  ![유동인구 카운트 이미지](https://github.com/maango97/DL-Pilot-Project/blob/main/people.png)

---

### 2. 폐결절 탐지 파일럿 프로젝트
- **프로젝트 설명**: YOLO 모델을 사용하여 영상 속 유동인구를 실시간으로 감지하고, 입장 및 퇴장 수를 카운트하는 시스템.
- **주요 기능**: 폐결절 자동 탐지.
- **관련 주피터 노트북**:
  - [구글 코랩 주피터 노트북](https://colab.research.google.com/drive/1RBH0rg7P-2Zty5SsS6-5Spmb1fbjbHXw?usp=sharing)
- **관련 링크**:
  - [YOLO 모델 다운로드](https://github.com/ultralytics/yolov5)
  - [OpenCV 공식 문서](https://docs.opencv.org/)
- **시연 이미지**:  
  ![폐결절 탐지 이미지](https://github.com/maango97/DL-Pilot-Project/blob/main/lung.png))

---

## 설치 및 실행 방법

1. 필요한 라이브러리 설치:
   ```bash
   pip install opencv-python-headless ultralytics numpy
