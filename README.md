# Fcm_Client App
> [Web] 2020-1 캡스톤디자인 - 유해가스 비상알림 앱
<br/>

## ✨ summary
아두이노에서 측정된 센서값이 일정 범위를 초과했을떼 작업자 폰으로 비상 알림이 오는 앱 제작
  <br/><br/>
## 📖 Introduction  
 Firebase Cloud Messaging 을 이용해 작업자에 설치되어져 있는 앱으로 비상알림이 실시간 전달되도록 구현하였습니다.
평상시에는 앱내에서 웹뷰를 통해 작업장 상태를 모니터링 할 수 있는 페이지가 나오고, 비상시에는 사이렌 그림과 함께 사이렌 소리가 자동으로 재생되어져 작업자로 하여금 신속히 대피할 수 있도록 돕습니다.
  <br/><br/>
## 👨‍💻 System requirements
개발은 안드로이드 스튜디오를 이용해 자바언어로 개발했습니다.<br/>
Compile SDK Version은 29이고, minimum SDK Version은 25입니다.<br/>
클래스는 크게 3개로 나눠져 있으며, 가장 기본 액티비티인 메인 엑티비티(MainActivity)와 노티피케이션(Notification)이 왔을때 처리해 주는 마이 파이얼 베이스 메세징 서비스(MyFireBaseMessagingService), 그리고 비상알림 사운드와 화면을 표시해주는 알람 액티비티(AlarmActivity) 클래스가 있습니다.

  <br/><br/>
## 📝 Todo list
제작할 코드와 문서들입니다.

- [x] [💻] Firebase와 연결
- [x] [💻] FCM 수신시 자동으로 앱 실행되도록 구현
- [x] [💻] 실행되며 사운드 재생 구현
- [x] [💻] 웹뷰 구현 - 자동으로 모니터링 페이지 열리도록 설정
- [x] [🔓] 로고 및 액티비티 내 이미지 설정 및 디테일 수정

  <br/> <br/>
  
  
## 💻 결과물
<img src="https://user-images.githubusercontent.com/56837413/85417338-729a3d00-b5aa-11ea-8806-50c8d4139720.jpeg" width="15%"></img><br/>
<img src="https://user-images.githubusercontent.com/56837413/85417270-6ca45c00-b5aa-11ea-91fb-9e97c45b8f7b.jpeg" width="35%"></img> &nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/56837413/85417314-7037e300-b5aa-11ea-8527-1395f1687d46.jpeg" width="35%"></img><br/>

  
