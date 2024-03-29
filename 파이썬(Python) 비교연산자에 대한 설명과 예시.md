---
title: 파이썬(Python) 비교연산자에 대한 설명과 예시
date: 2023-11-28 19:50
author: 
categories: 
tags: 
toc:
---

## 1. 개요
---
파이썬에서 데이터를 비교하고 조건을 평가하기 위해 '비교연산자'를 사용합니다.
조건문이나 반복문 등 여러 상황에서 사용하는 연산자여서 한 번 정리해봤습니다.



## 2. 비교연산자란?
---
파이썬에서 비교연산자는 데이터를 비교하고 조건을 평가하기 위해 사용되는 기호들입니다. 다시 말해 두 피연산자가 같은지 다른지를 비교하는 연산자입니다.



## 3. 비교연산자의 종류
---
- `>` : 왼쪽에 있는 값이 오른쪽에 있는 값보다 크면 참을 반환하고, 아니면 거짓을 반환합니다.
- `<` : 왼쪽에 있는 값이 오른쪽에 있는 값보다 작으면 참을 반환하고, 아니면 거짓을 반환합니다.
- `>=` : 왼쪽에 있는 값이 오른쪽에 있는 값보다 크거나 같으면 참을 반환하고, 아니면 거짓을 반환합니다.
- `<=` : 왼쪽에 있는 값이 오른쪽에 있는 값보다 작거나 같으면 참을 반환하고, 아니면 거짓을 반환합니다.
- `==` : 왼쪽에 있는 값이 오른쪽에 있는 값과 같으면 참을 반환하고, 아니면 거짓을 반환합니다.
- `!=` : 왼쪽에 있는 값이 오른쪽에 있는 값과 다르면 참을 반환하고, 아니면 거짓을 반환합니다.

비교연산자는 조건을 평가하고 결과를 `boolean` 값을 반환합니다. 주어진 조건이 참이면 `True`를, 아니면 `False`를 반환합니다.



## 4. 예시
---
간단하게 예시를 들어보겠습니다.

- 예시 코드
```python
a = 5
b = 7

print(a > b) # False
print(a < b) # True
print(a >= b) # False
print(a <= b) # True
print(a == b) # False
print(a != b) # True
```

조건문에서도 활용할 수 있습니다.

- 예시 코드
```python
age = 25
if age >= 18:
	print("성인입니다.")
else:
	print("미성년자입니다.")
```

위 코드는 나이가 18세 이상이면 "성인입니다." 를 출력하고 아니면 "미성년자입니다."를 출력합니다.
`age` 값이 25이기 때문에 "성인입니다."를 반환하겠네요.



## 5. 결론
---
지금까지 비교연산자에 대해 알아봤습니다. 프로그래밍을 하다보면 많이 사용하는 연산자여서 한 번 정리해보았습니다.