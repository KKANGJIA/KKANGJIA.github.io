---
layout: post
title: "[정리] 모던 웹을 위한 HTML5+CSS3 바이블 3판(1) "
subtitle: "Chapter2 HTML5 태그 기본"
categories: review
tags:
comments: true
header-img: ![책 이미지](https://search.pstatic.net/common/?src=http%3A%2F%2Fshop1.phinf.naver.net%2F20201206_274%2F1607214620995yhXHD_JPEG%2F14679317044366106_419076983.jpg&type=a340)
---

<br>

<article style="font-size: 20px; text-align: center;">최근에 <b style="color: green">모던 웹을 위한 HTML5+CSS3 바이블 3판</b>이라는 책을 읽고있다.

예전부터 읽기는 했었는데 Javascript를 공부한다는 핑계로 책을 읽지 않게 되었다.

읽으면서 아는 내용이라고 생각해서 굳이 읽어야 하나 싶었던 마음도 있었다.

하지만 막상 다시 읽어보니 정확히 알지 못했던 것들이나 새롭게 알게되는 내용을 보고 정독+완독해야겠다고 느꼈다.

그리고 올해는 웹 관련 서적, 컴퓨터 CS 관련 서적을 많이 읽어야겠다는 목표를 이루고자!!!

<br>
<br>

부담가지지 않고 술술 읽어내려 했는데 내 기억력은 <b style="color: orange">금붕어</b>라는 사실이 문득 머리를 퍽 때렸다.

'내 자신을 말이야... 도대체 믿을 수 없단 말이지... 이녀석...'

</article>
<br>

![짱구짤](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FDomPA%2FbtqVFCo1kT8%2FvUKVUHD6DZ7cxETczTNtu0%2Fimg.jpg)

<br>

<del>참고 + TMI : 글 작성자는 짱구를 아주아주 좋아하기 때문에 짱구 짤이 자주 등장할 예정이다</del>

[출처: https://www.youtube.com/watch?v=hqOE6OKUS7c](https://www.youtube.com/watch?v=hqOE6OKUS7c)

<br>
<br>

---

#Chapter 2 HTML5 태그 기본

<h3>[글과 관련된 태그]</h3>

<article style="font-size: 20px;">
1.  제목 태그: h1, h2, h3, h4, h5, h6 => heading의 줄임말로 1~6은 크기를 지정
    <br>

2.  본문 태그: p => paragraph의 줄임말로 하나의 단락을 생성

                    본문과 관련한 태그: br 줄바꿈 / hr 수평선

<br>
3. 앵커(Anchor) 태그: a => 서로 다른 웹페이지 사이를 이동하거나 웹페이지 내부에서 특정한 위치로 이동할 때 사용, href 속성으로 페이지 주소 지정

<br>4. 글자형태 태그: b => bold체

                    i => italic체

                    small => 작은 글자

                    sub => 아래에 달라 붙는 글자 태그

                    sup => 위에 달라붙는 태그

                    ins => 밑줄 글자 태그

                    del => 가운데 줄이 그어지는 글자 태그

<br>
5.  목록 태그: ul(unordered list): 순서가 없는 목록 태그

                    ol(ordered list): 순서가 있는 목록 태그

                     li: 목록 요소

<br>
6.  정의 태그: dl(definition list): 정의 목록 태그

                   dt(definition term): 정의 용어 태그

                   dd(definition description): 정의 설명 태그

<br>
<fieldset>
<legend>참고</legend>
실제 개발 시 목록과 정의태그는 구분없이 사용할 수 있음 하지만 구분해서 쓰도록 하자!
</fieldset>

<br>
<br>

<h3>[표 관련 태그]</h3>

1.  테이블 태그: table: 테이블 생성 태그 => border: 테이블의 두께 지정하는 속성

                    tr: 표 내부의 행 태그

                    th: 행 내부의 제목 셀 태그

                    td: 행 내부의 일반 셀 태그

<br>
<br>

<h3>[엔터테인먼트 관련 태그]</h3>
이미지 태그: img => 속성종류: src, alt(이미지가 없을 때 나오는 글자 지정), width, height

오디오 태그 => audio => 속성종류: src, preload(음악 재생 전에 모두 불러올 지 지정), autoplay, loop, controls(음악 재생도구 출력할 지 지정)

<fieldset>
<legend>참고</legend>
source태그를 사용할 때 type을 같이 지정해주면 웹 브라우저가 음악 파일을 내려받은 뒤에 재생 가능한 파일인지 확인하지 않아도 되서 트래픽 낭비가 발생하지 않음
</fieldset>
<br>
비디오 태그: video => 속성 태그: src, poster(동영상이 준비 중일 때 이미지 파일 경로 지정), preload, autoplay, loop, controls, width, height
<br>
<br>

<h3>입력 양식 태그: 사용자에게 입력받는 공간 (ex: 회원가입 양식)</h3>

form: 입력 양식 생성input: form태그 안에 작성하는 입력받는 태그 속성종류: HTML4/ HTML5에서 지원하는 속성의 종류가 다르다 HTML4에서 지원하던 속성의 종류: text, button, checkbox, file, hidden, image, password, radio, reset, submit // 내부에 글자를 넣고 싶다면 value속성을 사용하고 회색 글씨로 예시 글자를 보여주고 싶으면 placeholder를 사용하기HTML5에서 지원하는 속성의 종류: color, date, datetime, datetime-local, email, month, number, range, search, tel, time, url, week

textarea 태그: 입력양식의 한 종류로 여러 줄의 글자를 입력하는 박스를 만드는 태그 => 속성종류: cols(태그의 너비), rows(태그의 높이)

select 태그: 여러 개의 목록에서 몇 가지를 선택할 수 있는 태그, 선택 양식을 생성 => 속성종류: multiple="multiple" = 여러개의 목록을 선택할 수 있음(아무 속성도 입력하지 않으면 한개만 선택가능)optgroup: 옵션을 그룹화함 => 속성 종류: label = "그룹명"으로 그룹명을 지정할 수 있음option: 옵션을 생성

fieldset: 입력양식을 설명하는 태그로 입력양식을 박스형태로 만들어줌

legend: 입력양식의 제목을 달 수 있음
<br>
<br>

<h3>[공간분할 태그]</h3>

div: block 형태로 공간구분 (block형식 태그 => h1~h6, p, 목록, 테이블, form태그)

span: inline 형태로 공간구분 (lnline형식 태그 => a, input, 글자형식 태그)

<br>
<br>

<h3>[HTML5 시멘틱 웹 구조 태그]</h3>

<b style="color:red">시멘틱(semantic, 의미론적인) 웹</b>이란? 기계적인 검색엔진은 어떤 태그가 어떤 기능을 하는지 분별할 수 없어서 웹페이지에서 데이터를 효율적으로 추출할 수 없다는 단점이 있어서 이 것을 해결하고자 특정한 태그에 의미를 부여해서 웹페이지를 만드는 것

시멘틱 구조 태그: header(헤더), nav(네비게이션), aside(사이드에 위치하는 공간), section(여러 중심 내용을 감싸는 공간), article(글자가 많이 들어가는 부분), footer(푸터, 제작자 등을 표시) => <b style="color:red">기계적인 모든 것들이 웹페이지를 이해하기 위한 것</b>
<br>
<br>
<br>

<p style="text-align: center;">다음 <b>Chapter3</b>에서는 <b>CSS</b>에 대해 정리해보자 : )</p>
<br>
<br>
<br>
</article>

- [책소개 - 모던 웹을 위한 HTML5+CSS3 바이블 3판](https://search.pstatic.net/common/?src=http%3A%2F%2Fshop1.phinf.naver.net%2F20201206_274%2F1607214620995yhXHD_JPEG%2F14679317044366106_419076983.jpg&type=a340)
