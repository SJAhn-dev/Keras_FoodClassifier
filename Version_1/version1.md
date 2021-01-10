Version1 History

Class Label : 45 Class
Image Count : 1,000 x 45 Class = 45,000
Train/Test : 0.75 / 0.25 ( No validation Data, Test=Validation Data )
-> 데이터 개수가 작아 Test Data를 Validation 데이터로 사용

Image Size : 64 x 64 x 3

Test Accuracy : 0.2350

< 원인 예측 >
Class 개수에 비해 데이터가 너무 적다. 다음 테스트에선
Class 개수를 30개로 줄이고, ImageDataGenerator를 사용하여
Batch 이미지로 Class당 이미지를 3,000개 정도로 조절해볼 예정
