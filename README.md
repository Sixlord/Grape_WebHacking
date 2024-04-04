# Grape_WebHacking





### Broken Access Control Vulnerability

→ 손상된 접근제어

: 로그인과 같이 특정 기능을 정해진 유저만 수행할 수 있도록 제한하는 것을 **접근제어**라고 부른다.

특정 취약점은 접근제어를 손상시킨다. 정해지지 않은 유저도, 해당 기능에 접근할 수 있게 된다.

ex) 엔드포인트 접근 손상 : 로그인 안하고 url 이용해서 해당 엔드포인트에 접근 → 쿠키로 사용자 식별하도록 수정

### 취약점 악용(exploit)

### 취약점 패치(patch)

: 취약점을 고침, 보안 패치

### Mitigation(완화)

: 취약점을 수정하여 보안을 강화하는 것

### Cookie

: 서버가 브라우저에 저장하도록 명령할 수 있는 변수 기능

→ 서버의 php에서 변수에 값을 지정하면 서버 컴퓨터에 저장됨

→ 서버의 php에서 쿠키에 값을 지정하면 브라우저(클라이언트)에 저장됨

### Cookie Poisoing

: Client-Side에서 Cookie를 조작하는 해킹기법 

### Bypass

: 보안시스템을 우회하는 것 

### Request / Response

: 브라우저가 보낸 것은 Request(요청)

: 서버가 보낸 것은 Response(응답)

### Method

: 가장 앞에 나오는 POST 

### Payload(Data)

: method가 post일 때, 맨 아래에 붙는 보낼 첨부파일이나 텍스트 

### 상태코드 (status code)

→ 200 : Request 잘 받음, 요청한 파일 찾음

→ 404 : Request 잘 받음, 요청한 파일 못찾음

### Brute Force Attack

: 무차별 대입 공격 

### Buster

: 파괴자, 해체자. 암호를 부수는 프로그램이나 해킹툴 

### SQL Injection

: 쿼리문을 조작하여 해킹하는 수법

→ 쿼리에 주석을 삽입하여 조작함

⇒ 입력값 검사 (Input Validation / Input Sanitization) : 주석기호를 찾아서 없애버리면 방어 가능, 특정 문자열을 찾아 다른 문자열(빈 문자열)로 바꾸는 함수를 사용할 수 있음.
