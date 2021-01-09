---
title: html head tag 정리
categories:
  - HTML/CSS
feature_image: "/assets/logos/Background_header_green.png"
---

### html head tag

---

**head태그**
보이지 않는 사이트 정보를 브라우저에게 알려준다  
검색엔진이 이해할 수 있게 만든다

- **meta tag** : 부가적인 정보이다.
  - 요소: title, base, link, style, script를 이용하여 표현할 수 없는 다양한 종류의 메타데이터를 나타낸다  
    -meta tag들은 self-closing 태그이다
  - attribute(속성)은 2가지로 나눠진다
    - content
    - name
- **charset** : 브라우저에게 text를 어떻게 그려야할지 알려준다
  - 한글이나 특수문자 언어 입력할 때 브라우저가 이해하지 못하는 경우가 있다
  * 이 태그가 없으면 글자가 깨져보인다
- **html language**: attribute(속성)이다 구글등의 검색 엔진에 도움이 된다  
  사이트의 주 사용되는 언어를 가르쳐준다
- `title, description`: 구글 엔진이 찾는 태그이다
- `og:~`: 카카오톡 공유될 때 보여주는 정보들
