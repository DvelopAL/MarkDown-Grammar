# MarkDown-Grammar
MarkDown(이하 마크다운) 문법을 설명합니다.
대단원의 제목은 '한글이름' [영어이름]순으로 작성되었습니다.

몇몇 문법은 Github에서 올바르게 작동하지 **않을** (Ex. 각주) 수 있습니다.

# 목차
#### 1. [헤더 [Header]](#Header)
#### 2. [텍스트 [Text]](#Text)
#### 3. [강조 [Emphasis]](#Emphasis)
#### 4. [수평선 [Horizontal Rules]](#Horizontal)
#### 5. [인용구 [BlockQuotes]](#BlockQuotes)
#### 6. [코드 블록 [Code Blocks]](#CodeBlocks)
#### 7. [코드 [Code]](#Code)
#### 8. [목록 [List]](#List)
#### 9. [표 [Table]](#Table)
#### 10. [링크 [Link]](#Link)
#### 11. [참조 링크 [Link]](#Link2)
#### 12. [이미지 [Image]](#Image)
#### 13. [주석 [Comment]](#Comment)
#### 14. [각주 [Footnote]](#Footnote)
#### 15. [이미지 버튼 [Image Button]](#ImgButton)

## 1. 헤더 [Headers] <a id="Header">
* 보통 큰 대단원을 소개할 때 사용


* 사용법 : # 내용
  * 총 6단계 중첩 가능, #이 많아질수록 점점 작아짐
  * 3개 사용부터는 주로 부제목, 강조등에 사용


* 예시 코드

      ###### 6번 중첩
      ##### 5번 중첩
      #### 4번 중첩
      ### 3번 중첩
      ## 2번 중첩
      # 1번 중첩


* 결과
  ###### 6번 중첩
  ##### 5번 중첩
  #### 4번 중첩
  ### 3번 중첩
  ## 2번 중첩
  # 1번 중첩

## 2. 텍스트 [Text] <a id="Text">
* 문서의 본문에 사용


* 사용법 : 그냥 적으면 됨


* 예시 코드

        이것은 텍스트 입니다.


* 결과
이것은 텍스트 입니다.

## 3. 강조 [Emphasis] <a id="Emphasis">
* 텍스트를 강조할 때 사용
* 내용을 감싸주면 됨

* 사용법 : * or _ or ** or __ or ~~


* 예시 코드

        *Italic*
        _Italic_
        **Bold**
        __Bold__
        ++Under Line++
        ~~Strike Out~~


* 결과
*Italic*
_Italic_
**Bold**
__Bold__
++Under Line++
~~Strike Out~~

## 4. 수평선 [Horizontal Rules] <a id="Horizontal">
* 문장을 구분할 때 사용
  * 3가지 방법 모두 같은 결과를 도출
  * 즉, 마음에 드시는거 사용하면 됨



* 사용법 : --- or *** or ___


* 예시 코드

        ***
        ---
        ___


* 결과
***
---
___

## 5. 인용구 [BlockQuotes] <a id="BlockQuotes">
* 이메일에서 사용하는 인용구
  * 인용구안에 다른 요소들을 포함할 수 있음


* 사용법 : >


* 예시 코드

        > 인용구의 내용
        > ###### 헤더를 포함해 봤습니다.


* 결과
  > 인용구의 내용
  > ###### 헤더를 포함해 봤습니다.

## 6. 코드 블록 [Code Blocks] <a id="CodeBlocks">
* 코드 작성 블록 안에서는 마크다운 문법도 제외함
  * 약간씩 다를 수 있음
  * SPACE 4번 or TAP 4번

* 사용법 : '    ' or '[TAP][TAP][TAP][TAP]'


* 예시 코드

        # 여기서는 마크다운도 안됨
        이렇게 생성해주시면 됩니다.


* 결과
        # 여기서는 마크다운도 안됨
        이렇게 생성해주시면 됩니다.

## 7. 코드 [Code] <a id="Code">
* 특정 부분만 코드 블록으로 사용 가능
* 혹은 강조용으로 사용하기도 함


* 사용법 : \` (!에서 Shift땐 키)


* 예시 코드

        `# 이렇게도 사용하고`
        `강조`도 가능합니다.


* 결과
`# 이렇게도 사용하고`
`강조`도 가능합니다.


## 8. 목록 [List] <a id="List">
* 특정 줄 강조 혹은 목차등을 표시할 때 사용
* 오름차순으로 요소들을 표현할 때도 가능
* 하지만 내림차순은 안됨, 무조건 오름차순 표현 or 아예 없이


* 순서있는 목록 사용법 : 1 or 2 or 3 - 잘못 입력해도 알아서 수정됩니다.


* 순서없는 목록 사용법 : * or + or - 셋중 아무거나 사용하면 됩니다.


* 예시 코드

        1. 1번 요소
        3. 3번 요소
        2. 2번 요소

        * 제목
          * 부제목
            * 내용


* 결과값
1. 1번 요소
3. 3번 요소
2. 2번 요소

* 제목
  * 부제목
    * 내용

## 9. 표 [Table] <a id="Table">
* 표를 나타냄
* 안에 다른 요소를 포함 할 수 있음


* 사용법 : [:-] 오른쪽 정렬 | [:-:] 중앙 정렬 | [-:] 왼쪽 정렬


* 예시 코드 :

        | 이름     | 생년월일    | 상태   |
        | :-      | :-:         | -:     |
        | 김덕원   | ~~1999-04-06~~  | 피곤함 |


* 결과

| 이름     | 생년월일    | 상태   |
| :-      | :-:         | -:     |
| 김덕원   | ~~1999-04-06~~  | 피곤함 |

## 10. 링크 [Link] <a id="Link">
* 링크를 연결할 수 있음


* 사용법 : [텍스트]\(링크) or [텍스트]\(링크 "마우스 올렸을 때 문자")


* 예시 코드  

        [블로그 주소](wangchunsik.tistory.com),
        [블로그 주소](wangchunsik.tistory.com "한번 씩 들려주세요")


* 결과
[블로그 주소](wangchunsik.tistory.com)
[블로그 주소](wangchunsik.tistory.com "한번 씩 들려주세요")

## 11. 참조 링크 [Link] <a id="Link2">
* 해당 아이디가 있는 곳으로 스크롤을 이동함
* 보이는곳(한 스크롤에 보이는 곳)에 있다면 효과가 없음


* 사용법 : \[텍스트](#태그), 내용 \<a id="태그">


* 예시 코드

        [1번 헤더 설명](#Header)


* 결과
[1번 헤더 설명](#Header)

## 12. 이미지 [Image] <a id="Image">
* 화면에 이미지 출력가능
* 하지만 직접적으로 업로드는 힘듬
* 이미지 링크 or 이미지 경로를 통해 출력함


* 사용법 !\[이미지이름](이미지주소)


* 예시 코드

        ![프로필 사진](https://avatars2.githubusercontent.com/u/12786855?s=460&v=4)
        ![프로필 사진](https://avatars2.githubusercontent.com/u/12786855?s=460&v=4 "프로필 사진")


* 결과

![프로필 사진](https://avatars2.githubusercontent.com/u/12786855?s=460&v=4)

![프로필 사진](https://avatars2.githubusercontent.com/u/12786855?s=460&v=4 "프로필 사진")

## 13. 주석 [Comment] <a id="Comment">
* 프로그래밍언어처럼 주석을 남기기 가능


* 사용법 \<!-- 주석 내용 -->


* 예시 코드

        \
        <!--
        주
        석
        내
        용
        -->


* 결과
<!--
주
석
내
용
-->

## 14. 각주 [Footnote] <a id="Footnote">
* 내용에 대한 보충설명을 하는 각주를 달아줌


* 사용법 : 각주달 문장[^태그] || [^태그]: 각주 내용


* 예시 코드

        블로그[^주소]에 한번 놀러오세요!
        [^주소]: wangchunsik.tistory.com


* 결과

블로그[^주소]에 한번 놀러오세요!
[^주소]: wangchunsik.tistory.com


## 15. 이미지 버튼 <a id="ImgButton">
* 지금까지의 내용을 응용하여 이미지를 누르면 링크로 이동하는 걸 만듬


* 사용법 : \[!\[이미지이름](이미지링크)]("링크")


* 예시 코드

        [![영상](http://img.youtube.com/vi/23Fn12fUhCk/0.jpg)](https://www.youtube.com/watch?v=23Fn12fUhCk)

* 결과

[![영상](http://img.youtube.com/vi/23Fn12fUhCk/0.jpg)](https://www.youtube.com/watch?v=23Fn12fUhCk)
