# eat-my-combi
내 조합 먹어조(조별과제): 편의점 음식 조합 추천 서비스

프로덕션 브랜치 CICD 연동 웹페이지  
https://eatmycombi.ritchko.com

<br>

## 개발환경 구축하기
모든 커맨드 명령은 git bash(vs code 터미널) 또는 cmd(powershell 아님! 권한오류 남)에서 실행하세요!  

### 1. 코드(git) 가져오기
최초 1회
1. VSCode 열고 터미널 ```ctrl + ` ``` 실행, git bash 환경으로 설정
2. 원하는 폴더에서 ```git clone https://github.com/xeon-lloyd/eat-my-combi``` 실행해서 코드 가져오기
3. ```cd eat-my-combi```로 eat-my-combi 폴더로 이동한다음  
```git checkout -t origin/develop```로 develop 브랜치로 체크아웃


### 2. 실행 환경 만들기
최초 1회  
※ nodejs와 npm이 설치되어야 함  

nodemon을 통한 개발환경 실행  
1. ```npm install```으로 서버 실행에 필요한 모듈 설치
2. ```npm install -g nodemon```로 nodemon npm 설치
3. eat-my-combi 폴더에서 ```nodemon server.js``` 실행
4. http://localhost:80 포트로 접속하여 결과 확인
5. 이후 코드를 수정할때마다 수정사항이 반영되어 서버가 재시작 됨


### 3. 앞으로 어떻게 해야하는가
production과 develop에는 직접 push하지 못하도록 브랜치가 잠겨있음.  
새로운 작업을 할때는 아래의 순서를 따름.  
1. 로컬에서 ```develop```브랜치를 기준으로 새로운 브랜치 만들기 *(브랜치 이름은 기능 단위로!)*
2. 생성한 브랜치에서 작업 후 commit/push  
3. github에서 로컬에서 생성(작업)한 브랜치가 올라와있음
4. Pull Request에서 ```new pull request```를 통해서 ```develop <- 생성한 브랜치```로 새 pull request 생성  
이때 우측 Reviewers를 클릭하여 관련된 사람 추가하기
5. 팀원의 코드리뷰 이후 develop으로 merge되면 다른 팀원들은 각자 pull 실행하기


## 기록
### 2024-03-26
github 개념(브랜치) 설명 및 구조 공유  
github를 통한 작업방식(PR) 익히기 *(연습)*  
피그마를 통한 레이아웃 설계 *(메인페이지, 레시피 상세페이지)*  https://www.figma.com/file/kubLhZfdPbm9AT0eplNyLW/%EB%82%B4-%EC%A1%B0%ED%95%A9-%EB%A8%B9%EC%96%B4%EC%A1%B0  


### 2024-03-19
작품 기술서 작성 및 제출  
사이트 레이아웃(필요 페이지) 브레인스토밍 및 러프 작성  

