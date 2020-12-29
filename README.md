# portfolio
이 페이지는 제 개인 프로젝트 중 몇 가지를 추려 소개합니다.

## 기술 스택
프로젝트에서 사용한 기술 스택입니다.

- 언어  
  - Java
  - Kotlin
  
- 프레임워크 / 툴킷  
  - Adroid Studio
  - Unity

---

## Table of Contents
- lunch-waiting
- todo-Application
- AR-app


## [lunch-waiting](https://github.com/JJangA9/lunch-waiting)


### 요약  
lunch-waiting은 가천대학교 근처 식당의 대기시간을 알려주는 어플리케이션입니다.  
식당에 직접 가봐야 대기시간을 알 수 있다는 불편함에서 착안하여 앱으로 대기시간을 알 수 있도록 제작했습니다.   

### 사용된 기술

- **Client**

 1. Socket Commucation  
  Thead와 Handler를 통해 구현되었고 Service를 사용해 Background에서 실시간 알림을 받습니다.
 2. GPS service  
  사용자의 GPS를 기반으로 주변 식당을 Google Map에서 보여줍니다.
 3. Notification  
  대기시간을 요청했을때 또는 댓글이 달리면 상단바에 알림을 띄워줍니다.
 4. Glide Library  
  식당 이미지를 나타내는데 사용됩니다.  
  
- **Server**  

 1. REST API  
  > Login token을 확인하고 증명하는데 사용됩니다.
 2. MySQL  
  > Crawling한 식당의 정보를 Database에 저장합니다.

### 사용해보기
사용자에게 GPS 권한을 받고 사용자가 근처 식당의 대기시간을 입력합니다.  
입력되면 다른 사용자에게 그 대기시간이 표시되는 방식입니다.  
사용자는 주변 식당 위치를 Google Map을 통해 볼 수 있으며 원하는 식당에 좋아요를 누를 수 있습니다.  
또한 게시판에 원하는 글을 남기고 댓글을 달 수 있습니다.  

> 하단 이미지를 누르시면 유튜브로 넘어갑니다.  
[![lunch waiting 데모](https://img.youtube.com/vi/V3zJFMWD8Es/0.jpg)](https://www.youtube.com/watch?v=V3zJFMWD8Es)  

---

## [todo-Application](https://github.com/JJangA9/TodoApplication)


### 요약
todo-Application은 유저의 일정을 저장하고 해당 날짜가 다가오면 알림을 띄워주는 어플입니다.  

### 사용된 기술

- RoomDB
  > 사용자가 입력한 일정을 RoomDB에 저장하여 Recycler view로 보여줍니다.  
- Google Admob  
  > 메인화면, 설정화면 하단에 광고를 삽입하였습니다.  
- Notification  
  > 저장된 일정의 날짜가 되면 상단바에 알림을 띄워줍니다.

### 사용해보기
사용자는 원하는 일정을 아이콘과 함께 추가할 수 있습니다.  
또한 간편하게 일정을 슬라이드하여 제거할 수 있으며, 수정하고 싶은 일정을 클릭하여 수정가능합니다.  
알림 수신여부는 환경설정에서 설정할 수 있습니다.  

> 하단 이미지를 누르시면 유튜브로 넘어갑니다.  
[![Todo Application 데모](https://img.youtube.com/vi/ehVcs0IErOY/0.jpg)](https://www.youtube.com/watch?v=ehVcs0IErOY)  

---

## [AR-app](https://github.com/JJangA9/AR-app)  


### 요약
AR-app은 Unity를 이용한 AR 증강현실 어플리케이션입니다.  
스마트폰 카메라로 지정된 마커를 비추면 가상 아바타가 나타나는 방식입니다.  

### 사용된 기술

- Vuforia
  > AR 프로그램을 개발하기 위해 Unity에 Vuforia를 적용했습니다.  
- Assets
  > Robot Kyle, Fox, SimpleSky asset이 가상 캐릭터로 사용되었습니다.

### 사용해보기  
지정된 마커만 인식되므로 영상에 나타나는 분홍 패드만 인식됩니다.  
스마트폰 카메라로 패드를 비추면 가상 로봇, 여우, 구름이 나타납니다.  

> 하단 이미지를 누르시면 유튜브로 넘어갑니다.  
[![AR application 데모](https://img.youtube.com/vi/hxOvGPYa1H0/0.jpg)](https://www.youtube.com/watch?v=hxOvGPYa1H0)
