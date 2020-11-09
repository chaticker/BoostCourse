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
