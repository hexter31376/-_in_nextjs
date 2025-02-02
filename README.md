# 웹 프로그래밍 팀 프로젝트 과제 원본 소스
next.js 프레임워크를 통한 웹 프로그램 개발 진행을 완료하였습니다...    
기본적으로 주소가 공개되어 있기에 게시물 테러 방지를 위해 글 작성 기능을 제외한 다른 기능들은 현재 닫아놓은 상태입니다...    
다른 말로 풀어 보자면 이 프로젝트를 포크해서 env 설정을 건드리면 글의 편집이 가능하다는 이야기도 됩니다...   
기능 평가를 위해 일단 레파지토리로 소스를 공개할 예정입니다...

# **Adventure Design 과제 계획서**

## **작품과제명: 강릉원주대학교 뉴스레터 정보제공 서비스**

### **1. 과제 기획 동기 및 필요성**

위 과제를 선정한 이유로는 기존 재학생 및 신입생들이 학교 관련 정보를 찾아볼때 학교 커뮤니티중 하나인 에브리타임에 질문 및 정보 탐색을 통해 정보를 찾아내거나, 학교 홈페이지의 탐색을 통해 정보를 직접 탐문하며 찾아야 했었습니다.

물론 학교 공지사항등의 내용을 확인해도 되지만 학생들에게 필요한 정보인지, 아닌지를 파악하기가 어렵거나 탐색이 힘들다는 단점이 있었습니다.

따라서 저희 조에서는 꼭 필요한 정보를 엄선하여 제공하는 정보제공 서비스와, 신규 정보를 제공하는 뉴스레터 사이트를 제작하여 학생들이 이용할 수 있도록 하는 것이 좋겠다고 판단했고, 이를 통해 학생들의 학교 정보 접근성을 늘리는 효과를 볼 수 있기에 필요하다고 판단하였습니다.

### **2. 과제의 목표 및 개발내용**

최종 결과물은 학생들이 접속하여 내용을 확인 할 수 있는 정보제공 사이트를 구축하는것에 그 목표가 있습니다. 이에 사이트 관리자가 업로드 할 수 있는 게시판 페이지를 구축하고 전체적인 페이지의 구성은 html, css를 통해 구축하며, 글의 추가, 동적인 사이트 디자인 구축 등은 javascript와 그 외 확장 라이브러리를 이용해 구축할 예정입니다. 또한 이러한 업무는 git, github 등을 이용한 코드 버전관리 및 협업 시스템을 구축할 것이며, 회의 정보 및 개발 이슈 등은 구축해놓은 노션 페이지를 통해 프로젝트 계획을 공유하고 관리할 예정입니다

개발 업무 순서로는

-> 디자인 회의를 통한 웹 페이지 디자인 구성

-> 구현하려는 페이지의 부분들을 파트별로 나누고 업무 분담하기

-> 이슈 및 아젠다 발생시 회의, 프로그래밍

-> 실제 서비스 출시 전 사전 테스트 ->

가능하다면 도메인 발급을 통해 실제 방문할 수 있는 사이트 구축실제 서비스 출시 의 과정으로 업무가 진행 될 예정입니다.

또한 계획된 페이지가 제공할 정보로는

1. 신입생들에게 필요한 정보 피드

프로젝트 조에서 필요하다 판단한 피드

신입생들이 요청하여 필요하다 한 피드

2. 그 외 재학생들에게 필요한 정보 피드

프로젝트 조에서 필요하다 판단한 피드

재학생들이 요청하여 필요하다 한 피드

3. 그 외 정보 피드

오늘의 급식

학교 뉴스(뉴스 동아리 연계)

4. 추후 계획

가능하다면 태그 기능을 활용하여 자신에게 필요한 정보만 추려서 볼 수 있도록 설정하는 기능도 추가할 예정입니다.

또한 이러한 사이트를 제작하기 위한 정보 수집처는 학교 에브리타임과, 학교 홈페이지 공지 사항들을 통해 제공할 정보의 내용들을 수집할 예정이며,

레이아웃의 구성은 velog사이트의 홈 페이지 피드를 참고하여 제작할 예정입니다.

### **3. 과제 결과물에 대한 기대효과 및 활용방안**

처음에 ‘에브리타임’이라는 커뮤니티가 그러하였듯이 원래 시간표 자동 구성이라는 강력한 기능을 통하여 유저를 모으고 그 유저 풀을 바탕으로 대학 커뮤니티를 구축하였습니다. 이번 프로젝트를 통해 기본적으로 학생들의 학교 정보 접근성을 늘리고 이런 식으로 생긴 유저 풀을 이용하여 이후 학교 커뮤니티, 블로그 서비스, 지식 위키, 학식 관련 서비스 등으로의 확장을 기대할 수 있습니다.
  
ps) 24.10.21 기준 데이터베이스 닫혀 있습니다. 들어가도 정상 작동은 되지 않습니다.
