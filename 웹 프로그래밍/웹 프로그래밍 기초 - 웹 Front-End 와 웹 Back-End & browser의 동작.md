## 웹 프론트엔드란?
* 사용자에게 웹을 통해 다양한 콘텐츠를 제공하는 역할 -> 사용자의 요구사항에 반응하여 동작

### 웹 프론트엔드 역할
* HTML: 웹 콘텐츠를 보여주기 위한 구조를 만들어야함
* CSS: 적절한 배치와 일관된 디자인을 제공해야 함
* Javascript: 사용자의 요구사항을 반영해야 함

## 백엔드란?
* 정보를 처리하고 저장하며, 요청에 따라 정보를 내려주는 역할

## browser의 동작1
* html 파싱(문자 단위로 해석을 해서 의미 파악하는 과정) 
* 일종의 트리 구조 형태로 데이터를 가지고 있게 됨
* 렌더 트리를 기준으로 css를 합침 -> 구조와 스타일 정보를 합쳐서 매칭 함
* 모든 것이 결정이 되면 웹 페이지에 직접 그림을 그리게 됨

## browser의 동작2
* ex. 사파리 브라우저에서 처리되는 webkit 렌더링 엔진의 처리과정

![캡처](https://user-images.githubusercontent.com/23302973/98339748-90df7180-204f-11eb-98b0-efbfa483a828.PNG)

[출처](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)

* HTML을 해석해서 DOM Tree 만들고, CSS를 해석해서 CSS Tree를 만든다. -> 파싱 필요
* DOM Tree 와 CSS Tree는 연관되어 있으므로 Render Tree로 조합된다.
* 조합된 결과는 화면에 어떻게 배치할지 크기와 위치 정보를 담고 있다.
* Render Tree 정보를 통해 화면에 어떤 부분에 어떻게 색칠할지 그리는 과정을 거친다.
