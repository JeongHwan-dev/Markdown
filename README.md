<div align="center">
   <br />
   <img src="./markdown_logo.png" height="200px" />
   <br />
   <br />
   <h1>:page_facing_up: 마크다운 가이드(Markdown Guide)</h1>
</div>

<br />

## 목차

1. **[개요](#개요)**
2. **[제목](#제목)**
3. **[줄바꿈](#줄바꿈)**
4. **[강조](#강조)**
5. **[목록](#목록)**
6. **[링크](#링크)**
7. **[이미지](#이미지)**
8. **[인용문](#인용문)**
9. **[코드 강조](#코드-강조)**
10. **[표](#표)**
11. **[원시 HTML](#원시-html)**
12. **[수평선](#수평선)**

<br />

## 개요

**마크다운(Markdown)** 은 일반 텍스트 기반의 `경량 마크업 언어`이다.

### 장점

- 문법이 쉽고 간결하다!
- 관리가 쉽다!
- 지원 가능한 플랫폼과 프로그램이 다양하다!

### 단점

- 표준이 없다!
- 모든 HTML 마크업을 대신하지 못한다!

<br />

## 제목

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

<br />

## 줄바꿈

동해물과 백두산이 마르고 닳도록  <!--띄어쓰기 2번-->  
하느님이 보우하사 우리나라 만세  <!--띄어쓰기 2번-->  
(줄바꿈 위치에서 **space 두 번** 입력)

<br />

동해물과 백두산이 마르고 닳도록<br />
하느님이 보우하사 우리나라 만세<br />
(줄바꿈 위치에서 `<br />` 태그 사용)

<br />

## 강조

_이텔릭_  
**두껍게**  
**_이텔릭+두껍게_**  
~~취소선~~  
<u>밑줄</u>

<br />

## 목록

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록

<br />

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

<br />

## 링크

### 일반 링크

[Google](https://www.google.com/)

### title 옵션 추가 링크

[Google](https://www.google.com/ "Google로 이동!")

<br />

## 이미지

### 이미지 삽입

![Web-Development](https://t1.daumcdn.net/cfile/tistory/22564A3B564AAFD733)

### 이미지에 링크 삽입

[![Web-Development](https://t1.daumcdn.net/cfile/tistory/22564A3B564AAFD733)](https://blog.lgcns.com/959)

<br />

## 인용문

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>
> > 중첩된 인용문
> >
> > > 중중첩된 인용문 1  
> > > 중중첩된 인용문 2  
> > > 중중첩된 인용문 3

<br />

## 코드 강조

### 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

### 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank">Google</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = "AAA";
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

<br />

## 표

### 왼쪽 정렬(기본값)

**position 속성**

| 값       | 의미              | 기본값 |
| -------- | ----------------- | ------ |
| static   | 기준 없음         | O      |
| relative | 요소 자신         | X      |
| absolute | 위치 상 부모 요소 | X      |
| fixed    | 뷰포트            | X      |

### 가운데 정렬

**position 속성**

|    값    |       의미        | 기본값 |
| :------: | :---------------: | :----: |
|  static  |     기준 없음     |   O    |
| relative |     요소 자신     |   X    |
| absolute | 위치 상 부모 요소 |   X    |
|  fixed   |      뷰포트       |   X    |

### 오른쪽 정렬

**position 속성**

|       값 |              의미 | 기본값 |
| -------: | ----------------: | -----: |
|   static |         기준 없음 |      O |
| relative |         요소 자신 |      X |
| absolute | 위치 상 부모 요소 |      X |
|    fixed |            뷰포트 |      X |

<br />

## 원시 HTML

동해물과 <u>백두산</u>이 마르고 닳도록
<br />
하느님이 보우하사 <span style="text-decoration: underline;">우리나라</span> 만세

<a href="https://www.google.com" title="Google로 이동!" target="_blank">Google</a>

<img width="250" src="https://t1.daumcdn.net/cfile/tistory/22564A3B564AAFD733" alt="Web-Development">

<br />

## 수평선

---

---

---
