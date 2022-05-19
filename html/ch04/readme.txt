div 태그에 대해서 알아보자

div = division 이라는 단어에서 나왔다 ( 분할, 구분, 경계선 )

div(박스 모델)
: 의미가 없는 태그, 의미가 있는 태그로 대체 하고 있다.(semantic tag, non-semantic tag)

HTML 정리
- html = 뼈대, 근육
- CSS =  생김새
- javascript = 동작

태그는 꺽쇠만 있다면 만들 수 있지만 <abc123>안녕<abc123>
웹 브라우저는 이해하지 못한다. 
그래서 브라우저가 이해하는 언어로 작성을 해야한다.

태그 모양
<태그이름>content</태그이름>
<input .... /> = self closing tag
<a>
    <p>잠이 온다.</p>
</a>
= 태그 중첩
태그를 잘못사용하면 제대로 작동이 안될 수 있다.

속성
: 태그 안에는 각각에 맞는 attribute(속성)이 존재한다.
<h1 href="http://www.naver.com" target="_blank">하이</h1>  --- 작동 X 
: "" <-- 속성에 값을 넣을 때 쌍따움표("")을 사용하자
: '' <-- 물론 얘도 사용 가능하지만 권장하지는 않음
``

식별자
: 어떤 태그는 id or class 를 가질 수 있다.

semantic
: 태그에 의미가 있는 태그가 있고, 아무 의미가 없는 태그가 있다. 
: 가능한 semantic 태그를 사용하는 것을 권장한다.

semantic tag >>> header, main, footer, address ...
non-semantic tag >>> p, span, div ..... 

박스 모델
: 박스 옆에 박스가 올수 없다.
: 하지만 CSS로 변경이 가능하다.

웸사이트에 설정을 담당하는 태그 = <head> 태그이다.
