# IF문

> if 문 다음 if문 오면 다음으로 넘어간다. 
>
> if 다음  else 가와야 멈춘다.

## 문제 1

#### id와 password를 입력받아 모두 맞으면 로그인 성공 출력 그렇지 않으면 로그인 실패 출력

---

EX) 이부분은 첫째 if에서 아이디를 정확하게 치고 다음 if인 패스워드를 정확하게 치면 로그인 성공으로 뜬다 → if 다음 if가 나오면 첫번째 if 가 True 가 나와도 다음 if로 넘어간다. 

```python
id = input("아이디 입력: ")
pw = input("비밀번호 : ")

if id == "kahee78":
    if pw == "2170218":	
        print("로그인 성공")
    else:
        print("비밀먼호가 다릅니다.")
else:
    print("아이디가 다릅니다.")
```

## 문제 2

#### 정수를 입력받아서 홀수인지 짝수인지 판별하여 출력
----

EX)

```python
num = int(input('정수 입력 : '))
if num % 2 == 0:
    print('짝수')
else:
    print('홀수')
```
## 문제 3

####  입력한 정수가 음수, 0, 양수 인지를 확인하여 출력
---
EX) 이부분은 잘못되 예이다. 

1. 입력값: 5 = "5"를 입력하면  양수,음수 입니다. 가 뜬다 왜냐하면  if 다음이  if이기때문에 확인을 한다. 입력 값이 "5"이기 때문에  false가 나오고 끝난줄 알았지만 파이썬은 if 가 아닌걸 인식 했기 때문에 else 로 넘어가서 음수입니다. 까지 출력해버린다.

```python
integer = int(input("정수를 입력하세요: "))
if integer > 0:
    print("양수입니다.")
    if integer == 0:
        print("0입니다.")
    else:
        print("음수입니니다.")

```

EX)  올바른 예입니다.

1. 입력값: 5 = 입력값이 "5"이라면 첫번째 if에서 정답이 나오고  두번째 elif 에서 끝이난다.   => 양수입니다.

            2. 입력값: 0 = 입력값이 "0" 이라면  첫번째 if가 틀리고 elif로 넘어간다 그리고 입력값이 0이기 때문에 다음 else 에서 끝이난다.  => 0입니다.
        
         2. 입력값: -1 = 입력값이"-1"이라면 첫번째 if  → 두번째 elif → 세번째 else로 넘어가서 끝이 나게 된다. => 음수입니다.

```python
integer = int(input("정수를 입력하세요: "))
if integer > 0:
    print("양수입니다.")
elif integer == 0:
    print("0입니다.")
else:
    print("음수입니니다.")


 if num > 0:
     print('양수')
 elif num == 0:
     print('0')
 else:
     print('음수')
```


## 문제 4

####  문제 : 점수를 입력받아서 학점 출력 A, B, C, D, F
---

```python
score = float(input('점수입력: '))
if score >=90 and score <= 100:
    print('A')
elif 80 <= score < 90:
    print('B')
elif score >= 70:
    print('C')
elif score >= 60:
    print('D')
else:
    print('F')
    
grade= int(input("점수를 입력하세요: "))

if grade >= 90:
    print("A")
elif grade >= 80:
    print("B")
elif grade >= 70:
    print("C")
elif grade >= 60:
    print("D")
else:
    print("F")
    
    
```
## 문제 4

####  문제 : 점수를 입력받아서 학점 출력 A, B, C, D, F
---

```python
weight = float(input('몸무게(kg) :'))
height = float(input('키(미터) :'))
bmi = weight/(height*height)
# 출력
print('당신의 BMI는 {:.2f} 입니다.'.format(bmi))
print('당신의 BMI는 ', format(bmi, '.2f'), '입니다')
print(f"BMI 수치 : {BMI}")
```