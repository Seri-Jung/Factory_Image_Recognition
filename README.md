# Factory_Image_Recognition

1. 데이터 수집
    - 제조업 공장 사람들의 안전모 착용 여부 데이터 수집
    - 구글 이미지에서 50개의 데이터 수집
  
2. 이미지 라벨링
  - [링크](https://github.com/tzutalin/labelImg#labelimg)의 코드를 다운로드 후, 데이터 라벨링 실행
    - 라벨링: 
          0. 배경, 
          1. 헬멧 착용한 사람, 
          2. 헬멧 미착용한 사람
  ![image](https://user-images.githubusercontent.com/69622147/177708249-c4d94b0a-66e5-4e85-9d50-a5475fbda924.png)

3. 데이터 이미지 학습 및 테스트
    - 모델: FasterRCNN
  
