# capstone design (의료 커뮤니티 '덕분에')

한성대학교 컴퓨터공학부 18학번 조하영(팀장), 김예원, 김한빛


### 1. 프로젝트 수행 목적

**1.1 프로젝트 정의**

- 공공 API를 활용한 웹과 앱 모두 가능한 의료 커뮤니티

**1.2 프로젝트 배경**	

- 코로나로 인해 건강에 대한 관심이 높아지고, 궁금증도 많이 생기는 이 때에 그런 의문들을 해결해줄 수 있는 곳이 필요하다고 생각되었다. 기존에는 필요한 정보를 얻기가 힘들었는데 의료 커뮤니티를 통해 정보를 쉽게 공유할 수 있고, 자신의 경험 등을 다른 사람들에게 공유할 수 있다.

- 커뮤니티를 통해 다수의 사람들이 필요한 정보들을 얻을 수 있는 '집단지성'의 개념을 활용하여 더 좋은 의료정보를 누구나 누릴 수 있는 목표로 개발하게 되었다.

- 의료서비스의 규모제한성으로 인한 고비용문제, 전문가-비전문가 사이의 정보불균형 문제를 정보통신기술(IT)로 풀어내려 한다.

**1.3 프로젝트 목표** 

- 모바일과 웹 모두 지원	

- 전문가와 일반인의 소통	

- 사용자 경험을 바탕의 일상 의료 정보 제공	

- 공공 API 및 공공 데이터를 활용한 병원/약국 위치 제공



### 2. 프로젝트 개요

**2.1 프로젝트 내용**   

* 프로젝트 시나리오
  * 사용자는 페이지나 어플에 접속한다. 커뮤니티에 글을 작성하려면 회원가입/로그인을 해야 한다. 그렇지 않고 탐색만 하려면 회원가입을 하지 않아도 된다. 
  * 자유게시판/정형외과/내과/소아과/신경외과/치과/안과/산부인과/비뇨기과/피부과 등 원하는  메뉴에 들어가면, 전문가 분야와 일반인 분야, 지도가 있다.
  * 전문가 분야는 전문가들의 말로 일반인들이 도움을 받거나 전문가들끼리 정보를 공유할 수 있다. 
  * 일반인 분야는 사용자가 본인의 경험을 기반으로 정보를 공유할 수 있다.               
  * 지도를 누르면, 사용자 위치를 기반으로 근처 병원/약국을 찾을 수 있다.사용자 관리 탭을 누르면 키/몸무게/비밀번호 등 변경 가능하다.

**2.2 프로젝트 구조**

 ![구조도](https://user-images.githubusercontent.com/48209166/119610245-e173bc00-be33-11eb-9049-bff562263993.png)

 **2.3 관련기술** 

- React
- Apache Tomcat
- Hibernate
- Bootstrap
- Android
- React
- Spring boot
- SQL
- 크롤링
  - Beautiful soup4
  - Selenium
  - python openpyxl
  - MySql for Excel
- Python
- Kakao map API
- crawling 코드 활용 https://github.com/catSirup/naver_kin_crawling/blob/master/project.py

**2.4 개발도구**  

- IntelliJ
- Android Studio
- MySQL
- Navicat
- Pycharm
- AWS
- Visual Studio Code

**2.5 개발언어**  

- Java (Android, Spring boot)
- HTML
- CSS
- Javascript
- Python



### 3. 프로젝트 추진 체계

**3.1 역할 분담**   

 ![역할분담](https://user-images.githubusercontent.com/48209166/119610518-534c0580-be34-11eb-9bc8-20ff24697c5e.png)
 
 
### 4. 소스코드
**4.1 소스코드**
- Crawling - https://github.com/equipoida/capstone
- Android - https://github.com/equipoida/capstoneAndroid
- Web(Backend) - https://github.com/equipoida/capstoneWeb
- Web(Frontend) - https://github.com/equipoida/capstoneReact

