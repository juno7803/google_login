###  프로젝트 폴더 구조 설명

```
📦 src
 ┣ 📂 assets
 ┃ ┣ 📂 img
 ┃ ┗ 📂 themes
 ┃ ┃ ┗ 📜 index.js
 ┣ 📂 pages
 ┃ ┣ 📂 Background
 ┃ ┃ ┣ 📜 index.html
 ┃ ┃ ┗ 📜 index.js
 ┃ ┣ 📂 Newtab
 ┃ ┃ ┣ 📜 index.html
 ┃ ┃ ┣ 📜 index.css
 ┃ ┃ ┣ 📜 index.js
 ┃ ┃ ┣ 📜 App.js
 ┃ ┃ ┗ 📜 Newtab.js
 ┃ ┗ 📂 Popup
 ┃ ┃ ┣ 📜 index.html
 ┃ ┃ ┣ 📜 App.js
 ┃ ┃ ┣ 📜 index.js
 ┃ ┃ ┣ 📜 Loading.js
 ┃ ┃ ┣ 📜 index.css
 ┃ ┃ ┣ 📜 AddDir.js
 ┃ ┃ ┣ 📜 Directory.js
 ┃ ┃ ┣ 📜 Finish.js
 ┃ ┃ ┣ 📜 Main.js
 ┃ ┃ ┣ 📜 Popup.js
 ┃ ┃ ┗ 📜 Login.js
 ┣ 📂 components
 ┃ ┣ 📜 Directory.js
 ┃ ┣ 📜 AllCookies.js
 ┃ ┣ 📜 CardHover.js
 ┃ ┣ 📜 Card.js
 ┃ ┣ 📜 DirCard.js
 ┃ ┣ 📜 Switch.js
 ┃ ┗ 📜 ToastMsg.js
 ┣ 📂 hooks
 ┃ ┗ 📜 useInput.js
 ┣ 📂 lib
 ┃ ┗ 📂 api
 ┃ ┃ ┣ 📜 cookieApi.js
 ┃ ┃ ┗ 📜 directoryApi.js
 ┣ 📂 states
 ┃ ┗ 📜 atom.js
 ┗ 📜 manifest.json
```

### 선택한 기술 스택 및 사용 라이브러리

```
React
JavaScript es6
axios
recoil
react-google-login
styled-components
material-ui
webpack
```

### 팀원 역할 분담

- 안채린
    - 상세 디렉토리 리스트 구현
    - 프로젝트 세팅 선 구현
- 이정민
    - 프로젝트 세팅 (웹팩, 린트 등) 및 관리
    - 랜딩 페이지 제작
    - 리팩토링 및 전체적인 코드 리뷰

- 이준호
    - 전체적인 newtab extension 구현
    - directory 상세 페이지 web 구현

- 이현진
    - popup 부분 퍼블리싱 및 서버 연동
    - 웹클리퍼 기능 구현(url, og태그, favicon, author 정보 데이터 가져오기)
    - 구글 로그인 연동

- 천주윤
    - Card 컴포넌트 구현
