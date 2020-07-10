---
title: 마크다운(Markdown) 문법 총정리
date: "2020-07-11"
description: "개츠비로 블로그를 시작하게 되면서 마크다운을 이용하여 글을 작성하게 되었다. 
<br />
마크다운을 마스터해보자."
---

개츠비로 블로그를 시작하게 되면서 마크다운을 이용하여 글을 작성하게 되었다.

마크다운을 마스터해보자.

<!-- end -->

---

## 제목 Headers

# H1

## H2

### H3

#### H4

##### H5

###### H6

```
# H1
## H2
### H3
#### H4
##### H5
###### H6

h1
===

h2
---
```

<br />

## 인용 Blockquotes

> 인용문

```
> 인용문
```

<br />

## 코드 블럭 Code Blocks

```
코드 블럭
```

````
``` 혹은 ~~~
코드 블럭
``` 혹은 ~~~
````

<br />

## 인라인 코드 Inline Code Blocks

`인라인 코드 블럭`

```
`인라인 코드 블럭`
```

<br />

## 강조 Emphasis

_기울여 쓰기_

_italic_

**굵게 쓰기**

**bold**

```
*기울여 쓰기*
_italic_

**굵게 쓰기**
__bold__
```

<br />

## 수평선 Horizontal Rules

---

```
---
***
___
```

<br />

## 링크 Links

- 외부 링크 External Links

  - 인라인 링크

  [Google](https://www.google.com "구글")

  ```
  [Google](https://www.google.com "구글")
  ```

  - 참조 링크

  [Google][1]
  [Naver][2]

  ```
  [Google][1]
  [Naver][2]

  [1]: https://www.google.com/
  [2]: https://www.naver.com/
  ```

  - URL 링크

  <https://www.google.com/>

  ```
  <https://www.google.com/>
  ```

- 내부 링크 Internal (Anchored) Links

[H1](#h1)

```
[H1](#h1)
```

[1]: https://www.google.com/
[2]: https://www.naver.com/

<br />

## 리스트 Lists

- 순서 있는 리스트 Ordered Lists

  1. item 1
  2. item 2
  3. item 3

  ```
  1. item 1
  2. item 2
  3. item 3
  ```

- 순서 없는 리스트 Unordered Lists

  - item 1

        - item 1-1
        - item 1-2

```
* item 1
    * item 1-1
    * item 1-2
+ item 1
    + item 1-1
    + item 1-2
- item 1
    - item 1-1
    - item 1-2
```

<br />

## 테이블 Tables

| Header 1  | Header 2  |
| --------- | --------- |
| Content 1 | Content 3 |
| Content 2 | Content 4 |

```
| Header 1  | Header 2  |
| --------- | --------- |
| Content 1 | Content 3 |
| Content 2 | Content 4 |
```

<br />

## 이미지 Adding Images

![alt text](./gatsby-icon.png)

```markdown
![alt text](./gatsby-icon.png) // 인라인 이미지
![alt text](image_URL) // 링크 이미지
```

<br />
