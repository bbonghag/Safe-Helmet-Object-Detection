## Safety Helmet Object Detection 🏗⚠⛑

### 건설현장의 안전모 미착용으로 인한 사고 발생율을 줄이기 위해 안전모를 인식하는 모델 개발.

---
### ⛑Introduction
- 뉴스를 보다가 안전모와 보호장구 미착용으로 인한 사고 발생률이 높다는 기사를 보게됨
- 마침 Object Detection 교육을 듣고 있었고 이걸 관련 기사와 적용시킬수 없을까 고민함
- 불편하다거나 착용하는 걸 까먹었다던가 등의 이유로 안전모를 미착용한다면 이를 파악하고 주의를 주는 시스템을 통해 착용률을 높일 수 있지 않을까란 아이디어가 떠오름
- Object Detection 으로 안전모의 착용 유무를 포착하는 모델을 만들어보고자 이 주제를 선택하였다.

<br/>

### ⛑Materials and Methods
### Data
- [Kaggle dataset](https://www.kaggle.com/datasets/vodan37/yolo-helmethead)
- 총 22789장의 이미지와 라벨
- train_image : 15887장 
- valid_image : 4681장
- test_image : 2261장

### Models  
- Yolov3, Yolov4, Yolov5

<br/>

<!--
### ⛑Progress
- 데이터셋 확인
- 모델에 맞게 Config 작성
- 모델 학습 및 결과 확인 -->


### ⛑Results

<img src="https://user-images.githubusercontent.com/103362361/203070481-9081895e-04ba-4a14-a03c-ef1c41cec49b.png"  width="400" height="300"/>


<br/>

### ⛑Review
- 이미지 처리하는 전처리 과정에서 Augmentation등을 써보지 않음이 아쉬움. 
- 한번 학습하고 성능을 확인하는데 시간이 오래 걸리기 때문에, 관련된 자료들을 서치하고 참고하여 시도할 것들을 리스트업하고 제한된 시간내에 성능확인을 할 수 있도록 체계적인 워크플로우가 필요함을 느낌.
- YOLO 모델이 성능도 준수하면서 처리속도가 빠르기에 실시간으로 쓰이는 모델인만큼, 실시간으로 공사현장에서 CCTV 등과 연계하여 영상을 받아서 안전모 미착용 여부를 파악, 주의/경고 등을 주는 시스템을 사용한다면 사고발생율을 낮출 수 있지 않을까 생각됨
- 또한 안전모뿐 아니라 다른 보호장구까지도 확장 가능성도 존재함


<br/>

### ⛑Envs and Requirements
- Colab, Python, Pytorch, OpenCV


<br/>

### ⛑References
- https://opencv.org/
- https://github.com/AlexeyAB/darknet
- https://github.com/ultralytics/yolov3
- https://github.com/ultralytics/yolov5

