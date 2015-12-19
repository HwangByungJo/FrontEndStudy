## 각 언어별 Load Map
> **모든 스터디에는 *sample 예제* 가 있어야 한다.**

=
### javascript 실무 - 10월 18일 수정
#### - 분량 나누기(11월 14일 발표 분량) -
- 매주 일요일 밤 10~11시 정기 후기 회의 진행 결정
- 4주차는 3주차 문서에 대한 정리 및 발표 준비

**동기 vs 비동기 통신 (1주차-10/19~25)**

* 차이점    
* 정의 및 특징   
  
**실무에 자주 쓰이는 함수**    

* 타이머함수 __(1주차-10/19~25)__

    - setTimeout(function,millisecond)
    - setInterval(function,millisecond)clearTimeout(id)
    - clearINterval(id)
    - __setTimeout과 setInterval의 차이점__ (중요함)
    
* 인코딩/디코딩 함수escape() / unescape() __(2주차-10/26~11/1)__

    - encodeURI(url) / decodeURI(encodeURI)
    - encodeURIComponent(uriComponent) / decodeURIComponent(encodedURI)
    
* 코드 실행 함수 __(2주차-10/26~11/1)__

    - eval(String)
    
* 숫자 확인 함수 __(3주차-11/2~8)__

    - isFinite()
    - isNaN()
    - cast 함수
    - parseInt(String)
    - parseFloat(String)
    - String(number)
    - Number(String)
    - Boolean(String)
    
* 기타 __(3주차-11/2~8)__

    - typeof()
    - confirm(String)
    - prompt(String)
    
**scope**

* 정의 및 특징 - 반응형 할 시 필수로 알아야 할 개념        
  혹시나 모르실 듯 하여 좋은 블로그 하나 보내드립니다. 이걸 중심으로 스터디 하시면 됩니다    
  [http://www.nextree.co.kr/p7363/](http://www.nextree.co.kr/p7363/)

**사용자 정의 함수**

* 정의 및 정의 방법    
  (앞의 로드맵을 모두 스터디 하면 최종적으로 이 부분으로 도달 할 겁니다. 깊이 파고들면 복잡하므로 이러한방법이 있다라는 정도만 스터디 진행하고 완료할 것.)
    * 사용자 정의 함수 - [http://spongi.tistory.com/33](http://spongi.tistory.com/33)
    * 사용자 정의 객체 - [https://opentutorials.org/course/49/2912](https://opentutorials.org/course/49/2912)
    * 사용자 정의 이벤트 - [http://sean86.tistory.com/10](http://sean86.tistory.com/10)
    
* 향후 심화 과정으로 그룹 스터디 진행합니다~

** web socket **

  HTML5 스터디하면 할까 하다 Javascript 실무에서 많이 쓰이다 보니 여기서 스터디 하겠습니다.
* HTML5에서 추가로 도입한 Socket 통신 방법(javascript로 코딩)
* 개념 및 기초
  https://www.websocket.org/ , http://html5korea.com/%EC%9B%B9%EC%86%8C%EC%BC%93websocket-%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0%EA%B0%95%EC%9D%98%EB%B2%88%EC%97%AD/ 를 바탕으로 스터디함

** web worker **

 HTML5 스터디하면 할까 하다 Javascript 실무에서 많이 쓰이다 보니 여기서 스터디 하겠습니다.
 http://www.w3schools.com/html/html5_webworkers.asp 를 바당으로 스터디 할 것

=
### JQuery 실무

**특징(tutorial) 및 자주 쓰이는 함수**

  - [http://api.jquery.com/](http://api.jquery.com/) 을 참고.

**크게 3종류의 API가 있습니다.**   

  - JQuery API(공통 API)
  - JQuery UI API(UI 플러그인 관련) -  
  이걸 때셔야 플러그인 조사하실 때 쉽게 소스 분석할 수 있습니다.
  - JQuery Mobile API(모바일 UI 플러그인 관련)  
  반응형 / 모바일 웹 관련 API (최근에 나온거라 저도 안해봤음. 추후 따로 빼서 스터디 그룹하면 좋을듯)

**QUnit API (Jquery 단위 Test 관련 API)** - 중요하진 않으나 추후 스터디 고려는 할 수 있음

**Jquery Plugin**

- 오픈 소스용 또는 상용 버전의 Plugin들을 조사한다.    
  [http://plugins.jquery.com/](http://plugins.jquery.com/) 을 참조하여 조사함
    - 그래프(차트), 테이블(grid), datepicker, colorpicker, tree, multiselect 등의 UI 관련 plugin
    - Upload / downlaod 등의 ajax 관련 plugin
    - animation plugin
    - slider / responsive 관련 plugin 등
   
=
### Bootstrap 실무

* 핵심기능 위주 레퍼런스 정리
	- Bootstrap CSS
 		- grid system
 		- container
	- Bootstrap component   
    	- panel
    	- list group
	- Bootstrap Javascript
		- collapse
		- modal
	- 참고사이트
		- [http://getbootstrap.com/css/](http://getbootstrap.com/css/)    
	    - [http://bootstrapk.com/css/](http://bootstrapk.com/css/)

* 레퍼런스 정리 전 기초적으로 시작하기 부분은 각자 숙지 
	- 시작하기(tutorial)    
	    - [http://getbootstrap.com/getting-started/](http://getbootstrap.com/getting-started/)
	    - [http://bootstrapk.com/getting-started/](http://bootstrapk.com/getting-started/)

* 예제사이트 조사 & 카피 (추후 자세한 내용 확정 예정)
	- Bootstrap Theme
	    - [http://themes.getbootstrap.com/](http://themes.getbootstrap.com/)
	- Bootstrap 4
	    - [http://blog.getbootstrap.com/2015/08/19/bootstrap-4-alpha/](http://blog.getbootstrap.com/2015/08/19/bootstrap-4-alpha/)    
	    (새롭게 출시되는 4버전)



    
=
### Angular JS

* 교제 선정 및 그것을 중심으로 스터디 진행.
* 10/15(목)에 교제 선정 완료 및 로드맵 진행.
* 교제 선정 완료.
  - 프로 Angular JS
  - [http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788994774879&orderClick=LEA&Kc=](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788994774879&orderClick=LEA&Kc=)
* 스터디 진행 순서
  - Chapter 1에 나와있는 개발환경 세팅에 대한 실습 진행(node.js를 이용한 Connect 설치 및 구동 확인)
  - MVC 패턴에 대한 이해
  - RESTful 서비스 이해
  - 그 외 AngularJS 이해와 관련된 내용
  - Chapter6 ~ 8 까지는 빠르게 진행(한 타임에 다 하는 방향으로)
  - 그 후 중요한 사항 5가지를 놓고 각자 맡아서 진행할 계획
    - 탬플릿
    - 컨트롤러
    - 필터
    - 디렉티브
    - 뷰어
* 스터디 진행기간은 대략 4~5개월정도 예상  
_위 로드맵은 그런트 실습 후 다시 미팅을 할 것이며 Chapter 6 이후에 대한 부분은 중간에 수정될 수 있음_

=
### SASS 
* SASS 설치 및 설정 및 변환 방법
* SASS 기초(Tutorial)
 http://sass-guidelin.es/ko/#section-6 ,  http://sass-lang.com/guide 를 참고하여 스터디 
 - Preprocessing
 - Variables
 - Nesting
 - Partials
 - Import
 - Mixins
 - Inheritance
 - Operators
 - 조건문 `@if, @else if, @else`
 - 반복문
 - 경고와 오류
 - [Sass scripting](http://sass-lang.com/documentation/file.SASS_REFERENCE.html#sassscript):
    - '!global'
    - 보간법 `#{$selector}`

=
### postcss
 - https://github.com/postcss/postcss 를 참고로하여 스터디



#### [PostCSS Benchmarks](https://github.com/postcss/benchmark)

```sh
PostCSS:   61 ms
Rework:    72 ms   (1.2 times slower)
libsass:   129 ms  (2.1 times slower)
Less:      152 ms  (2.5 times slower)
Stylus:    161 ms  (2.6 times slower)
Stylecow:  171 ms  (2.8 times slower)
Ruby Sass: 1042 ms (17.0 times slower)
```

=

* [FrontEndStudy](../../../../)