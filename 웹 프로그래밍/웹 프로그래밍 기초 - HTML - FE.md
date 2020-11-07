## HTML Tags

* 레이아웃을 위한 태그
  - header
  - section
  - nav
  - footer
  - aside
  
![캡처](https://user-images.githubusercontent.com/23302973/98446624-0cc9de80-2162-11eb-8e7e-5b2b6a66f568.PNG)

## class 와 id 속성

* ID
  - 고유한 속성으로 한 HTML 문서에 하나만 사용 가능
  - 고유한 ID 값이 있으면 하나하나에 특별한 제어를 할 수 있으며 검색에도 용이

* Class
  - 하나의 HTML문서 안에 중복해서 사용 가능
  - 하나의 태그에 여러 개의 다른 class 이름을 공백을 기준으로 나열할 수가 있음
  - 홈페이지 전체적인 스타일을 일관성 있게 지정하기 위해서는 class의 사용이 필수적
  
## CSS 선언방법

```python
span {
  color : red;
  }
```

* span : selector(선택자)
* color : property
* red : value

* style을 HTML페이지에 적용하는 3가지 방법
  - inline: HTML 태그 안에 적용(다른 CSS 파일에 적용한 것보다 가장 먼저 적용됨)
  - internal: style 태그로 지정(유지보수 어려움)
  - external: 외부 파일로 지정(코드가 길면 길수록 이 방법으로 구현하는 것이 좋음)
