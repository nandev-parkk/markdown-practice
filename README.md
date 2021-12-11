# 제목(Header)

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

# 문장 (Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks), 띄어쓰기 2개 or br tag

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산  
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이탤릭_  
**두껍게**  
**_이탤릭 + 두껍게_**  
~~취소선~~

<!-- markdown에서 밑줄을 입력하는 기능이 없기 때문에 html tag로 입력 -->

<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
   <!-- (들여쓰기 두번) -->
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
  <!-- (들여쓰기 두번) -->
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동")

<!-- markdown에는 target 속성이 없기 때문에 아래와 같이 a tag로 작성하거나 원시 html을 이용해야한다. -->

<a href="https://naver.com" title="NAVER로 이동" target="_blank">NAVER</a>

# 이미지(Images)

![이미지이름](https://dreamy-lamarr-cab7d4.netlify.app/images/starbucks_logo.png)

[![이미지이름](https://dreamy-lamarr-cab7d4.netlify.app/images/starbucks_logo.png)](https://naver.com)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>
> > 중첩된 인용문
> >
> > > 중중첩된 인용문 1  
> > > 중중첩된 인용문 2  
> > > 중중첩된 인용문 3

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은
background-image 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://google.com" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  let a = "AAA";
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표(table)

position 속성

| 값       |       의미        | 기본값 |
| -------- | :---------------: | -----: |
| static   |     기준 없음     |      O |
| relative |     요소 자신     |      X |
| absolute | 위치 상 부모 요소 |      X |
| fixed    |      뷰포트       |      X |

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br />
하느님이 보우하사 우리나라 만세

<a href="https://naver.com" title="NAVER로 이동" target="_blank">NAVER</a>

<img width="100" src="https://dreamy-lamarr-cab7d4.netlify.app/images/starbucks_logo.png" alt="logo" />

# 수평선(Horizontal Rule)

---

---

---
