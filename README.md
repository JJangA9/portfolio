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

---

## [lunch-waiting](https://github.com/JJangA9/lunch-waiting)

**요약**  
lunch-waiting은 가천대학교 근처 식당의 대기시간을 알려주는 어플리케이션입니다.  
식당에 직접 가봐야 대기시간을 알 수 있다는 불편함에서 착안하여 앱으로 대기시간을 알 수 있도록 제작했습니다.   

**사용된 기술**  
- Client

 1. Socket Commucation  
  > Thead와 Handler를 통해 구현되었고 Service를 사용해 Background에서 실시간 알림을 받습니다.
 2. GPS service  
  > 사용자의 GPS를 기반으로 주변 식당을 Google Map에서 보여줍니다.
 3. Notification  
  > 대기시간을 요청했을때 또는 댓글이 달리면 상단바에 알림을 띄워줍니다.
 4. Glide Library  
  > 식당 이미지를 나타내는데 사용됩니다.

- Server  

 1. REST API  
  > Login token을 확인하고 증명하는데 사용됩니다.
 2. MySQL  
  > 식당의 정보를 Crawling 하고 Database에 저장합니다.

**사용해보기**  
사용자에게 GPS 권한을 받고 사용자가 근처 식당의 대기시간을 입력합니다.  
입력되면 다른 사용자에게 그 대기시간이 표시되는 방식입니다.  
사용자는 주변 식당 위치를 Google Map을 통해 볼 수 있으며 원하는 식당에 좋아요를 누를 수 있습니다.  
또한 게시판에 원하는 글을 남기고 댓글을 달 수 있습니다.  

하단 이미지를 누르시면 유튜브로 넘어갑니다.
[![lunch waiting 데모](https://img.youtube.com/vi/V3zJFMWD8Es/0.jpg)](https://www.youtube.com/watch?v=V3zJFMWD8Es)


## [todo-Application](https://github.com/JJangA9/TodoApplication)
## [AR-app](https://github.com/JJangA9/AR-app)
