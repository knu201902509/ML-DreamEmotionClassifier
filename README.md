기계학습 미니프로젝트 6조 

꿈 텍스트를 활용한 감정분류

4 개의 데이터 파일(원본 데이터셋과, 정제된 train_data.csv, test_data.csv, val_data.csv(validation data) 그리고, 최종 모델 적용까지의 과정이 포함된 원본 코드입니다. 

감정분류에 특화된 DistilBERT 모델을 통해 꿈 텍스트에 긍정/부정 정답레이블(ground_truth)을 데이터셋의 분석을 통해 기준을 정하여 정제(22000개에서 정제를 통해 최종 13000개)를 하였고,
모델의 학습 정확도 향상을 위해 데이터를 60%는 train data로 20%는 validation data, 남은 20%는 test data로 적용하였습니다.

이진 분류(Binary Classification)로 긍정 또는 부정을 나타냅니다.
