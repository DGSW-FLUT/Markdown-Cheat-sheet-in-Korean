# Markdown-Cheat-sheet-in-Korean
+ Check [Original Version](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
+ 깃헙에서 사용가능한 [이모지 목록](https://gist.github.com/rxaviers/7360908)

||**목차**||
|:---:|:---:|:---:|
|[헤더](#헤더)|[강조](#강조)|[열거](#열거)|
|[링크](#링크)|[이미지](#이미지)|[코드](#코드)|
|[표](#표)|[블록강조](#블록강조)|[html](#html)|
|[구분선](#구분선)|[줄넘기기](#줄넘기기)|[유튜브](#유튜브)|

헤더
-----
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

H1, H2에 밑줄을 추가한 버전도 쓸 수도 있습니다.

Alt-H1
=====
Alt-H2
-----
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

H1, H2에 밑줄을 추가한 버전도 쓸 수도 있습니다.

Alt-H1
=====
Alt-H2
-----

강조
----- 
```
이탤릭체는 *별표* 혹은 _언더대쉬_ 를 원하는 글 양 옆에 두어 쓸 수 있습니다.

굵은체는 **별표 두 개** 혹은 __언더대쉬 두 개__ 를 원하는 글 양 옆에 두어 쓸 수 있습니다.

강조효과를 중첩할 수 도 있습니다. **별표 두 개와 _언더대쉬_**.

가운뎃줄은 ~~물결표 두개~~ 를 원하는 글 양 옆에 두어 쓸 수 있습니다.
```
이탤릭체는 *별표* 혹은 _언더대쉬_ 를 원하는 글 양 옆에 두어 쓸 수 있습니다.

굵은체는 **별표 두 개** 혹은 __언더대쉬 두 개__ 를 원하는 글 양 옆에 두어 쓸 수 있습니다.

강조효과를 중첩할 수 도 있습니다. **별표 두 개와 _언더대쉬_**.

가운뎃줄은 ~~물결표 두개~~ 를 원하는 글 양 옆에 두어 쓸 수 있습니다.

열거
----- 
```
1. 첫번째 번호 항목
2. 그 다음 번호 항목
⋅⋅⋅* 하위 단계의 번호 없는 항목
1. 번호는 순차적이지 않아도 동작 합니다.
⋅⋅⋅1. 하위 단계의 번호 항목
4. 마지막 번호 항목
(위의 항목에 한 줄 간격을 주지 않으면 이어 써집니다.)
⋅⋅⋅이렇게 긴 문장도 항목 안에 넣을 수 있습니다. 좌측에 들여쓰기가 생기고 이전 항목 간에 여백이 생깁니다.
⋅⋅⋅그러나 엔터를 해도 줄이 하나로 합쳐집니다.

⋅⋅⋅이를 막기 위해 줄이 끝나는 곳에 스페이스를 두개 넣어서 이를 막을 수 있습니다.⋅⋅
⋅⋅⋅줄을 나누어도 문단이 나누어지지 않았기에 이전 항목 간에 여백이 생기지 않습니다.

* 번호 없는 항목은 별표를 찍어 쓸 수 있습니다.
- 마이너스 표시도 됩니다.
+ 플러스 표시도 되고요.
```
1. 첫번째 번호 항목
2. 그 다음 번호 항목
   * 하위 단계의 번호 없는 항목
1. 번호는 순차적이지 않아도 동작 합니다.
   1. 하위 단계의 번호 항목
4. 마지막 번호 항목
(위의 항목에 한 줄 간격을 주지 않으면 이어 써집니다.)

   이렇게 긴 문장도 항목 안에 넣을 수 있습니다. 좌측에 들여쓰기가 생기고 이전 항목 간에 여백이 생깁니다.
   그러나 엔터를 해도 줄이 하나로 합쳐집니다.

   이를 막기 위해 줄이 끝나는 곳에 스페이스를 두개 넣어서 이를 막을 수 있습니다.  
   줄을 나누어도 문단이 나누어지지 않았기에 이전 항목 간에 여백이 생기지 않습니다.

* 번호 없는 항목은 별표를 찍어 쓸 수 있습니다.
- 마이너스 표시도 됩니다.
+ 플러스 표시도 되고요.

링크
----- 
```
[인라인 링크](https://www.google.com)

[제목을 가진 인라인 링크](https://www.google.com "Google's Homepage")

[레포지토리에 있는 파일도 링크 할 수 있습니다](../blob/master/LICENSE)

[참조 링크][네이버]

아니면 참조 링크 그 자체로 링크 할 수 있습니다. [네이버].

Some text to show that the reference links can follow later.

[네이버]: http://www.naver.com
```
[인라인 링크](https://www.google.com)

[호버 텍스트를 가진 인라인 링크](https://www.google.com "Google's Homepage")

[레포지토리에 있는 파일도 링크 할 수 있습니다](../blob/master/LICENSE)

[참조 링크][네이버]

아니면 참조 링크 그 자체로 링크 할 수 있습니다. [네이버].

[네이버]: http://www.naver.com

이미지
----- 
```
인라인 방식  
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "호버 텍스트 1")

참조 방식  
![alt text][로고1]

[로고1]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "호버 텍스트 2"


```

코드
-----
`(삐침표)를 3개 연달아 써서 원하는 코드를 표시할 수 있습니다.
```
'''javascript
var s = "자스";
alert(s);
'''

'''python
s = "파이썬"
print(s)
'''

'''
언어를 사용하지 명시하지 않고 표시합니다.
html을 표시할 때 사용됩니다.
**tag**<br>br
'''
```


```javascript
var s = "자스";
alert(s);
```

```python
s = "파이썬"
print(s)
```

```
언어를 사용하지 명시하지 않고 표시합니다.
html을 표시할 때 사용됩니다.
**tag**<br>br
```

표
----- 
```
열 구분 표시(------)는 정렬 표기에도 이용됩니다.

| 표            | is             | 편안  |
| ------------- |:-------------:| -----:|
| 3열은          | 오른쪽 정렬 | $1600 |
| 2열은          | 중앙절렬    |   $12 |
| 파이썬은        | 멋지다      |    $1 |

열 구분 표시는 3개 이상의 -(대쉬)를 가지고 있어야 합니다.
바깥 |(파이프)는 선택적입니다.
```
열 구분 표시(------)는 정렬 표기에도 이용됩니다.

| 표            | is             | 편안  |
| ------------- |:-------------:| -----:|
| 3열은          | 오른쪽 정렬 | $1600 |
| 2열은          | 중앙절렬    |   $12 |
| 파이썬은        | 멋지다      |    $1 |

열 구분 표시는 3개 이상의 -(대쉬)를 가지고 있어야 합니다.
바깥 |(파이프)는 선택적입니다.

블록강조
----- 
```
> 블록 강조는 이메일 답장에서 자주 사용되는 양식입니다.
> 이 줄도 이전의 블록 강조에 이어씁니다.

블록 나누기!

> 이 블록은 매우 긴 줄이고 모든 글자가 블록안에 들어가고 있습니다. 계속 작성해서 이것이 길어도 모두를 위해 포장(?)할 수 있는지 확인하세요. 이건 *블록강조에* 전부 들어가고 있습니다.
>> 이렇게 블록안에 블록을 둘 수도 있습니다.
> 그렇습니다.
```
> 블록 강조는 이메일 답장에서 자주 사용되는 양식입니다.
> 이 줄도 이전의 블록 강조에 이어씁니다.

블록 나누기!

> 이 블록은 매우 긴 줄이고 모든 글자가 블록안에 들어가고 있습니다. 계속 작성해서 이것이 길어도 모두를 위해 포장(?)할 수 있는지 확인하세요. 이건 **블록강조**에 전부 들어가고 있습니다.
>> 이렇게 블록안에 블록을 둘 수도 있습니다.
> 그렇습니다.

html
----- 
여러분은 HTML 코드를 마크다운에 넣을 수 있습니다. 잘 동작 할 것입니다.
```
<dl>
  <dt>정의 목록</dt>
  <dd>때때로 쓰는 무언가.</dd>

  <dt>Markdown in HTML</dt>
  <dd>**아주** 잘 동작 하지 *않*습니다. HTML <em>tags</em>를 써보세요.</dd>
</dl>
```
<dl>
  <dt>정의 목록</dt>
  <dd>때때로 쓰는 무언가.</dd>

  <dt>Markdown in HTML</dt>
  <dd>**정말** 잘 동작 하지 *않*습니다. HTML <em>tags</em>를 써보세요.</dd>
</dl>

구분선
----- 
```
3개 이상은 써주셔야 해요.

---

대쉬들

***

별표들

___

언더대쉬들
```

3개 이상은 써주셔야 해요.

---

대쉬들

***

별표들

___

언더대쉬들

줄넘기기
----- 

```
여기에 줄이 몇 개 있습니다.

이 줄과 이전 줄 사이에 한 줄 여백이 있습니다. 그러면 문단은 이렇게 나눠집니다.

이것도 나눠진 문단인데요. 그러나...
이 줄은 이전 줄 사이에 한 줄 여백이 없습니다. 그러면 같은 줄에 써집니다.

그러나 위의 사례에서 첫번째 줄 끝에 공백을 두개 추가하면요.⋅⋅  
줄은 넘겨집니다만 문단은 나눠지지 않습니다.
```
여기에 줄이 몇 개 있습니다.

이 줄과 이전 줄 사이에 한 줄 여백이 있습니다. 그러면 문단은 이렇게 나눠집니다.

이것도 나눠진 문단인데요. 그러나...
이 줄은 이전 줄 사이에 한 줄 여백이 없습니다. 그러면 같은 줄에 써집니다.

그러나 위의 사례에서 첫번째 줄 끝에 공백을 두개 추가하면요.  
줄은 넘겨집니다만 문단은 나눠지지 않습니다.

유튜브
-----

유튜브 영상을 바로 넣을 수는 없습니다만 
유튜브 영상 링크를 가진 이미지는 만들 수 있습니다.
```
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
```
<a href="http://www.youtube.com/watch?feature=player_embedded&v=v78CPJVrl8E
" target="_blank"><img src="http://img.youtube.com/vi/v78CPJVrl8E/0.jpg" 
alt="LOONA/OEC Sweet Crazy Love" width="240" height="180" border="10" />
</a>

License: [CC-BY](https://creativecommons.org/licenses/by/3.0/)
