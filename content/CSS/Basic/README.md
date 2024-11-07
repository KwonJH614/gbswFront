# CSS 기본

### 웹 문서에 디자인 입히기
* 스타일 (style) : HTML 요소의 시각적 표현을 정의하는 규칙이다
* 스타일 사용 이유
    * 웹 문서의 내용과 상관없이 디자인만 바꿀 수 있음
    * 다양한 기기에 맞게 바뀌는 문서 작성이 가능해진다 ( 반응형 웹페이지 )

### 스타일과 스타일 시트
* 스타일 시트 : 스타일 규칙을 한 군데 묶어놓은 것
* 우선순위 : 인라인 스타일 > 내부 스타일 시트 > 외부 스타일 시트

### 인라인 스타일
* 스타일을 적용할 대상에 직접 작성한다
```
<h1 sytle="color: red;"> This is Test </h1>
```
### 내부 스타일 시트
* 사용할 스타일을 같은 문서 안에 정리한다
* \<head>태그 안 \<style> \</style> 사이에 작성한다
```
<head>
  <style>
  h1 {
    color : red;
  }
  </style>
</head>
<body>
<h1>This is test<h1>
<body>
```

### 외부 스타일 시트 
* .css 파일을 별도로 생성하고 불러와서 사용한다

#### test.html
```
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <style>
  <link rel = "stylesheet" href="./test.css">
</head>
<body>
<h1>This is test<h1>
<body>
```

#### test.css
``` css
h1 {
    color : red;
}
```

### 스타일 상속
* 특정 요소가 부모 요소로부터 스타일을 물려받는것을 말한다
* 기본적으로 텍스트 관련 속성( 예 :  ```color```, ```font-family``` )은 자식 요소에 상속되지만 레이아웃 관련 속성 ( 예 : ```margin```, `width`, ```height``` )은 상속되지 않는다

* 상속되지 않는 속성도 ```inherit``` 키워드를 사용해 명시적으로 사용할 수 있다
``` css
  div {
    width: 200px;
    background-color: lightblue;
  }
  p {
    width: inherit;
    background-color: inherit;
  }
```