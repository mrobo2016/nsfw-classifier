# nsfw-classifier
유해 이미지 차단


설치, 환경:  
pip install nudenet  
tf version == 1.15.2 
  
구성 기능:  
1. 중요부위 box 필터
2. 사진파일에 warning, safe 임배딩
3. 텔레그램 API 사용 (문자 + 이미지첨부 기능 사용)
4. NudeNet Classifier

  
  

참고:  
https://github.com/notAI-tech/NudeNet  
https://praneethbedapudi.medium.com/nudenet-an-ensemble-of-neural-nets-for-nudity-detection-and-censoring-c8fcefa6cc92


Dataset:  
The entire data for the classifier is available at https://archive.org/details/NudeNet_classifier_dataset_v1  
A part of the auto-labelled data (Images are from the classifier dataset above) used to train the base Detector is available at https://github.com/notAI-tech/NudeNet/releases/download/v0/DETECTOR_AUTO_GENERATED_DATA.zip
