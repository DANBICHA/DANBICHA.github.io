---
layout: post
title:  "[부산대 공학교육거점센터] 파이썬 기반 데이터 프로그래밍 1차시"
date:   2021-03-04
excerpt: "파이썬 기반 데이터프로그래밍_python primer"
tag:
- python
- dataprogramming
- datascience
- soltrux
comments: true
---

## PYTHON PRIMER part1

```python
# an example of a dataframe in which python code can be executed in a browser

# variable x is assigned value 10
x = 10

# variable y is assigned value 20
y = 20

# print the result of expressing that x is equal to y (False as x does not equal y)
print(x == y)
```

x와 y가 동일 값인지 확인  
결과값 : `TRUE` or `FALSE`

```python
# variable 'text' is assigned the string 'x * y ='
text = 'x * y ='

# print the value of variable 'text' followed by the sum of 'x * y', each of which have previously been defined
print(text, (x * y))
```
text에 'x\*y' 문자 할당시키기
print함수를 이용하여 위의 할당시킨 `text 문자열`과 (x\*y)로 `x와y를 곱한 결과값`을 프린트함
괄호 안에 연산식 넣으면 그대로 프린트 됨!

```python
# change the value of 'x' by assigning the value 20
x = 20

print(text, (x * y))

# print the result of expressing that x is equal to y (True as x does equal y)
print(x == y)

# print the output of the `print` function
print(print(x== y))
```
x에 새로운 값을 할당시켜 x와 y비교
`print(x==y)`의 결과값은 `TRUE`이므로, 
`print(print(x==y))`에서 결과값은 `NONE`이다.
