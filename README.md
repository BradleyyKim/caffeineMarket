# ☕️ caffeineMarket
## **1. 프로젝트 소개**

커피를 좋아하는 현대인이라면 손쉽게 로그인하여 커피와 관련된 상품을 판매하고 일상을 공유할 수 있는 SNS 서비스입니다.  커피와의 일상을 게시글로 공유하며 좋아요와 댓글을 통해 사용자와 소통합니다. 다양한 사람들을 팔로우하고, 마음에 드는 피드가 있다면 '좋아요'를 누르거나 댓글을 달 수도 있습니다. 또한, 다른 사용자와 채팅창을 이용해 즐거운 대화도 나눌 수 있습니다.

<br>

## 2. 팀원 소개(2호선 불주먹팀)
|김민영|김지수|김태희|채지훈|
|:-----------:|:-----------:|:-----------:|:-----------:|
| <img width="180px" src="https://user-images.githubusercontent.com/101693495/180898054-cf7cbf5c-0476-402b-b7bd-a088ffd6d126.jpg">| <img width="180px" src="https://user-images.githubusercontent.com/101693495/180899475-794fd51c-cef7-4154-b452-aeda89dd6f09.png"> | <img width="180px" src="https://user-images.githubusercontent.com/101693495/180899712-35607b00-3b6f-408d-8f7f-568a60072be9.jpg"> |<img width="180px" src="https://user-images.githubusercontent.com/101693495/180897571-3f123fcb-517b-4c82-83be-af644a98c973.jpg">|
|🔗 <a href="https://github.com/BradleyyKim">BradleyyKim</a>|🔗 <a href= "https://github.com/jsk3342">jsk3342</a>|🔗 <a href="https://github.com/greenT-Hee">greenT-Hee</a>|<a href ="https://github.com/jihoon-chae">🔗 jihoon-chae</a>|

<br>

## 3. 목표
리액트 및 뷰 라이브러리를 활용하기 전 라우팅, 상태관리, 비동기 통신 개념 이해를 목표로 바닐라 자바스크립트로 반응형 사이트 구현 

<br>

## 4. 개발 환경 

### 4.1 스택
* Front-End : HTML CSS JavaScript
* Back-End : 제공된 API 사용
### 4.2 개발 관리
* 버전 관리 및 이슈 : Github, Jira, Slack
* 회의록: 🔗 <a href="https://github.com/secondlinefirefist/caffeineMarket/wiki/2%ED%98%B8%EC%84%A0-%EB%B6%88%EC%A3%BC%EB%A8%B9-%ED%9A%8C%EC%9D%98%EB%A1%9D-%F0%9F%94%A5">Github Wiki</a>, Notion
* 디자인 : Figma, Illustrator

|Jira|Slack|
|:-----------:|:-----------:|
|<img src= "https://user-images.githubusercontent.com/101693495/181179852-4a42b02f-c587-46dd-8538-680c771163b2.png" width= "500px">|<img src="https://user-images.githubusercontent.com/101693495/181180614-afc1cba9-e4d2-478c-9747-3026c5277c26.png" width="360px">|

### 4.3 배포
> 🧷 <a href="https://secondlinefirefist.github.io/caffeineMarket">배포 URL</a>

<br>

## 5. 프로젝트 구조와 개발 일정
### 5.1 프로젝트 구조
```
.
├──📁 src
   ├──📁 pages
   |   └── ...html
   ├──📁 css
   ├──📁 img
   └──📁 js
```

## 6. 역할 분담

### 👨🏻‍🚒 김지수
- splash 구현
- 로그인 기능 구현
- 회원가입 구현
- 프로필 수정 구현

### 👨🏻‍🚒 김민영
1. 게시글 등록(upload)
    - 텍스트 입력 및 업로드 구현
    - 여러 이미지 업로드 구현
    - POST요청으로 API에 데이터 저장
2. 게시글 상세 페이지(postDetail)
    - myProfile 페이지에서 이미지 클릭 시 postId값을 불러와 상세 페이지 UI 구현
    - API에 저장된 개인 로그인 토큰을 이용해 GET요청을 통해 UI 구성
    - 댓글 UI 구현
3. 댓글 작성 기능(commentLoad)
    - 댓글 작성 시 reload를 통해 댓글 실시간 추가 구현
4. 검색페이지(search)
    - 검색 결과 박스 실시간 구현 예정

### 👨🏻‍🚒 채지훈
- 상품등록 (product)
   - 이미지 업로드 기능 구현
   - 상품 데이터 POST 요청

- 상품수정(productModification)
   - 이미지 업로드 기능 구현
   - 상품 데이터 GET요청/ PUT 요청

- 채팅방(chatRoom) 
   - 텍스트 입력후 전송 버튼 클릭시 채팅창에 렌더링
   - 이미지 업로드시 채팅창에 렌더링

### 👷🏻‍♀️ 김태희
- myProfile & yourProfile 
   - 유저 정보, 상품&게시글 리스트 PUT, POST, GET, DELETE 요청
   - 공용 및 프로필 모달  기능 구현
   - 로그아웃 기능 구현

- follwing & follower
   - 팔로잉/ 팔로우 API GET, DELETE, POST
   - 팔로우 버튼 누르면 숫자 증감 반영  

- 좋아요 기능 
   - 좋아요 API POST, DELETE 요청

- 일러스트 로고 디자인
   - 카페인 마켓 캐릭터 로고 및 아이콘 제작

## 7. 개발 기간
2022.06.09 ~ 2022.07.31

<br>

## 8. 페이지 기능
상세 기능 설명은 각 페이지별 링크 연결해두었습니다.
1) 홈

|🔗splash|🔗로그인 페이지|🔗회원가입 페이지|
|------|---|---|
|내용 넣기| 내용 넣기 | 내용넣기|
|🔗홈 페이지|🔗검색 페이지|🔗채팅 페이지|
|내용 넣기| 내용 넣기 | 내용넣기|
		
2) 게시글

|🔗게시글 작성 페이지|🔗게시물 상세 페이지|
|------|---|
|내용 넣기| 내용 넣기 |
|🔗게시글 수정|🔗댓글 삭제 |
|내용 넣기| 내용 넣기 |
	
3) 프로필

|🔗마이 프로필 페이지|🔗유저 프로필 페이지|🔗팔로워 페이지|
|------|---|---|
|내용 넣기| 내용 넣기 | 내용넣기|
|🔗팔로잉 페이지|🔗로그아웃 페이지|🔗프로필 수정 페이지|
|내용 넣기| 내용 넣기 | 내용넣기|
		
4) 판매 상품

|🔗상품 등록 페이지|🔗상품 수정 페이지|
|------|---|
|내용 넣기| 내용 넣기 |
|🔗상품 삭제 페이지|🔗상품 사이트로 이동 페이지 |
|내용 넣기| 내용 넣기 |
	
## 9. 트러블 슈팅(핵심 로직)

## 10. 시연 영상 

## 11. 스페셜 포인트

## 12. 고생담 

## 13. 레슨런 

