# human_segmentation_clone

Image Segmentation
Extract human from image & Photo manipulation

- U-net을 활용해서 Model 생성
- Preprocess를 통해 Input size를 가공하는 작업 수행 : 사이즈를 input에 맞게 조절하고, 빈 부분을 padding하는 작업
- 예측한 Model을 가지고 Prediction(Inference)을 수행하고, 이를 통해 Mask를 뽑아내는 과정 수행

## Reference

빵형의 개발도상국 참조

- Code: https://github.com/kairess/human_segmentation
- Youtube: https://www.youtube.com/watch?v=zrSp5QuHru4&t=29s
- HumanParsing Dataset: https://github.com/lemondan/HumanParsing-Dataset
  HumanParsing Dataset에서 바이두 클라우드 계정이 필요하여 따로 만들어둔 kaggle Dataset으로 실행
  - Preprocessed Dataset: https://www.kaggle.com/kairess/human-segmentation

## Model Keywords

    CNN
    U-Net Architecture
    Image Segmentation

## Build System

    Windows 10 Home
    Ryzen 9 3900X
    RTX 2070 Super

## Dependancies

    Refer to requirements.txt
    - Python
    - OpenCV
    - numpy
    - Keras
    - matplotlib
