# 쇼핑몰 

## 비동기
- 기존에 작성한 웹은 동기 (새로고침 요구), 작업을 요청하는 클라이언트와 처리하는 서버의 동기화 => 대기(클라이언트)
- 비동기 : 클라이언트가 서버에게 작업을 요청한 후 다른 작업을 처리, 작업 완료시 해야할 일만 등록(이벤트 헨들러)
    * 대신 동기는 직관적이고, 디버깅 쉬움 반면 비동기는 디버깅 어렵고 비직관적임 (순차냐 분할 후 합체냐)
- AJAX : 비동기 자바스크립트와 XML, Asynchronous javaScripts And XML
    * 자바스크립트를 통해 서버에 비동기로 요청하는 것
    * XML 말고 JSON 사용해도 무관, 현재는 더 많음
    * 검색에 자동완성,
    * 회원가입 페이지를 새로 띄우지 않으면서 아이디 중복 검사,
    * 인스타그램에서 스크롤을 내리는 것만으로 다음 목록을 불러오는 것 
    * (더 나은 사용자 경험을 제공하기 위해 사용한다.)
 

  
