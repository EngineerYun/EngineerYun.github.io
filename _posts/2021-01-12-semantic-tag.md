---
title: Semantic html
categories:
  - HTML/CSS
feature_image: "/assets/logos/Background_header_green.png"
---

### semantic html

---
+ 코드 자체에 의미가 부여된다
+ 해야하는 이유 : 작성된 코드들이 보기 좋고 알아보기 쉽다
+ head랑 헷갈리지 말자 head는 안 보이지만 header는 보인다
+ = container, box가능
+ = div태그로 다 대체 가능하다
  
**example**

```html
<header><h1>안녕하세요</h1></header>  <! ---머릿말--- >
<main><p>안녕하세요</p></main>        <! ---내용--- >
<footer><p>안녕하세요</p></footer>    <! ---꼬릿말--- >
```

**출력 결과**
<header><h1>안녕하세요</h1></header>
<main><p>안녕하세요</p></main>
<footer>&copy;안녕하세요</footer>  

**non-semantic tag**
+ 의미 없는 태그
+ 아무 값이 없는 box이다
+ div, span등이 속한다
  - `span` : 짧은 text를 위한 태그
    + div는 가장 통용적인 container  
  
```html
<div><span>안녕하세요</span></div>
```
**출력 결과**
<div><span>안녕하세요</span></div>


  


