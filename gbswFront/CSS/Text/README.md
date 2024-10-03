# CSS 텍스트 스타일

### 텍스트 스타일
* `font-family`, `font-size`, `font-weight`로 폰트를 설정한다. 
```css
h1 {
    font-family: Arial, sans-serif;
    font-size: 24px;
    font-weight: bold;
}
```
* `text-align`으로 정렬하고, `line-height`로 줄 간격을 조정한다. 
```css
p {
    text-align: center;
    line-height: 1.5;
}
```

### 목록 스타일
* `list-style-type`으로 목록 스타일을 지정한다. 
```css
ul {
    list-style-type: square;
}
```
* `list-style-position`으로 아이템의 위치를 조정한다.

### 표 스타일
* `border`로 경계를 설정하고, `padding`, `text-align`으로 셀 내용을 조정한다. 
```css
table {
    border: 1px solid black;
    padding: 8px;
    text-align: left;
}
```
* `border-collapse`로 테이블 경계를 합친다.
```css
table {
    border-collapse: collapse;
}
```