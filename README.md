# eat-my-combi
내 조합 먹어조(조별과제): 편의점 음식 조합 추천 서비스

<br>

## 개발환경 구축하기
모든 커맨드 명령은 cmd(powershell 아님! 권한오류 남)에서 실행하세요!  

### 1. 코드(git) 가져오기
최초 1회
1. 원하는 폴더에서 ```git clone https://github.com/xeon-lloyd/eat-my-combi```
2. ```cd eat-my-combi```로 eat-my-combi 폴더로 이동한다음 ```git checkout -t origin/develop```로 develop 브랜치로 체크아웃
3. VSCode에 eat-my-combi 폴더를 열어서 코드 수정 환경 만들기

### 2. 실행 환경 만들기
최초 1회  
※ nodejs와 npm이 설치되어야 함  

nodemon을 통한 개발환경 실행  
1. ```npm install```으로 필요한 모듈 설치
2. ```npm install -g nodemon```로 nodemon npm 설치
3. eat-my-combi 폴더에서 ```nodemon server.js``` 실행
4. http://localhost:80 포트로 접속하여 결과 확인
5. 이후 코드를 수정할때마다 수정사항이 반영되어 서버가 재시작 됨


## 기록
### 2024-03-19
작품 기술서 작성 및 제출  
사이트 레이아웃(필요 페이지) 브레인스토밍 및 러프 작성  