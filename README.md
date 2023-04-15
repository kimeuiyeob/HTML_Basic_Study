# HTML_Basic_Study

서버와 클라이언트<br>
클라이언트 : 서버에게 요청하는 대상<br>
서버 : 요청받은 서비스를 응답해주는 대상<br>
<br>
웹(Web)<br>
요청과 응답이 일어나는 장소.<br>
웹 브라우저(Web Browser)<br>
사용자의 요청에 맞는 주소로 찾아가서 인터넷 컨텐츠(문서와 그림, 멀티미디어 파일 등)를<br>
검색 및 열람 후 사용자에게 응답하기 위한 응용 프로그램의 총칭이다.<br>
주요 웹 브라우저로는 모질라 파이어폭스, 구글 크롬, 인터넷 익스플로러, 마이크로스프트 엣지, 오페라, 사파리 등이 있다.<br>
<br>
프로토콜(protocol) : 통신규약<br>
사람끼리 소통할 때 서로 이해할 수 있는 공용어를 사용해야 하듯이 컴퓨터끼리도 공용어를 사용해야 한다.<br>
이러한 공용어를 원활하게 통신하기 위해서 필요한 규약을 프로토콜이라고 한다. 사용자의 요청에 반드시 응답하도록 약속한다.<br>
<br>
http://(Hypertext Transfer Protocol)<br>
클라이언트와 서버 간의 웹 페이지 등의 자원을 통신하는 규약 , 텍스트로 통신하기 때문에 가로채어 본다면 누구든 내용을 볼 수 있다.<br>
<br>
https://(Hypertext Transfer Protocol Secure Socket)<br>
SSL(Secure Socket Layer) 프로토콜을 이용하여 자원을 공개키 암호화 방식으로 암호화해서 통신하는 규약<br>
<br>
IP(Internet Protocol)<br>
사람이 태어나면 출생신고를 하고 고유번호인 주민번호를 발급받는다.<br>
이를 통해 서로를 구분하듯이 네트워크 상에서 인터넷에 접속할 때 다른 컴퓨터와 구별될 수 있도록 하는 고유번호를 IP주소라고 한다.<br>
클라이언트가 찾아갈 서버의 고유한 값, 컴퓨터가 컴퓨터를 찾을 때 쓰는 고유한 값<br>
<br>
도메인(Domain)<br>
IP 주소는 기억하고 이해하기 힘들기 때문에 이를 위해서 이름을 부여할 수 있도록 한 것.<br>
도메인을 통해 IP 주소를 검색할 수 있다.<br>
아이피 주소로 직접 접근하면 연산이 필요한 부분이 제외되거나 프로토콜이 적용되지 않을 수 있기 때문에<br>
반드시 도메인을 통해 사이트에 접근하기로 한다.<br>
<br>
WWW(World Wide Web)<br>
인터넷에 연결된 전 세계 컴퓨터들을 통해 사람들이 정보를 공유할 수 있는 정보 공간<br>
<br>
W3C(더블유삼씨)<br>
WWW를 위한 표준을 제정하고 관리하는 중립적인 기관이다.<br>
<br>
웹 접근성<br>
모든 사용자가 신체적, 환경적 조건에 관계 없이 웹에 접근하여 이용할 수 있도록 보장하는 것을 의미한다.<br>
마우스가 없는 환경이나 키보드만을 조작해야 할 경우, 신체적 장애로 인해 특수한 환경 하에 접속을 해야<br>
되는 경우, 브라우저별, 모바일 환경에서 접속해야 되는 경우와 같이 다양한 플랫폼에서도 정보 제공에<br>
다름이 없어야 한다는 것이다.<br>
<br>
웹 표준(Web Standard)<br>
웹에서 표준으로 사용되는 기술이나 규칙을 의미하며, 이는 특정 브라우저에서만 사용되는<br>
비표준화된 기술을 배제하고 W3C의 토론을 통해 나온 권고안을 사용하는 것을 말한다.<br>
웹 문서의 구조와 표현, 그리고 동작을 구분해서 사용하는 것을 뜻한다.<br>
<br>
<br>
<h3>1. HTML(Hypertext Markup Language)</h3><br>
  웹 페이지에서 다른 페이지로 이동할 수 있도록 해주는 마크업 언어이다.<br>
  마크업 언어란 태그 방법 체계를 의미하며, 태그 등을 이용하여 문서나 데이터의 구조를 기술하는 언어이다.<br>
  <br>
2. CSS(Cascading Style Sheets)<br>
  구체적으로 어떤 스타일로 요소가 표시되는 지를 정하는 규격이다.<br>
  HTML은 문서를 구조화(레이아웃)하는 것 뿐만 아니라 꾸미기도 할 수 있지만,<br>
  동일한 디자인을 사용한 문서가 여러 개 있다면, 변경 시 모두 하나씩 수정해야 한다.<br>
  따라서 CSS는 이런 문제를 해결함과 동시에 웹 페이지에서 내용과 스타일을 분리하고 역할도 분리해준다.<br>
  <br>
3. JS(Javascript)<br>
  화면 쪽에서 연산이 가능한 스크립트 언어이다.<br>
  사용자의 다양한 이벤트 처리, 비동기 통신 등을 자유롭게 사용할 수 있다.<br>
  HTML안에서 태그형태로 JS를 사용할 수도 있으며, 외부 파일로 제작 후 포함시켜 사용할 수도 있다. 유효성 검사, 통신 등을 담당한다.<br>
  <br>
4. XHTML(Extensible HTML)<br>
  기존에 사용되던 HTML 규격이 가진 문제점을 극복하고 보다 다양한 분야에 응용될 수 있도록 해주는 여러가지 확장된 기능을 포함한다.<br>
  하지만 XML기반으로 만들어졌기 때문에 지원되지 않는 브라우저도 있다. 따라서 HTML과 XHTML은 사실상 큰 차이 없이 사용된다.<br>
  <br>
5. XML(Extensible Markup Language)<br>
  어떠한 데이터를 설명하기 위해서 임의로 지은 태그로 데이터를 감싼다.<br>
  태그로 데이터를 설명하며, 이것이 데이터의 표시(Markup)가 되고 추가적인 데이터가 생기면 태그 추가와 태그 내부 내용 추가를 할 수 있다.<br>
  <br>
HTML의 요소<br>
<p> You are better </p><br>
(1) 여는 태그(Opening tag) : 요소의 이름(p)과 열고 닫는 꺽쇠 괄호로 구성된다.<br>
(2) 닫는 태그(Closing tag) : 요소의 이름 앞에 슬래시(/)가 있다.<br>
(3) 내용(Content) : 요소의 내용이며, 단순한 텍스트를 의미한다.<br>
<br>
(1), (2), (3)을 통틀어 요소(Element)라고 한다.<br>
요소(태그)의 이름은 대소문자를 구분하지 않지만 가독성에 있어서 소문자로만 작성하는 것을 권장하다(XHTML).<br>
<br>
속성(Attributes)<br>
요소(태그)는 속성을 가질 수 있다.<br>
<br>
<p class="conversation"> You are much better </p><br>
<br>
속성은 요소에 나타내고 싶지 않지만 추가적인 내용을 담고 싶을 때 사용한다.<br>
특히 id와 class 속성은 스타일에 관련된 내용이나 기타 연산등의 내용을 위해 해당 태그를 찾을 수 있는 구분점 역할을 수행한다.<br>
<br>
- 속성 사용 시 주의사항<br>
1. 태그 이름 다음에 오는 속성은 태그 이름과 속성 사이에 공백이 있어야 하고,<br>
여러 속성이 있을 경우에는 속성 사이에도 공백이 있어야 한다.<br>
<p id="p1" class="pGroup"> You are much better </p><br>
2. 속성이름 다음에는 등호(=)를 작성한다.<br>
3. 속성 값은 따옴표 안에 작성한다(따옴표는 생략하여도 된다).<br>
내포된 요소(Nesting elements)<br>
요소 안에 다른 요소를 넣는 기법<br>
해당 부분에 다른 스타일 또는 다른 연산, 레아이웃 등을 적용하고자 할 때 사용한다.<br>
You are much better<br>
<br>
HTML 주의사항<br>
1. HTML은 대소문자를 구분하지 않지만 되도록 소문자로 작성한다.<br>
2. 속성의 값은 따옴표를 사용하지 않아도 되는 경우가 있지만, 띄어쓰기가 있을 경우 반드시 따옴표를 작성한다.<br>
3. HTML에서 작은 따옴표와 큰 따옴표는 둘 다 같은 의미이다.<br>
<br>
<br>
HTML 요소의 종류<br>
<br>
▶ 블록 요소<br>
- p, h, ul, ol, div, form, ... 등<br>
- 웹 페이지 상에 블록(영역)을 만드는 요소<br>
- 코드 상에 한 줄로 이어 써도 화면 상에서는 앞 뒤 요소 사이에 새로운 줄을 만들어서 나타난다.<br>
- <p>apple</p><p>banana</p><br>
- 영역이 정확히 구분되어 있기 때문에, width와 heigth 속성을 수정할 수 있다.<br>
- margin-top, margin-bottom 속성도 잘 적용된다(바깥 여백 상하)<br>
- padding-top, padding-bottom 속성도 잘 적용된다(안쪽 여백 상하)<br>
<br>
- div 태그<br>
1. 다른 html 요소들을 하나로 묶는 데 사용되는 대표적인 블록 요소이다.<br>
2. 주로 여러 요소들의 스타일을 한 번에 적용하기 위해 div 태그를 사용한다.<br>
<br>
▶ 인라인 요소<br>
- span, a, img, strong, em, ... 등<br>
- 새로운 줄을 만들지 않고 작성한 단락 내에 나타난다.<br>
- 안에 있는 내용 만큼만 영역을 차지한다.<br>
- <em>apple</em><span>banana</span><br>
- 영역이 불분명하기 때문에 width와 height를 임의로 부여할 수 없다.<br>
- margin-top, margin-bottom 속성도 부여할 수 없다(바깥 여백 상하)<br>
- padding-top, padding-bottom 속성도 부여할 수 없다(안쪽 여백 상하)<br>
<br>
- span 태그<br>
1. 텍스트의 특정 부분을 묶는 데 자주 사용되는 요소이다.<br>
2. 주로 텍스트의 특정 부분에 따로 다른 스타일을 적용하기 위해 사용한다.<br>
<br>
▶ 인라인 블록 요소<br>
- button, input, select, ...<br>
- inline 요소와 동일한 영역(내용만큼)을 가지지만 width와 height를 설정할 수 있다.<br>
- margin-top, margin-bottom 속성도 잘 적용된다(바깥 여백 상하)<br>
- padding-top, padding-bottom 속성도 잘 적용된다(안쪽 여백 상하)<br>
<br>
태그<br>
form 태그 (나중에 정확히 다룰 예정)<br>
   웹 페이지 내에서 사용자로부터 입력을 받을 때 사용하는 태그<br>
   사용자가 입력한 데이터를 다른 페이지로 전송할 때 form 태그를 사용한다.<br>
입력 태그 입력 태그 ...<br>
action : 데이터를 전송할 페이지의 경로(생략 시 현재 페이지)<br>
method : 데이터를 전송하는 방식(생략 시 get방식)<br>
name : form 태그의 이름을 설정(생략 시 이름 없음)<br>
<br>
input 태그<br>
입력 받기 위해 사용되는 태그, 데이터를 지정하여 전달할 때 사용하는 태그<br>
type : 입력 종류를 설정<br>
name : value의 key값<br>
value : 사용자가 입력한 값(입력 전에 미리 값을 넣어줄 수 있다).<br>
placeholder : 값은 아니지만 미리 출력해줄 문구를 작성할 수 있다.<br>
readonly : 수정할 수 없도록 하는 설정<br>
required : 필수 항목<br>
maxlength : 글자 수 제한<br>
<br>
input 태그의 type<br>
<input type="값"><br>
*text : 텍스트 입력(작성한 텍스트가 눈으로 보임)<br>
*password : 텍스트 입력(작성한 텍스트가 눈으로 안보임)<br>
*radio : 여러 개 중 하나의 옵션만 선택 가능<br>
*checkbox : 여러 개 중 다수의 옵션 선택 가능<br>
*file : 파일 전송(첨부파일 업로드)<br>
color : 색상 선택<br>
email : 이메일 입력(골뱅이 포함 입력)<br>
url : http://로 입력<br>
tel : 핸드폰 번호 입력<br>
date : 날짜 입력(브라우저 별로 캘린더의 스타일은 다를 수 있다)<br>
number, min, max, step : 숫자 입력<br>
range : 일정 범위 안의 값만 입력<br>
search : 검색어를 입력<br>
*button, submit, reset : 버튼, 전송, 초기화<br>
<br>
선택 입력<br>
select 태그는 여러 개의 옵션이 드롭다운 리스트로 되어 있으며,<br>
그 중 단 하나의 옵션만을 입력받을 수 있다.<br>
사용자에게 보여질 값 사용자에게 보여질 값 사용자에게 보여질 값 사용자에게 보여질 값 사용자에게 보여질 값 ...<br>
문장 입력<br>
<br>
textarea 요소는 사용자로부터 여러 줄의 텍스트를 입력받을 수 있다.<br>
<textarea cols="가로 글자 수 크기" rows="세로 행 크기">실제 값</textarea><br>
<br>
fieldset<br>
fieldset 요소는 관련있는 폼 필드 세트를 표시한다.<br>
form 필드 세트는 form 내에서 관련 태그를 하나의 그룹으로 묶은 것을 의미한다.<br>
<br>
legend<br>
fieldset 요소의 제목을 표시<br>
묶음에 대한 설명을 할 때 사용한다.<br>
