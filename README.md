# Classroom-Smart-Ventilation-System
### 강의실 스마트 환기 시스템

![image](https://github.com/ahastuart/Classroom-Smart-Ventilation-System/assets/117140125/16c51e7d-bb56-47f7-b470-6ab07d39b3c0)

<br>

### 프로젝트 소개
<img width="600" alt="image" src="https://github.com/ahastuart/Classroom-Smart-Ventilation-System/assets/117140125/df9b8f87-252c-416a-a782-d5aeeef371dc">
<br> 
다양한 공기질 센서(미세먼지 센서, 불꽃 센서)를 사용하여 강의실 공기 오염수치를 측정하여 창문과 환풍기 자동 제어기능을 구현한 프로젝트


### 유사 프로젝트와의 차별성
기본 프로젝트들은 실내 공기질의 측정값만을 통하여 창문 제어 시스템을 구축하였다. <br>
본 프로젝트는 공기질과 더불어 화염 수치를 측정하여 다양한 상황에 적용하였다. 또한 강의실이라는 특정 공간을 사용하여 그에 맞는 서비스를 구축하였다.


### 핵심 기능
1. 강의실의 미세먼지 농도와 화재 감지 기능
2. 센서에서 수집한 데이터를 LoRa 통신으로 게이트웨이(Wemos)에게 전송
3. 게이트웨이(Wemos)에서 Aws로 전송 및 저장
4. 창문 개방 및 환푼기 자동 제어 기능


### 시스템 구성
<img width="600" alt="image" src="https://github.com/ahastuart/Classroom-Smart-Ventilation-System/assets/117140125/a4432b6e-a39c-415c-ba42-bcc913b5c8a8">


### 간단한 기술 소개
미세먼지 센서 --> 대기질 측정
불꽃 센서 --> 대기질 측정
서브 모터, 환풍기 팬 --> 대기질이 안좋아지거나 일정 수치 이상 불꽃이 감지되면, 서브모터로 창문을 열고 환풍기 작동 (수치가 다시 정상화되면, 환풍기가 꺼지고 창문이 다시 닫힘.)


### 앱
![image](https://github.com/ahastuart/Classroom-Smart-Ventilation-System/assets/117140125/9a335ddd-d77d-48c7-8ebd-998fccaa4add)
앱은 현재 레이아웃만 구성함.



   
