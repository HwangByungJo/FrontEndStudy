# column-rule-style

작성자 : 김동일

작성일 : 2015-09-17

css 레퍼런스 설명:
 - column-rule-style : column간의 스타일를 명시 한다.

 - syntax :
```sh
column-rule-style: none|hidden|dotted|dashed|solid|double|groove|ridge|inset|outset|initial|inherit;
```

none : 기본 값, 아무것도 적용하지 않는다.

hidden : column간 스타일을 숨긴다.

dotted : column간 스타일 짧은 점선으로 설정

dashed : column간 스타일 긴 점선으로 설정

solid : column간 스타일 선으로 설정

double : column간 스타일 두 선으로 설정

groove : column간 스타일에 groove가 들어간 3D선으로 설정. width와 색상에 영향을 받음

ridge :column간 스타일에 ridge가 들어간 3D선으로 설정. width와 색상에 영향을 받음

inset : column간 스타일에 inset가 들어간 3D선으로 설정. width와 색상에 영향을 받음

outset : column간 스타일에 outset가 들어간 3D선으로 설정. width와 색상에 영향을 받음

initial:기본 값으로 set되어 있는 값을 불러온다.

inherit:부모 element에 설정되어 있는 값을 상속 받는다.

sample code :
```html
<!DOCTYPE html>
<html>
<head>
<style>
.newspaper {
    /* Chrome, Safari, Opera에서 사용하는 css (반드시 앞에 -webkit-을 붙여야함)*/
    -webkit-column-count: 3;
    -webkit-column-gap: 40px;
    -webkit-column-rule-style: dotted;

    /* Firefox 에서 사용하는 css (반드시 앞에 -moz-을 붙여야함)*/
    -moz-column-count: 3;
    -moz-column-gap: 40px;
    -moz-column-rule-style: dotted;

    /*IE 10.0 이후 에서 사용하는 css (이전 버전은 지원 안함)*/
    column-count: 3;
    column-gap: 40px;
    column-rule-style: dotted;
}
</style>
</head>
<body>

<p><strong>Note:</strong> The column-rule-style property is not supported in Internet Explorer 9 and earlier versions.</p>

<div class="newspaper">
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Typi non habent claritatem insitam; est usus legentis in iis qui facit eorum claritatem. Investigationes demonstraverunt lectores legere me lius quod ii legunt saepius.
</div>

</body>
</html>
```

결과

![column-rule-style](../images/column-rule-style.jpg)




-----

* [CSS3 README](../README.md)

* [column-count](column-count.md)
* [column-gap](column-gap.md)
* [column-rule](column-rule.md)
* [column-rule-color](column-rule-color.md)
* [column-rule-style](column-rule-style.md)
* [column-rule-width](column-rule-width.md)
* [column-span](column-span.md)
* [column-width](column-width.md)
* [columns](columns.md)
