# 2021-2 졸업프로젝트

##### 2021.09.01 ~ 2021.11.09
##### Version 1.0


## 프로젝트 설명
최근 MZ세대 사이에서 MBTI에 대한 관심이 인기를 몰고 있으며, 코로나 바이러스로 인해 사람들이 대부분 집에 있는 시간이 많아졌습니다.
그 영향으로 영화시청 시간이 많아짐에 따라 영화콘텐츠에 대한 추천시스템 프로젝트입니다.

해당 프로젝트는 MBTI에 초점을 두어 성격유형별로 개인에게 영화를 추천해주는 어플리케이션 프로젝트이며,

본 레포지토리에서는 프론트앤드(클라이언트)인 안드로이드(Android Studio)를 주로 다룹니다.

<br/><br/>
## 프로젝트 유스케이스

<img width="430" alt="image" src="https://user-images.githubusercontent.com/108053426/203484509-85e731d6-2218-46fb-afe4-b2c619843e70.png">



<br/><br/>
## 프로젝트 프로세스 설계

<img width="430" alt="image" src="https://user-images.githubusercontent.com/108053426/203484449-197f98ca-86e3-409f-aa13-cafabc9ec9a1.png">



<br/><br/>
## 프로젝트 화면 설계
<br/>
1. 실행 및 로그인/회원가입 화면


<img width="279" alt="image" src="https://user-images.githubusercontent.com/108053426/203480119-a3904bbc-8419-4b5a-862e-c89c5a386d71.png"> <img width="279" alt="image" src="https://user-images.githubusercontent.com/108053426/203480194-be6f203f-986d-45b0-9162-f4d225626b2b.png"> <img width="281" alt="image" src="https://user-images.githubusercontent.com/108053426/203480228-79d3d13e-53d8-4d5c-b619-1083c9ce3cd3.png">

<br/>
2. MBTI 선택 및 검사 화면


<img width="280" alt="image" src="https://user-images.githubusercontent.com/108053426/203480263-b1338e46-2dde-4fa0-8da9-8e66307093e8.png"> <img width="280" alt="image" src="https://user-images.githubusercontent.com/108053426/203480332-59b4ec85-90de-4a1f-8c32-6083e8a75c89.png">

<img width="282" alt="image" src="https://user-images.githubusercontent.com/108053426/203480297-aab336a8-ba5e-4896-abdb-9438dcdd2541.png">
<br/>
3. 영화에 대한 개인 리뷰 화면


<img width="277" alt="image" src="https://user-images.githubusercontent.com/108053426/203480381-7b0fcbe3-ed32-4e60-b0ca-6bb40b8330d4.png">
<br/>
4. 추천되는 영화콘텐츠 화면


<img width="280" alt="image" src="https://user-images.githubusercontent.com/108053426/203480421-8ed8af0d-1732-4235-974e-b67a72bcd0ad.png"> <img width="279" alt="image" src="https://user-images.githubusercontent.com/108053426/203480446-33d363f0-8dff-4203-ab59-5fb8995706c8.png">
<br/>
5. 로그아웃 및 종료 화면


<img width="281" alt="image" src="https://user-images.githubusercontent.com/108053426/203480510-9db4321d-a131-4c00-8277-2658e938592f.png">

<br/><br/>
## 프로젝트 시연 영상
<br/><br/>
## 추천시스템 알고리즘 설명


<아이템 기반 협업 필터링 알고리즘>
협업 필터링은 사용자기반 협업필터링과 아이템 기반 협업 필터링이 있는데, 본 프로젝트에서는 콘텐츠가 '영화'이기에 아이템 기반 협업 필터링을 사용하였습니다.

협업 필터링 추천 시스템은 사용자의 데이터를 가지고 선호도에 따라 자동적으로 예측하여 제공해주는 방법입니다.

코사인 유사도를 통해 평점이 비슷한 아이템끼리 추천을 해주는 함수를 사용하였습니다. 그럼 각 영화끼리 서로 유사한 정보의 값을 가지게 됩니다. 그럼 서로 유사도가 가까운 영화일수록 1에 가깝고, 자기 자신과 같은 영화이면 유사도 값이 1이 됩니다.

이런 데이터를 가지고, 자기 자신을 제외하고 유사도가 가장 비슷한 영화 개수를 정해 영화추천 기능을 구현할 수 있는 사용자 함수를 생성하였습니다. 사용자가 어떠한 영화를 볼 때 그 영화와 비슷한 영화목록을 추천하여줍니다.

<br/><br/>
## 디렉토리 설명

<br/><br/>
## 안드로이드 개발 스택
Client : Android Studio ( JAVA )
