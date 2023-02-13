# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

```
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록<br />
하느님이 보우하사 우리나라 만세<br />
무궁화 삼천리 화려 강산<br />
대한 사람 대한으로 길이 보전하세<br />

```html
동해물과 백두산이 마르고 닳도록<br />
하느님이 보우하사 우리나라 만세<br />
무궁화 삼천리 화려 강산<br />
대한 사람 대한으로 길이 보전하세<br />
```

# 강조(Emphasis)

_이탤릭_  
문장뒤에 띄워쓰기 두번해도 줄 바꿈이 됩니다.  
**두껍게**  
**_이탤릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

```markdown
문장뒤에 띄워쓰기 두번해도 줄 바꿈이 됩니다.  
**두껍게**  
**_이탤릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>
```

# 목록

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 탭을 누르고 목록을 작성하면 하위 목록이 생성됩니다.
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록
  
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록

  # 링크(Links)

  <a href="https://google.com">GOOGLE</a>
  [GOOGLE](https://google.com)
  ```html
  <a href="https://google.com">GOOGLE</a>
  [GOOGLE](https://google.com)
  ```

  <a href="https://naver.com" title="NAVER로 이동!">NAVER</a>  
  [NAVER](https://naver.com "NAVER로 이동!")  
  <a href="https://naver.com" title="NAVER로 이동!" target="_blanck">NAVER</a> 
  ```html
  <a href="https://naver.com" title="NAVER로 이동!">NAVER</a>  
  [NAVER](https://naver.com "NAVER로 이동!")
  <a href="https://naver.com" title="NAVER로 이동!" target="_blanck">NAVER</a> 
  ```

  # 이미지(Images)

  ![이미지명(생략가능)](이미지 주소)

  ![Jgone2](https://media.vlpt.us/images/jgone2/post/5097e3af-f64e-4e9f-b990-bfa9e084f4a0/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202022-01-03%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%2010.48.49.png)
  ```
    ![Jgone2](https://media.vlpt.us/images/jgone2/post/5097e3af-f64e-4e9f-b990-bfa9e084f4a0/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202022-01-03%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%2010.48.49.png)
  ```
  <img width="70" src="https://media.vlpt.us/images/jgone2/post/5097e3af-f64e-4e9f-b990-bfa9e084f4a0/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202022-01-03%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%2010.48.49.png" alt="Gon">

```html
<img width="70" src="https://media.vlpt.us/images/jgone2/post/5097e3af-f64e-4e9f-b990-bfa9e084f4a0/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202022-01-03%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%2010.48.49.png" alt="Gon">
```

  # 인용문(BlockQuote)
  
  > 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
  > (네이버 국어 사전)

  > 인용문을 작성하세요!
  >> 중첩된 인용문
  >>> 중중첩된 인용문1
  ```
  > 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
  > (네이버 국어 사전)

  > 인용문을 작성하세요!
  >> 중첩된 인용문
  >>> 중중첩된 인용문1
  ```

  # 인라인(inline) 코드 강조

  CSS에서 `background` 혹은  
  `background-image` 속성으로 요소에 배경  
  이미지를 삽입할 수 있습니다.

  ```plaintext
  CSS에서 `background` 혹은  
  `background-image` 속성으로 요소에 배경  
  이미지를 삽입할 수 있습니다.
  ```

  # 블록(block) 코드 강조

  <a href="https://google.com" target="_blank">GOOGLE</a>  
  ```html
    <a href="https://google.com" target="_blank">GOOGLE</a>  
  ```

  ```css
    h1 {
        color: orange;
    }
  ```

  ```javascript
    function func() {
        var a = 'Hello World!';
        return a;
    }
  ```

  ```bash
    git commit -m 'Study Markdown'
  ```

  ```plaintext
    동해물과 백두산이 마르고 닳도록  
    하느님이 보우하사 우리나라 만세
  ```

  # 표(Table)

  position 속성

  값 | 의미 | 기본값  
--|--:|:--:
static | 기준 없음 | O  
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

```
  값 | 의미 | 기본값  
--|--:|:--:
static | 기준 없음 | O  
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X
```


# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세
```html
동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세
```


<a href="https://google.com" title="GOOGLE로 이동" target="_blank">GOOGLE</a>  
```
<a href="https://google.com" title="GOOGLE로 이동" target="_blank">GOOGLE</a>  
```


# 수평선(Horizontal Rule)

수평선만들기  

---
수평선 만드는 중

***
수평선 만드는 중

___
