## Safety Helmet Object Detection 🏗⚠⛑

### 건설현장의 안전모 미착용으로 인한 사고 발생율을 줄이기 위해 안전모를 인식하는 모델 개발.

---

### Models  
- Yolov3, Yolov4, Yolov5

### Data
- [Kaggle dataset](https://www.kaggle.com/datasets/vodan37/yolo-helmethead)
- 22789장의 이미지와 라벨

### Envs and Requirements
- Colab, Python, Pytorch, OpenCV

### Progress
- 데이터셋 확인
- 모델에 맞게 Config 작성
- 모델 학습 및 결과 확인

### Retrospective
- 이미지 처리하는 전처리 과정이 다소 부족한 것이 아쉬움. 추후에 이미지 증강을 통해 성능을 더 향상시킬 것.
- 한번 학습하고 성능을 확인하는데 시간이 오래 걸리기 때문에, 관련된 자료들을 서치하고 참고하여 시도할 것들을 리스트업하고 제한된 시간내에 성능확인을 할 수 있도록 체계적인 워크플로우가 필요함을 느낌.

### References
- https://opencv.org/
- https://github.com/AlexeyAB/darknet
- https://github.com/ultralytics/yolov3
- https://github.com/ultralytics/yolov5

