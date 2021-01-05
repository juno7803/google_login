## Cookie Parking : 쿠키파킹의 귀염탱, WEB
---
###  프로젝트 구조

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

### 기술 스택 및 라이브러리

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

### 쿠키파킹의 웹둥이들 🥰

| **🙋 [이준호](https://github.com/juno7803)** | **🙋‍ [이정민](https://github.com/danmin20)** | **🙋‍ [이현진](https://github.com/junyup0319)** |**🙋‍ [안채린](https://github.com/achrvv)** | **🙋‍ [천주윤](https://github.com/ewq3167)** |
| :---: |:---:| :---:| :---:| :---:|
| ![준호사진]() | ![정민사진]()  | ![현진사진]() | ![채린사진]() | ![주윤사진]()
| 웹 개발자 | 웹 개발자| 웹 개발자| 웹 개발자| 웹 개발자|
|rdb설계  <br /> 배포 환경 구축 <br /> 회원가입, 로그인 <br /> 그룹 인증 관리 <br /> 그룹 리스트 조회  <br />|rdb설계 <br /> 배포 환경 구축 <br /> place 업로드 <br /> 지하철 API <br /> 네이버 지도 API |rdb설계 <br /> 배포 환경 구축 <br /> 장소 검색 필터링 <br /> 장소 검색 API <br /> 장소 검색 sorting|

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
