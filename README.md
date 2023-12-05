# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
<!-- #*6까지 -->
<!-- # 띄어쓰기 해야 함 -->

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리 나라 만세

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리 나라 만세  
무궁화 삼천리 화려 강산<br/> 
대한 사람 대한으로 길이 보전하세
<!-- 띄어쓰기 2번 안먹힐 경우 <br /> -->


# 강조(Emphasis)

_이탤릭_  
**두껍게**  
**_이탤릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>
<!-- 마크다운엔 언더라인 개념 없음 -->

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    <!-- 들여쓰기 두번 시 하단으로 들어가게 됨 -->
1. 순서가 필요한 목록
1. 순서가 필요한 목록

-  순서가 필요하지 않은 목록
-  순서가 필요하지 않은 목록
-  순서가 필요하지 않은 목록
    -  순서가 필요하지 않은 목록
    -  순서가 필요하지 않은 목록
-  순서가 필요하지 않은 목록

# 링크(link)

<a href="https://googl.com">GOOGLE</a>  

[GOOGLE](https://googl.com)

<a href="https://naver.com" tite="NAVER로 이동!">NAVER</a>
  
[NAVER](https://naver.com) "NAVER로 이동!"

<a href="https://naver.com" tite="NAVER로 이동!" target="_blank">NAVER</a>

# 이미지 (Image)

![]()
![GYANGTTO](https://avatars.githubusercontent.com/u/105619361?v=4)

[![GYANGTTO](https://avatars.githubusercontent.com/u/105619361?v=4)](https://github.com/gyangtto)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1  
>>> 중중첩된 인용문 2  
>>> 중중첩된 인용문 3

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은  
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다. 

# 블록(block) 코드 강조

```html
<a href="https://googl.com">GOOGLE</a>
```
<!-- 코드가 화면에 그대로 출력 됨 코드에 하이라이팅 -->

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
fucntion func() {
  let a = 'AAA';
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```planetext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리 나라 만세
```

# 표(table)

position 속성

값 | 의미 | 기본 값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X
<!-- 가운데 정렬 :--: -->
<!-- 오른쪽 정렬 --: -->

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리 나라 만세

<a href="https://naver.com" tite="NAVER로 이동!" target="_blank">NAVER</a>  
---
<img width="40" src="https://avatars.githubusercontent.com/u/105619361?v=4" alt="GYANGTTO" />

# 수평선(Horizontal Rule)

---

***

___




