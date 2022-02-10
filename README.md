# Tutorial
###테스트

## 마크다운(markdown)?
일반 텍스트 기반의 마크업언어로 README.md 파일이나 온라인 문서, 혹은 일반 텍스트 편집기로 문서 양식을 편집할 때 쉽게 쓰고 읽을 수 있으며 HTML로 변환이 가능하다.

## 문단 구분을 위한 강제 개행

문장을 작성하면 됩니다.(공백을 안 두면..) 
빈 줄이 없으면 자동으로 앞의 문장 뒤에 붙습니다.(Space Bar를 두 번 이상 눌러 띄어쓰기를 하면..)   
위 문장에서 두 칸의 공백을 두어 강제 개행할 수 있습니다.

# 헤더 크기 (h1) 
## 헤더 크기 (h2) 
### 헤더 크기 (h3) 
#### 헤더 크기 (h4) 
##### 헤더 크기 (h5) 
###### 해더 크기 (h6)

## 목록(Lists)

Unordered 
* Item 1 
* Item 2 
    * Item 2a 
    * Item 2b 

Ordered 
1. Item 1 
1. Item 2 
1. Item 3 
    1. Item 3a 
    1. Item 3b

## 하이퍼링크(Links)

[GitHub](http://github.com "깃허브")

## 코드 블록(Code Blocks)

```javascript 
function test() { 
 console.log("hello world!"); 
} 
```

## 인용 상자(Blockquotes)

As Grace Hopper said: 

> I’ve always been more interested. 
> in the future than in the past.

## 강조(Emphasis)

*This text will be italic* 
_This will also be italic_ 

**This text will be bold** 
__This will also be bold__ 

*You **can** combine them*

## 테이블 TABLES

First Header | Second Header 
------------ | ------------- 
Content cell 1 | Content cell 2 
Content column 1 | Content column 2

## 체크 박스(Task Lists)

- [x] this is a complete item 
- [ ] this is an incomplete item 
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported 
- [x] list syntax required (any unordered or ordered list supported)

## 인라인 코드(Inline code)

문단 중간에 `Code`를 넣을 수 있습니다. 
예를 들어 `printf("hello world!");` 이런 식으로 들어갑니다.

## 수평선(hr)

--- 
*** 
___

## 탈출 문자 (Backslash Escapes)

＼*literal asterisks＼* 
*literal asterisks* 
__＼*＼*Text＼*＼*__ 
_＼_Tom＼__

## 이모지(EMOJI) - 아이콘

GitHub supports emoji! 
:+1: :sparkles: :camel: :tada: 
:rocket: :metal: :octocat:
