# face_recognition_model
#1. 얼굴인식 원 소스 코드 주소 URL
https://github.com/today-is-orange2two/face_gender_recognition.git

#2. 개요
opencv를 이용해 얼굴을 인식하고, 성별을 판별할 수 있는 프로그램이다.
프로그램을 실행하면 사용자를 등록할 수 있고, 
등록된 정보는 creat_database.py를 통해 detabase.db에 업로드 되는 것으로 보이고, 사용자 삭제 및 변경, 초기화 또한 선택 가능하다. 

#3. 장단점 분석

실행 했을 경우 얼굴이 정확히 다 나오지 않더라도 결과값이 정확하게 나왔다. 다른 비교군이 없어 정확하게 비교할 수는 없지만, 머리카락의 모양의 이미지만으로도 성별을 식별할 수 있는 장점을 가진 모델이지만, 이로 인해 머리가 짧거나 긴 여성/남성의 경우 잘못된 결과값을 낼 수도 있다는 단점이 있을 것이다. 또한 ‘여성입니다’, ‘남성입니다’ 와 같은 결과를 전송한다는것과 달리 female이라고 결과에서 나타났다. 
 조명이 환하지 않더라도 제대로 인식을 하였고, 각도가 다양하더라도 같은 결과값이 나옴으로 정확성이 뛰어난 모델로 보였다.
