# CSS - 반응형 웹과 미디어 쿼리

## 반응형 웹이란 ?
* 웹 사이트의 내용을 그대로 유지하면서 화면크기에 맞게 웹 사이트를 변형하는 방법이다
* 다양한 화면크기의 기기들에 맞춰서 웹 사이트를 제작하는 것은 비효율적 -> 화면 크기에 반응해 화면 요소를 자동으로 바꾸는 것이 
반응형 웹 디자인이다

## 적응형 웹과 반응형 웹
* 적응형 웹 : 사용자의 기기에 따라 다른 페이지를 반환한다
    * 모바일 환경에서 naver.com 접속시 자동으로 m.naver.com으로 접속된다

<br>

* 반응형 웹 : 동일한 웹 페이지를 화면 사이즈에 따라 다르게 반환한다
    * https://school.gyo6.net/gbsw/main.do 에 접속 후 브라우저 사이즈를 변경하면 크기에 맞춰 다르게 보여진다

### 미디어 쿼리
``` css
@media [ only  |  not ] 미디어 유형 [ and 미디어 조건 ] … { CSS 요소 }
```
* `@media`로 사용 가능하다
    * 미디어 조건
        * `width, height` : 웹 페이지의 가로너비, 세로 높이
        * `min-width, min-height` : 웹 페이지의 최소 너비, 최소 높이
        * `max-width, max-height` : 웹 페이지의 최대 너비, 최대 높이
        * `device-width, device-height` : 디바이스의 물리적 너비, 높이 (단위 : px)
        * `orientation` : 디바이스 방향 (가로 방향 - landscape / 세로 방향 - portrait)

* ### [media query 사용예시](./MediaQuery.html)