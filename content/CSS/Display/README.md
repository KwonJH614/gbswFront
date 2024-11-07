# CSS - 요소 배치

* #### `display` : 블록 레벨 요소, 인라인 레벨 요소를 바꿀 때 사용한다
  * `block` : 인라인 요소를 블록 요소로 바꾼다(요소 앞 뒤로 줄바꿈 적용)
  * `inline` : 블록 요소를 인라인 요소로 바꾼다(요소 앞 뒤로 줄바꿈 적용 X)
  * `inline-block` : 인라인, 블록 요소의 속성을 모두 가지고 있으며 마진, 패딩을 지정 할 수 있다
  * `none` : 해당 요소를 화면에 표시하지 않기 때문에 공간도 차지하지 않는다
```css
body {
  display : block  |  inline  |  inline-block  |  none ;
}
```

* #### `float` : 이미지를 어떻게 띄워서 텍스트와 함께 배치할 것인가에 대한 속성이다
  * `left` : 왼쪽에 정렬시키며, 페이지 내용은 박스 오른쪽에 위치한다
  * `right` : 오른쪽에 정렬시키며, 페이지 내용은 박스 오른쪽에 위치한다
  * `none` : 정렬시키지 않는다
```css
body {
  float : left | right | none;
}
```

* #### `clear` : float의 흐름을 제거하기 위해 사용한다
  * `none` : 아래로 이동되지 않는다
  * `left` : 요소가 left를 해제하기 위해 아래로 이동한다
  * `right` : 요소가 right를 해제하기 위해 아래로 이동한다
  * `both` : 요소가 left 및 right 를 해제하기 위해 아래로 이동한다
```css
body {
  clear : left  |  right  |  both ;
}
```

* #### `position` : 웹 문서 내 요소를 배치하는 방법을 지정한다
  * 정적 위치 지정 방식(static)
    * 요소를 일반적인 문서 흐름에 따라 배치하고, 위치를 지정할 수 없다
  * 상대 위치 지정 방식(relative)
    * 요소를 일반적인 문서 흐름에 따라 배치하고, 위치를 지정할 수 있다
  * 절대 위치 지정 방식(absolute)
    * 요소를 일반적인 문서 흐름에서 제거하고, 페이지 레이아웃에 공간도 차지하지 않는다
    * 가장 가까운 위치 지정 조상 요소에 대해 상대적으로 배치한다
  * 고정 위치 지정 방식(fixed)
    * 요소를 일반적인 문서 흐름에서 제거하고, 페이지 레이아웃에 공간도 차지하지 않는다
    * 스크롤해도 움직이지 않는다

* ### [dispaly 사용예시](./Display.html)
* ### [float 사용예시](./Float.html)