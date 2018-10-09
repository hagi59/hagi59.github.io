## 줄바꿈

### 줄바꿈 안됨

```
동해물과 백두산
이 마르고 닳도록
```

동해물과 백두산
이 마르고 닳도록

### 줄바꿈 '..'

```
동해물과 백두산..
이 마르고 닳도록
```

동해물과 백두산..
이 마르고 닳도록

## 제목의 표시

```
This is an H1
=============

This is an H2
-------------

# This is an H1
## This is an H2
### This is an H3
#### This is an H4
##### This is an H5
###### This is an H6
```

This is an H1
=============

This is an H2
-------------

# This is an H1
## This is an H2
### This is an H3
#### This is an H4
##### This is an H5
###### This is an H6

## 글자 강조

```
*italic*
_italic_

**bold**
__bold__

++underline++
<U>underline</U>

~~cancelline~~
```

*italic*
_italic_

**bold**
__bold__

++underline++
<U>underline</U>

~~cancelline~~

## 인용

```
> This is first blockquote
>> This is second blockquote
>>> This is Third blockquote
>>>> This is 4th blockquote
```

> This is first blockquote
>> This is second blockquote
>>> This is Third blockquote
>>>> This is 4th blockquote

## 리스트

```
1. item1
1. item2
1. item3

- item1
* item2
+ item3


- item1
  - item1
    - item1
```

1. item1
1. item2
1. item3

- item1
* item2
+ item3


- item1
  - item1
    - item1

## 코드삽입

### 일반적인 코드
````
```
This is a code Block 
```
````

~~~~
~~~
This is a code Block
~~~
~~~~

```
일반 문단에서 한줄 띄고:

    4개의 공백 또는 탭을 치면 소스가 됩니다.
```

``` 
This is a code Block 
```

~~~
This is a code Block
~~~

일반 문단에서 한줄 띄고:

    4개의 공백 또는 탭을 치면 소스가 됩니다.

### 언어 지정
~~~c
void f() {
  printf(%s, "이것은 C코드 입니다");
}
~~~

~~~python
def f:
  print("이것은 파이썬 코드입니다")
~~~

### 인라인 코드

`````
`This is an inline code block`

마크다운 코드블럭을 `<pre>`와 `<code>`로 감쌉니다.


``` This is an inline code Block ```

`````

`This is an inline code block`

마크다운 코드블럭을 `<pre>`와 `<code>`로 감쌉니다.


``` This is an inline code Block ```



## 수평선

```
* * *
***
*****
---
------
```

* * *
***
*****
---
------

## 링크


### 참조 링크

```
이 부분은 [Google][1]을 참조하시면 됩니다.
이 부분도 [Google][1]을 참조하시고 저 부분은 [Naver][2]를 참조하세요.

[1]: http://google.com "구글"
[2]: http://naver.com "네이버"

```

이 부분은 [Google][1]을 참조하시면 됩니다.
이 부분도 [Google][1]을 참조하시고 저 부분은 [Naver][2]를 참조하세요.

[1]: http://google.com "구글"
[2]: http://naver.com "네이버"

### 함축적 링크

```
이 부분은 [Google]을 참조하시면 됩니다.
이 부분도 [Google]을 참조하시고 저 부분은 [Naver]를 참조하세요.

[Google]: http://google.com "구글"
[Naver]: http://naver.com "네이버"
```

이 부분은 [Google]을 참조하시면 됩니다.
이 부분도 [Google]을 참조하시고 저 부분은 [Naver]를 참조하세요.

[Google]: http://google.com "구글"
[Naver]: http://naver.com "네이버"


### 인라인 주소 삽입

```
이 부분은 [Google](http://www.google.com)을 참조하시면 됩니다.
이 부분도 [Google](http://www.google.com)을 참조하시고 저 부분은 [Naver](http://www.naver.com)를 참조하세요.
```

이 부분은 [Google](http://www.google.com)을 참조하시면 됩니다.
이 부분도 [Google](http://www.google.com)을 참조하시고 저 부분은 [Naver](http://www.naver.com)를 참조하세요.

### URL 링크 삽입

```
<https://google.com/>
<example@gmail.com>
```
<https://google.com/>
<example@gmail.com>

### Internal(anchored) 링크 삽입
```
[ URL 링크 삽입으로 이동](###-url-링크-삽입)

[ 다른 파일로 이동](jekylltest.md#-이건-헤드1)
```
[ URL 링크 삽입으로 이동](###-url-링크-삽입)

[ 다른 파일로 이동](jekylltest.md#-이건-헤드1)


## 이미지 삽입
인라인 주소 삽입문법과 유사함. 그 앞에 ! 가 추가되어야 함.


### 참조 이미지 삽입

```
![alt text][id]
![Github][logo]

[id]: /test.png
[logo]: https://assets-cdn.github.com/images/modules/open_graph/github-octocat.png

```
![alt text][id]
![Github][logo]

[id]: /test.png
[logo]: https://assets-cdn.github.com/images/modules/open_graph/github-octocat.png


### 인라인 이미지 삽입
```
![alt text](imgae_URL)

![Github](https://assets-cdn.github.com/images/modules/open_graph/github-octocat.png)
```

![alt text](imgae_URL)

![Github](https://assets-cdn.github.com/images/modules/open_graph/github-octocat.png)


## 표

### 표 기본

```
Header 1  | Header 2
----------|----------
Content 1 | Content 2
Content 3 | Content 4
```

Header 1  | Header 2
----------|----------
Content 1 | Content 2
Content 3 | Content 4


### 표 정렬
```
| Header 1 | Header 2 | Headre 3 |
|---------:|:--------:|:-------- |
|  Right   |  Center  |   Left   |
```

| Header 1 | Header 2 | Headre 3 |
|---------:|:--------:|:-------- |
|  Right   |  Center  |   Left   |

### 각주

```
각주입니다[^id]
[^id]: 각주에 대한 설명
```

각주입니다[^id]
[^id]: 각주에 대한 설명
