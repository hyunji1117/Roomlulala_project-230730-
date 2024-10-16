<!-- # Roomlulala
1. main image   
><img src="./img/main.png" width="450px" height="300px" title="main" alt="main"></img><br/>
2. list image   
><img src="./img/list.png" width="450px" height="300px" title="main" alt="main"></img><br/>
3. info image   
><img src="./img/info.JPG" width="450px" height="300px" title="main" alt="main"></img><br/>

https://i-ri.tistory.com/39
https://choa-ri.tistory.com/74 -->

* 구현한 기능
    
[CRUD](https://github.com/4BFC/Roomlulala_project/blob/master/Roomlulala/info/js/app.js>)
    
[Google map 임베드 코드](https://codingdaisy.tistory.com/50>)
     
[검색 기능](https://github.com/4BFC/Roomlulala_project/blob/master/Roomlulala/main/test/test_search/search.js>)
    
[별점 기능](https://github.com/4BFC/Roomlulala_project/blob/master/Roomlulala/info/test/Star_test/app.js>)
    
[로그인 기능](https://github.com/4BFC/Roomlulala_project/blob/master/Roomlulala/info/test/Star_test/app.js>)
    
    
    
* 아쉬웠던 점
> Github : 깃 허브 브런치를 좀더 적극 적으로 활용했으면 파일을들을 더욱 잘 분산해서 사용 했을 수 있었는데 잘 안되서 아쉽다.
> api : api를 적극적으로 사용하지 못한 점이 아쉬웠다. api를 사용해서 사용자 정보를 가져왔다면 더욱 다양하게 활용했을 것 같다.
> 구성 : info파일 부분에서 js를 너무 많이 부분별로 나뉜거 같아서 조금은 복잡해 보였다.
    

* 보완해야 할 점
> info    별점기능을 test버전으로 만들긴 했으나 완벽히 구현하지 못한 것.   로그인 구현에 따른 댓글관리 시스템 구축이 미약하다.    
    
> 세부적인 페이지 구현이 미약해서 보완이 필요하다..
    
> 전반적으로 재점검하면서 실제 사이트를 이용할 수 있는 정보들을 우선순위로 리패토링 해볼 필요가 있다.
   
> css에서 transition이 들어가서 더욱 자연스러운 UX를 연출하는 부분에 보완이 필요하다.
   
> 사용자에게 도움이되는 서비스로 개선할 필요가 있다.
    

* 마무리를 지으며
> 프로젝트가 우리의 의도와는 달리 완성도가 높지는 않았지만 생각과 정보를 공유하면서 진행 과정들이 만족스러웠다. 이를 기반으로 공부를 하고 싶은 재미가 생겼다. 구체적으론 효율적인 코딩 방식에 관심이 생겼고 이론들을 공부하면서 코드에 대입해 보고 싶다.
    
> 각자 개인 프로젝트로 웹 사이트를 만들어서 코드를 리뷰하는 방식으로 스터디를 해도 좋을 듯하다.


# 방탈출 카페 정보 제공 웹사이트

##### 참여자: 김현지(방탈출 리스트 페이지), 장X용, 김X우 (팀 프로젝트)  
  
#### 프로젝트 기간: 2023.07.30 ~ 2023.08.30 (4주)  
  
#### 프로젝트 도구: Media Query
  
#### 사용 언어: Html, Css, Javascript  
  
### 프로젝트 개요  
  - 방탈출 카페 정보를 제공하는 웹사이트 구현.
  - 사용자는 방탈출 카페 리스트 조회 및 후기 좋은 카페와 난이도 별 추천 방탈출 정보를 확인할 수 있도록 함.
  - 방탈출을 함께할 사람을 모집할 수 있는 공간 제공.
  
### 프로젝트 배경  
#### 팀워크와 문제 해결 능력이 돋보이는 방탈출 게임
  - 방탈출 애호가들은 원하는 카페나 테마를 찾기 위해 다양한 웹사이트를 방문해야 하는 불편함을 겪음.
  - 이 프로젝트는 방탈출 카페 정보를 한 곳에서 확인하고, 사용자들이 리뷰와 난이도 별 추천을 통해 더 쉽게 카페를 선택할 수 있도록 돕기 위해 시작함. 
  
### 프로젝트 진행 과정  
1. 기획 단계 (UI 설계)
  #### 피그마를 사용하여 UI 기획:  
  - 피그마(Figma)를 활용해 웹사이트의 전체적인 레이아웃과 UI 구조 설계.
  - 메인 페이지, 검색 페이지, 상세 정보 페이지 등의 와이어프레임을 작성하여 주요 섹션(검색 바, 추천 콘텐츠, 카페 리스트 등)을 시각적으로 표현.
  #### 사용자 흐름 및 인터페이스 정의: 
  - 사용자가 사이트를 이용하며 어떻게 정보를 찾아 갈지에 대한 플로우 정의
  - 각 페이지별로 필요한 요소 배치.  
  
2. Html 구조 설정
  #### Html 요소 배치: 
  - Html5를 사용해 페이지의 기본 구조 구축.`<header>, <nav>, <section>, <footer>` 등을 활용해 각 페이지를 구분하고 콘텐츠 영역을 설정.  
  #### 검색 바 및 네비게이션 메뉴 구현: 
  - 사용자들이 쉽게 검색하고 사이트를 탐색할 수 있도록 검색 바와 네비게이션 메뉴를 추가.  
  
3. Css 스타일 적용
  #### 외부 및 내부 CSS 연결: 
  - Css 파일을 외부에 두어 스타일을 설정.
  - Css 변수(:root)를 사용해 일관된 색상 테마를 적용 및 기본적인 레이아웃 구성.  
  #### 반응형 웹 디자인 설정: 
  - 미디어 쿼리를 사용해 다양한 화면 크기에서도 사이트가 일관성 있게 보이도록 반응형 디자인을 구현. 
  #### 카드 레이아웃 사용: 
  - 방탈출 카페 정보를 카드 형태로 배치하여 사용자가 한눈에 정보를 볼 수 있도록 시각화.  
  
4. JavaScript 기능 추가
  #### 로그인 유효성 검사 구현: 
  - 로그인 페이지에서 간단한 사용자 이름 및 비밀번호 유효성 검사 구현.
  - 잘못 된 정보가 입력될 시 경고 메시지 팝업.  
  #### 검색 필터 기능 구현: 
  - 검색 입력란에 실시간으로 키워드를 입력하면 관련된 카페와 테마를 필터링할 수 있는 기능 구현.  
  
5. 디자인 요소 및 사용자 인터페이스 개선
  #### 폰트 및 아이콘 추가: 
  - Google Fonts와 FontAwesome을 사용해 독특한 폰트와 아이콘 추가. 이를 통해 방탈출 테마에 맞는 분위기 연출.  
  #### 소셜 로그인 버튼 추가: 
  - Facebook, Google, Twitter와 같은 소셜 미디어 계정을 통해 로그인할 수 있는 버튼을 추가해 사용자 편의성 향상 목표 설정.  
  
6. 테스트 및 최적화
  #### 브라우저 테스트: 
  - 다양한 브라우저에서 페이지가 일관되게 보이는지 확인. 
  - Css 리셋 파일을 사용해 브라우저 간의 기본 스타일 차이 줄임.  
  #### 디바이스 테스트:  
  - 다양한 크기의 디바이스(모바일, 태블릿, 데스크탑)에서 테스트하여 반응형 디자인이 정상적으로 작동하는지 점검. 

<p align="center">
  <img width="460" height="300" src="./img/Roomlulala_project(1).png">
</p>  
  
<p align="center">
  <img width="460" height="300" src="./img/Roomlulala_project(2).png">
</p> 

<p align="center">
  <img width="460" height="300" src="./img/Roomlulala_project(3).png">
</p> 

<p align="center">
  <img width="460" height="300" src="./img/Roomlulala_project(4).png">
</p> 

<p align="center">
  <img width="460" height="300" src="./img/Roomlulala_project(5).png">
</p> 