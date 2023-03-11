#  🫀 심장병 진단 예측 프로젝트 🩺

##  📜 개요
이 프로젝트는 환자의 나이, 혈압, 흡연 여부 등 정보를 활용해 심장병 진단을 받았는지 여부를 예측한다. <br><br>
  • 이진 분류 문제 <br>
  • 목표 변수 (label): 심장병 진단 여부 <br>

## 📊 데이터
  • 학습 데이터: train.csv 정답 레이블 포함 <br>
  • 데이터 인코딩: UTF-8 <br>
  • <b>변수 명세<b> <br>

```diff
+ 성별 (1:man , 2:woman )   
+ 키 (cm) 
+ 몸무게 (kg) 
+ 수축기 혈압 (mmHg) 
+ 이완기 혈압 (mmHg) 
+ 콜레스테롤 수치 (1: normal, 2: above normal, 3: well above normal) 
+ 포도당 수치 (1: normal, 2: above normal, 3: well above normal) 
+ 흡연 여부 (0: No, 1: Yes) 
+ 음주 여부 (0: No, 1: Yes) 
+ 신체 활동 여부 (0: No, 1: Yes) 
- label (0: Not Diagnosed, 1: Diagnosed) 
```

 ## ⚖️ 성능평가 기준 
 - F1-score(70%), AUC(30%) 가중 평균 
  
  
 ## Is this actually woking
    
