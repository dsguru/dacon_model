---
title: 파이썬(Python) 대입 연산자에 대한 설명과 예시
date: 2023-11-29 20:20
author: 
categories: 
tags: 
toc:
---
## 1. 개요
---
지금까지 산술 연산자, 비교 연산자, 논리 연산자에 대해 정리했습니다.
오늘은 파이썬에서 사용하는 대입 연산자에 대해 알아보고 정리해보았습니다.



## 2. 대입 연산자(Assignment Operator)란?
---
대입 연산자는 프로그래밍 언어에서 변수에 값을 할당하는 데 사용합니다. 다시 말해 변수에 값을 대입할 때 사용하는 연산자입니다.
대입 연산자를 어떻게 사용하냐에 따라 코드 작성과 메모리를 효율적으로 관리할 수 있습니다.



## 3. 대입 연산자 종류
---
파이썬에서 대입 연산자는 크게 단순 대입 연산자와 복합 대입 연산자가 있습니다.

단순 대입 연산자의 경우 변수에 값을 할당하는 가장 기본적인 연산자입니다. `=` 기호를 사용하여 변수에 특정 값을 할당하는 것입니다.

- `=` : 왼쪽의 변수에 오른쪽의 값을 대입하는 연산자

복합 대입 연산자는 연산 후에 값을 할당하는 연산자로, 산술 연산자와 함께 사용합니다.

- `+=` : 왼쪽 변수에 오른쪽의 값을 더한 후, 그 결괏값을 왼쪽의 변수에 대입합니다.
- `-=` : 왼쪽 변수에 오른쪽의 값을 뺀 후, 그 결괏값을 왼쪽의 변수에 대입합니다.
- `*=` : 왼쪽 변수에 오른쪽의 값을 곱한 후, 그 결괏값을 왼쪽의 변수에 대입합니다.
- `/=` : 왼쪽 변수에 오른쪽의 값을 나눈 후, 그 결괏값을 왼쪽의 변수에 대입합니다.
- `%=` : 왼쪽 변수를 오른쪽의 값으로 나눈 후, 그 나머지를 왼쪽 변수에 대입합니다.
- `**=` : 왼쪽 변숫값을 오른쪽의 값만큼 지수승한 후 왼쪽의 변수에 대입합니다.
- `//=` : 왼쪽의 변숫값을 오른쪽 수로 나눈 후 내림한 값을 왼쪽 변수에 대입합니다.



## 4. 예시
---
파이썬으로 간단하게 예시를 들어보겠습니다.

```Python
# 단순 대입 연산자
a = 2
b = 2

# 복합 대입 연산자
a += b  # a = a + b
a -= b # a = a - b
a *= b # a = a * b
a /= b # a = a / b
a %= b # a = a % b
a **= b # a = a ** b
a //= b # a = a // b
```



## 5. 결론
---
대입 연산자는 변수에 값을 할당하는 주된 방법입니다. 프로그래밍을 하는데 사용하지 않을 수 없죠.
지금까지 대입 연산자에 대해 알아보았습니다. 마지막 연산자 관련 글은 비트 연산자를 마지막으로 작성할 것 같네요.