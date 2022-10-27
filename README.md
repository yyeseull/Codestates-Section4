# Codestates-Section4
# 1. 프로젝트 개요
 초기 자각증상이 없는  안질환은 나이를 불문하고 정기검진을 통한 조기 발견이 필수적이다.안구는 치료시기를 놓치면 시력회복이 불가능할 뿐 아니라 치료비용도 기하급수적으로 늘어 날 수도 있다.
나아가 안구는 채혈하지 않고도 혈관을 볼 수 있는 가장 바깥에 있는 인체기관이다. 눈의 혈관을 보면 다른 내과 진단도 판단 할 수 있을 것으로 예상한다.고령화가 증가하는 현 시점에서 눈 검사는 필수적이라고 생각한다.<br>
그래서 더 쉽게 눈 검사를 할 수 있으며 조금 더 발전을 하여 집에서 자가진단만 으로 안질환을 예측할 수 있길 바라며 프로젝트를 준비하였다. <br><br><br>

# 2. 데이터 
- 출처 : 캐글 
[ https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k?select=full_df.csv ]
- 안구 사진 & csv 파일 
- 안구 질병 : 정상[N], 백내장[C], 녹내장[G], 연령관련 황반변성[A] <br><br><br>

# 3. 모델 
<img width="541" alt="image" src="https://user-images.githubusercontent.com/102211628/198277321-86602892-c9f6-48a2-9c14-b93209f2506a.png">
<img width="537" alt="image" src="https://user-images.githubusercontent.com/102211628/198277353-86a6413d-2fd2-466a-aec5-2e1aad625c87.png">
<img width="355" alt="image" src="https://user-images.githubusercontent.com/102211628/198277381-020bb2eb-d847-49cc-b807-bdbe6b10b7b5.png">
<img width="548" alt="image" src="https://user-images.githubusercontent.com/102211628/198277412-ee0cc7cd-7a30-4889-bf06-3a3276a07bd4.png">

- 모델 : ResNet50
- 활성함수 : softmax
- Accuracy : 0.789 <br><br><br>

# 4. 시연
<img width="911" alt="image" src="https://user-images.githubusercontent.com/102211628/198277601-bcf7a49c-af48-45a6-b06c-986d8fdd4239.png">
<br><br><br>

# 5. 보안점 
- 데이터가 불균형하므로 데이터를 더 수집하거나 Oversampling을 진행후 정확도를 높일 예정.
- 안과질병 이외에 다른 내과 질병도 예축 할수 있도록 함.

