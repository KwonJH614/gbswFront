# body 주요 태그 - 멀티미디어 파일 삽입
## ```<object>```
* data 속성에 오디오, 비디오, PDF 등 다양한 멀티미디어 파일을 삽입하는 태그이다

## ```<embed>```
* src 속성에 멑티미디어 파일을 지정하여 삽입하는 태그이며, 닫는 태그가 없다

## ```<video>```
* HTML4까지는 웹 페이지에 영상을 띄우기 위해 별도의 프로그램을 설치하는 등 절차가 복잡했다
* HTML5에서 video 태그의 등장으로 영상을 띄우는게 간편해졌다

## ```<audio>```
* 웹 페이지에서 플러그인의 도움 없이 오디오를 재생시킬 수 있는 태그이다

## \<audio> 와 \<video> 태그의 속성
<table>
    <tbody>
    <tr>
      <th> 종류 </th>
      <th> 설명 </th>
    </tr>
    <tr>
      <td>controls</td>
      <td>화면에 컨트롤 바 표시</td>
    </tr>
    <tr>
      <td>autoplay</td>
      <td>자동 재생</td>
    </tr>
    <tr>
      <td>loop</td>
      <td>반복 재생</td>
    </tr>
    <tr>
      <td>muted</td>
      <td>음소거</td>
    </tr>
    <tr>
      <td>preload</td>
      <td>비디오 파일이 같이 로드되어야 하는지 여부(auto, metadata, none)</td>
    </tr>
    <tr>
      <td>width, height</td>
      <td>비디오 화면 너비, 높이 지정</td>
    </tr>
    <tr>
      <td>poster=”파일명”</td>
      <td>비디오 재생 전, 화면에 표시될 이미지 지정</td>
    </tr>
  </tbody>
</table>

## ```<a>```
* 하이퍼링크 설정 태그 

<table>
  <tbody>
    <tr>
      <th>속성</th>
      <th>설명</th>
      <th>주요 값</th>
    </tr>
    <tr>
      <td>href</td>
      <td>하이퍼링크 URL</td>
      <td>URL, tel:010-1234-5678, madogkwon@gmail.com</td>
    </tr>
    <tr>
      <td>target</td>
      <td>URL 이동 방법 지정</td>
      <td>_self : 현재 브라우저에 띄움<br>_blank : 새로운 탭에 띄움</td>
    </tr>
  </tbody>
</table>

## ```<img>``` <br>
* 이미지를 삽입하는 태그이다
* src - 이미지 파일이 저장된 주소를 명시한다
* alt - 이미지를 로딩할 수 없을 때, 이미지 대신 나타날 문자열이다

``` <img src="./dog.png" alt = "닥스훈트">```

### 절대 경로와 상대 경로
* 절대경로 - 파일의 root 부터 해당 파일까지의 전체 경로이다 <br>
``` ex) C:\Users\user\사진\image.png```

* 상대경로 - 현재 파일의 위치부터 해당 파일까지의 상대적인 경로이다<br>
``` ex) ../img/image.png(../ => 상위 폴더로 이동)```

### 이미지 크기 표현 단위
* ```%``` - 현재 웹 브라우저 창의 크기에 비례하여 이미지의 크기를 조정한다
* ```px``` - 창의 크기와 관계없이 픽셀 크기만큼 이미지의 크기를 고정한다

* ### [멀티미디어 사용 예시](./MultiMidiaEx.html)