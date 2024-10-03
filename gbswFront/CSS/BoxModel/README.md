# CSS 박스 모델

### 박스 모델
* 모든 HTML 요소는 박스 형태로 구성된다. 
* 박스 모델은 `content`, `padding`, `border`, `margin`으로 이루어져 있다.

### 요소 크기
* `width`, `height`로 요소의 크기를 조정한다. 
* `box-sizing` 속성을 사용하면 요소의 크기를 포함하는 방식이 달라진다.
```css
/* 기본 box-sizing 설정 */
* {
    box-sizing: border-box;
}
```

### 여백과 테두리
* `margin`은 요소 외부의 여백을 설정한다. 
* `padding`은 요소 내부의 여백을 설정한다. 
```css
.box {
    margin: 20px;
    padding: 10px;
}
```
* `border` 속성으로 테두리를 설정할 수 있다. 
```css
.box {
    border: 2px solid black;
}
```

### 박스 모델 시각화
* `outline` 속성으로 요소의 외곽선을 추가할 수 있다. 
* `display` 속성으로 요소의 박스 유형을 설정한다.
```css
.box {
    outline: 2px dashed red;
    display: inline-block; /* 블록 또는 인라인 블록으로 설정 */
}
```

* ### [박스모델 사용 예시](./BoxModel.html)