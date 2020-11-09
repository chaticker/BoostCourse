## css 선언방법

* css 우선순위: inline > internal = external / Id > Class > element

## css selector

* HTML의 요소를 tag, id, html 태그 속성 등을 통해 쉽게 찾아주는 방법

```html
//tag로 지정
<style>
     span {
       color : red;
     }
 </style>
 
 //id로 지정
 <style>
     #spantag {
       color : red;
     }
</style>

<body>
     <span id="spantag"> HELLO World! </span>
</body>

 //class로 지정
 <style>
     .spanClass {
     color : red
     }
</style>

<body>
     <span class="spanClass"> HELLO World! </span>
</body>
```

## css 기본 스타일 변경

* font 색상 변경
     - color : red;
     - color : rgba(255, 0, 0, 0.5);
     - color : #ff0000;   //16진수 표기법으로 가장 많이 사용되는 방법이죠.
 
* font 사이즈 변경
     - font-size : 16px;
     - font-size : 1em;
 
* 배경색 
     - background-color : #ff0;
     - background-image, position, repeat 등의 속성이 있습니다.
     - background : #0000ff url(“.../gif”) no-repeat center top; //한 줄로 정의도 가능

* 글씨체/글꼴
     - font-family:"Gulim";
     - font-family : monospace;

## element가 배치되는 방법(css layout)

* block
* inline
* position: static
     - 순서대로 배치
* position: relative
     - 원래 자신이 위치해야 할 곳을 기준으로 이동 - top, left, right, bottom으로 설정
* position: absolute
     - 기준점을 상위 element로 단계적으로 찾아감 - static이 아닌 position이 기준점
* position: fixed
     - 전체화면의 좌측, 맨 위를 기준으로 동작
