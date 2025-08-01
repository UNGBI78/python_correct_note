# 문제 제목: 합

## 문제 정보
- **출처:** https://www.acmicpc.net/problem/8393
- **난이도:** Medium

## 문제 설명
n이 주어졌을 때, 1부터 n까지 합을 구하는 프로그램을 작성하시오.

## 해결 과정
많은 문제를 풀어본건 아니였지만 늘 그렇듯 반복문을 만드는게 정말 어렵다. 우선 한줄씩 차근차근 어떻게 쌓아 나가야 하는지 접근했다.

### 접근 방법
n이 10000 이하긴 하지만 얼마나 주어질지 모르므로 for 함수로 접근했다. 그 후, 0의 할당값을 지닌 변수를 하나 만들어서 그 변수에 정답을 쌓아가도록 접근했다.

## 코드
```python

n = int(input())

if n <= 10000:
    x = 0
    for i in range(1, n + 1):
        x = x + i  

    result = int(x)
    print(result)
else:
    pass

<img width="738" height="352" alt="image" src="https://github.com/user-attachments/assets/cfdd6762-ece4-459f-b05e-8f5266620bfb" />
