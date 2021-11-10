# Starbucks Hompage Clone Page 
## 스타벅스 홈페이지 클론 코딩 페이지

아래의 사이트를 참고하여 만들었습니다.  
> [박영웅님의 스타벅스 랜딩 페이지(+로그인) 예제](https://github.com/ParkYoungWoong/starbucks-vanilla-app)

메인 페이지와 로그인 페이지의 동일하게 쓰이는 .css와 .js는 각 common 파일에 넣었습니다. 
***

추가한 CSS 자료
---
[Reset.css](https://fonts.google.com/)
  - 브라우저의 기본 스타일을 초기화합니다.
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.1/reset.min.css" />
  ```
[Google Fonts](https://fonts.google.com/) 
  - 폰트 라이선스를 확인 후 파일을 가져옵니다.

[Google Material Icons](https://fonts.google.com/icons?selected=Material+Icons)
  - 구글에서 제공하는 무료 머터리얼 아이콘입니다.
  - [Google Marerial Icons 사용 방법](https://material.io/develop/web/getting-started)
***
추가한 JavaScript 라이브러리
---
[lodash](https://cdnjs.com/libraries/lodash.js)
  - JavaScript에서 배열 안의 객체들의 값을 핸들링 할때 유용합니다. (다양한 유틸리티 기능을 제공)
  - `forEach()`, `find()`...

[gsap & ScrollToPlugin](https://cdnjs.com/libraries/gsap) 
  - JavaScript로 제어하는 타임라인 기반의 애니메이션 라이브러리입니다. ScrollToPlugin은 스크롤 애니메이션을 지원하는 GSAP 플러그인입니다.
  - `gsap.to(요소, 시간, 옵션)`

[Swiper](https://swiperjs.com/)
  - 하드웨어 가속 전환과 여러 기본 동작을 갖춘 슬라이드 라이브러리입니다. 
  - [Swiper 사용 방법](https://swiperjs.com/get-started)

[Scroll Magic](http://scrollmagic.io/docs/)
  - 스크롤과 요소의 상호 작용을 위한 자바스크립트 라이브러리입니다.

[Youtube API](https://developers.google.com/youtube/iframe_api_reference?hl=ko) 
  -  YouTube 동영상을 제어할 수 있습니다.
  - `onYouYubePlayerAPIReady` 함수 이름이 다르면 동작하지 않습니다.
