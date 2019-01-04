---
layout: post
title: Mastering Markdown, 마크다운 작성법
---

최근 들어 자주 사용하는 Markdown 문법 정리

## 제목
![](https://help.github.com/assets/images/help/writing/headings-rendered.png)
 ```
# The largest heading
## The second largest heading
###### The smallest heading
``` 
  

## 문자 스타일
**Bold** - ```**Bold**```

*Italic* - ```*Italic*```

~~Strikethrough~~ - ```~~Strikethrough~~```
  

## 블럭
> Pardon my French
```
> Pardon my French
```

## 리스트
**Unordered**
- George Washington
- John Adams
```
- George Washington
- John Adams
```

**Ordered**
1. James Madison
2. James Monroe

```
1. James Madison
2. James Monroe
```
1. First list item
   - First nested list item
     - Second nested list item

```
1. First list item
   - First nested list item
     - Second nested list item
```
 
## 코드

**Inline code**
Use `git status` to list all new or modified files that haven't yet been committed.
```
Use `git status` to list all new or modified files that haven't yet been committed.
```

**Inline code**
```
git status
git add
git commit
```
**code blocks**
```
```git status
git add
git commit```
```

**Syntax highlighting**
```
```java
Toolbar toolbar = findViewById(R.id.toolbar);
setSupportActionBar(toolbar)```
```

```java
Toolbar toolbar = findViewById(R.id.toolbar);
setSupportActionBar(toolbar);
```

## 링크
This site was built using [GitHub Pages](https://pages.github.com/).

```
[GitHub Pages](https://pages.github.com/)
```
  
## 이미지
```![GitHub Logo](/images/logo.png)```

## 이모지
:smile: :grinning: :blush: :heart_eyes: :yum:
```
:smile: :grinning: :blush: :heart_eyes: :yum:
```


## 에디터
[https://stackedit.io/app](https://stackedit.io/app)
실시간으로 적용 화면을 확인할 수 있음



## 참고 하면 좋은글
-  [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)

-  [https://help.github.com/articles/basic-writing-and-formatting-syntax](https://help.github.com/articles/basic-writing-and-formatting-syntax)