# 📀PODO MUSIC

<h1>
  1. 프로젝트 소개
</h1>
<p align="center">
  <img src="https://user-images.githubusercontent.com/115390448/228555238-2fbd2d61-1902-44e2-8ce9-4438f5127c6b.png">
  <p align="center", font-size="10px"> 
     PODO MUSIC은 음악 스트리밍 기능을 구현한 사이트 입니다.<br>
     https://github.com/YeChan3110/Podo-Project-BackUp
  </p>
</p>
<hr>

### 1-1. 프로젝트 개요<br>
- 개발기간 : 2022.11.01 ~ 2022.11.17 (17일)<br>
- 개발인원 : 5명<br>
- 주요 구현기능 : 회원가입/로그인, 음악 컨트롤러(재생, 일시정지, 목록), 결제(이용권 결제, 멤버십 기능), 관리자페이지(회원관리, 음원관리, 공연관리), 공연예매 
- 팀원 구성
  1. 강예찬(팀원) : 관리자페이지(메인화면, 회원관리, 음원/공연 CRUD), 멤버십 결제 (기여도 100%)
  2. 박세진(팀장) : 음악 컨트롤러 기능, 관리자페이지(문의사항)
  3. 정택구(팀원) : 회원가입 / 로그인, 차트, 메인페이지
  4. 차석호(팀원) : 공연 예매, 취소 기능
  5. 신유진(팀원) : 위시리스트, 마이페이지, 문의하기
  
- 주제 선정 이유 
  - 기존 음원사이트(멜론,지니,바이브 등)에서 음원을 듣기 위해서는 따로 어플리케이션을 설치해야만 음원을 들을 수 있었음.
  - 따로 설치 없이 웹에서 음원 재생이 가능한 사이트를 구현하고자 함
  - 전체적인 디자인은 바이브를 참고하였음

### 1-2. 개발 환경<br>
- Java 11, JavaScript(Jquery), JSP
- JDK 11
- IDE : Eclipse, SQL Developer
- Database : Oracle 11
- Template Engine : jstl

### 1-3. ERD
<p align="center">
  <img width="1002" alt="ERD 수정본" src="https://user-images.githubusercontent.com/115390448/228571926-6845ea38-7de0-4c92-939f-7fb572db59ff.png">
</p>

### 1-4. 작업 일정
<p align="center">
  <img width="795" alt="일정" src="https://user-images.githubusercontent.com/115390448/228572543-624d480c-a6e2-4359-88b8-847c0614c2b1.png">
</p>

<h1>
  2. 구현 화면
</h1>
### 메인화면
  <img width="951" alt="mainPage" src="https://user-images.githubusercontent.com/115390448/228572827-488748c6-bc43-48f0-848b-537b7e9922ba.png">
 - 로그인을 하면 페이지 아래에 뮤직 플레이어가 나타
 <img width="953" alt="mainPage(with player)" src="https://user-images.githubusercontent.com/115390448/228572995-f2f9adf2-a216-4df4-9765-2ee2967be23e.png">

### 회원가입 화면
<img width="956" alt="signUp(web)" src="https://user-images.githubusercontent.com/115390448/228573168-0fd5d12b-6c83-4925-aa18-c15bc83f9bcc.png">

### 음원 차트,위시리스트 화면
 - 차트에서 음원을 클릭하면 플레이어 음악 목록에 음원이 추가됨
<img width="953" alt="chart" src="https://user-images.githubusercontent.com/115390448/228573360-bddff9ad-d9e2-4d41-8bd8-6c3d59e1f53f.png">
 - 음악에 있는 하트표시를 누르면 위시리스트에 추가됨
 <img width="953" alt="wishlist" src="https://user-images.githubusercontent.com/115390448/228574578-6e69bc8a-94f8-40c9-a482-97c760e1c346.png">


### 재생목록(플레이어)
<img width="954" alt="playerList" src="https://user-images.githubusercontent.com/115390448/228573631-eeb0bb1e-dcea-4a37-9b5a-f974163438a7.png">

### 멤버십 구매
 - 원하는 멤버십을 클릭하면 멤버십 내용이 출력되고 카카오페이 결제를 할 수 있음.
<img width="626" alt="getMembership" src="https://user-images.githubusercontent.com/115390448/228573765-5cf5a00f-3f35-4325-a385-5a0de1a4a3e4.png">

### 마이페이지
 - 개인정보 수정 및 사용중인 멤버십 내역, 예매한 공연 내역을 확인할 수 있음.
<img width="882" alt="mypagePerform" src="https://user-images.githubusercontent.com/115390448/228574151-00d3c567-b919-4764-8f0d-34e73730f1c5.png">

### 공연/콘서트 예매
<img width="1133" alt="ticketMain" src="https://user-images.githubusercontent.com/115390448/228574738-66b96061-c5b2-4961-82ed-5c719eedb80f.png">
<img width="1120" alt="ticketDetail" src="https://user-images.githubusercontent.com/115390448/228574841-81efec89-a811-4d6d-bdef-d226b92dd514.png">

### 관리자페이지
 - 메인화면에 매출액, 회원 정보, 문의내역 표시함
<img width="855" alt="adminMain" src="https://user-images.githubusercontent.com/115390448/228574978-e453185b-847b-46c3-9918-50e428854c98.png">
 - 음원 / 공연 / 멤버십 (추가/수정/삭제)
 - 현재 등록된 음원,공연,멤버십 현황을 확인하고 수정/추가/삭제가 가능함
 <img width="911" alt="adminPerform" src="https://user-images.githubusercontent.com/115390448/228575378-eb5585e2-dd5c-461e-afc5-671c4b230b42.png">
<img width="914" alt="adminAddMusic" src="https://user-images.githubusercontent.com/115390448/228575246-4690fa63-b8db-438a-ba7c-ecb89df1b3bf.png">








