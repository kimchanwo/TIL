## day3 복습

```
# for name in ["apple","banana","melon"]:
#     print(name)
#
# print("___________________________")
#
# for number in range(10): # 0 ~9까지
#     print(name)
#
# print("___________________________")
#
# for number in range(1, 10): # 1~9까지
#     print(number)
#
# print("___________________________")
#
# for number in range(1,10, 2):
#     print(number)
#
# print("___________________________")
#
# for number in [1,3,5,7,9]:
#     print(number)
#
# print("___________________________")
#
# for i in range(1,10,-2):
#     print(i)
#
# print("___________________________")
#
# string = "python"
# print(string.ljust(10))
# print(string.rjust(10))
# print(string.center(5))
#
# star = "*"
# for i in ["*****","****","***","**","*"]:
#     print(i)
#
#
# for i in range(1,10,2):
#     string = i*"*"
#     print(string.center(9))
#
# # abc=int(input("숫자입력:"))
#
#
# n=0
#
# score = [70, 90, 100, 50, 85]
# for i in score:
#     n += 1
#     if i >= 60:
#         print(f"{n}번 합격 {i}점")
#     else:
#         print(f"{n}번 불합격 {i}점")
#
#
# num = 0
# for i in range(3):
#     for y in range(5):
#         num +=1
#         print(num, end=" ")
#     print()
#
#
#
# for y in range(3):
#     for x in range(1, 5):
#         print(x + y * 4, end = ' ')
#     print()

# sum= 0
# for i in range(1,11):
#     print(i)
#     sum += i
#     print("1부터 10까지 누적된 숫자:%4.2f" %sum,)
#     print(f"1부터 10까지 누적된 숫자:{sum}")
#     print("1부터 10까지 누적된 숫자:{}".format(sum))
#
# print(f"1부터 10까지 누적된 숫자:{sum}")
#

# odd = 0
# for i in range(1,101,2):
#     odd += i
#     print(i)
# print(f"1부터 100까지 홀수 결과:{odd}")

# odd = 0
# even = 0
# for i in range(1,101):
#     if i % 2 == 0:
#         even += i
#         print(f"짝수 값{i}, 짝수 누적값{even}")
#     else:
#         odd += i
#         print(f"홀수 값{i}, 홀수 누적값{odd}")
#
# print(f"짝수 합계{even}, 홀수 합계{odd}")


# a = 0
# b = 0
# for i in range(1,101,2):
#     a += i
#     b += i+1
#     print(a, b)
#
# print(a)
# print(b)
#
# multiple =0
# for i in range(1,100):
#     if i %3 ==0:
#         print(i)
#         multiple +=i
# print(multiple)


# n = int(input("단수입력:"))
#
# for i in range(1,10):
#     times = n * i
#     print(f"{n}*{i}={times}")
#
#
#
# n = int(input("숫자입력:"))
# for i in range(n,0,-1):
#     print(i, end=" ")
# print("성공")
#

# plus = 0
# minus = 0
# zero = 0
#
# for i in range(1,11):
#     n = int(input(f"{i}번 정수입력:"))
#     if n>0:                   #if 가 있을때는 그냥 써도 된
#         print("양수입니다.")    # "="은 단독으로 못씀 if 든 아니는 하지만 앞에 변수 설정해주면 씀   times = n * i
#         plus += 1
#     elif n==0:
#         print("0입니다.")
#         zero += 1
#     else:
#         print("음수입니다.")
#         minus += 1
#
# print(f"양수의 개수{plus}개 0의 개수 {zero}개 음수의 개수{minus}개")
#


# names = ["베토벤","홍길동", "변학도", "아쿠아맨"]
# search_name = input("이름 입력")
#
# for i in names:
#     print(i)
#     if  search_name == i:
#         find = True
#         break
#     else:
#         find = False

# if find:
#     print('명단에 있어요')
# else:
#     print('명단에 없어요')

#
# num1=int(input("첫번쨰 정수:"))
# num2=int(input("두번쨰 정수:"))
# num3=int(input("세번쨰 정수:"))
#
# if num1 > num2 and num1 > num3 :
#     print(f"제일큰수{num1}")
# elif num2 > num3 :
#     print(f"제일큰수 {num2} ")
# else:
#     print(f"제일큰수 {num3} ")


# num1=int(input("첫번쨰 정수:"))
# num2=int(input("두번쨰 정수:"))
# num3=int(input("세번쨰 정수:"))
#
# if num1 > num2 and num1 > num3 :
#     maxNum=num1
# elif num2 > num3 :
#     maxNum = num2
# else:
#     maxNum = num3
#
# print('제일 큰 수 :', maxNum)


#
# n = int(input("도형 입력(1: 사각형, 2: 삼각형, 3: 원):"))
#
# if n==1:
#     side = int(input("가로입력:"))
#     high = int(input("높이입력:"))
#     area = side * high
#     print("사각형의 면적:%.2f" %area)
# elif n==2:
#     side = int(input("밑변입력:"))
#     high = int(input("높이입력:"))
#     area = side * high/2
#     print("삼각형의 면적:%.2f" %area)
# elif n==3:
#     radius = int(input("밑변입력:"))
#     area = radius*3.14
#     print("원의 면적:%.2f" %area)


# for i in range(1,11):
#     print(i, end = " ")
# print("\n________________")

# i = 1      # while 변수값 하나 지정해줘야함!
# while i<=10:
#     print(i, end=" ")
# print()

# i = 1 #전역변수     # while 변수값 하나 지정해줘야함!
# sumN = 0
# while i<=10:  #지역변수 이거 두개끼리 지역 변수가 되버린다. 전역변수 1을 먹는다
#     sumN += i   #지역변수 이거 두개끼리 지역 변수가 되버린다.
#     i += 1    #전역변수 여기서 이걸 안해주면 전역변수가 하나 빈다.
# print(sumN)
#
# print("___________________________")
#
#
# sumN = 0
# seven = int(input("숫자입력"))
# while seven != 7:
#     seven = int(input("숫자입력"))
#     sumN += seven
# print(f"{seven}, 입력 종료! 입력된 값 합{sumN}")

# sum = 0
# while True:
#     num= int(input("숫자입력:  "))  # 이건 초기값을 안주는 이유가 while True 이기때문에 안 줘도 된다.
#     if num ==7:                   # while ==7: 이런식이라면 초기값을 써줘야 한다.
#         break
#     sum += num
#     print(f"누적된 숫자:{sum}")
#
# print(num, "입력! 종료!")


# while 1:                         # True 1,  펄스는 0 이다 그래서 1 쓴거다!
#     num = int(input('숫자입력 : '))
#     if num == 7:
#         break
#
# print(num, '입력! 종료')
#



# while 1:
#     num = input("문자입력: ")
#     if num == "q":
#         break
#
# print(num,"입력종료!")
#
#
# count = 0
#
# while True :
#     count += 1
#     money = 10000 - (2000 * count)
#     print(f"노래를 {count}곡 불렀습니다.")
#     print(f"현재 {money}원 남았습니다.")
#     if money == 0 :
#         print("잔액이 없습니다. 종료합니다.")
#         break
#
# count = 0
#
# while 1:
#     count += 1
#     money = 10000 -(2000*count)
#     print(f"노래 {count}곡 불렀습니다.")
#     print(f"현재 {money}원 남았습니다.")
#     if money == 0:
#         print("남은 돈을 모두 소비하였습니다.")
#         break
#
#


#
# from random import randint
#
# n = randint(1, 10)
# print(n)



# a=100; a=a<<100 ; print(a)



# 1. 진수 아직 못품


#2. 다음 실행결과와 같이 입력한 금액을 5만원, 1만원, 5천원, 1천원, 500원, 100원, 50원,
#10원 동전으로 교환하는 프로그램을 작성하시오.

#
# mey50000 = 0 ; mey10000 = 0; mey5000 = 0; mey1000 = 0; mey500 = 0;mey10 = 0 ; mey5 = 0; mey1 = 0
# num = int(input("교환할 돈은 얼마?"))
# mey50000 += num // 50000
# money =+ num % 50000
# mey10000 += money // 10000
# money2 = + money % 10000
# mey5000 += money2 // 5000
# money3 = + money2 % 5000
# mey1000 += money3 // 1000
# money4 = + money3 % 1000
# mey500 += money4 // 500
# money5 = + money4 % 500
# mey10 += money5 // 100
# money6 = + money5 % 100
# mey5 += money6 // 50
# money7 = + money6 % 50
# mey1 += money7 // 10
# money8 = + money7 % 10
# print(f"교환한 돈은 얼마?{num}원 50000원,  {mey50000}장, 10000원 {mey10000}장, 5000원 {mey5000}장, 1000원 {mey1000}장, 500원 {mey500}장, 100원 {mey10}장, 50원 {mey5}장,10원 {mey1}장")
# print(f"바꾸지못한돈{money8}")


# mey50000 = 0 ; mey10000 = 0; mey5000 = 0; mey1000 = 0; mey500 = 0;mey10 = 0 ; mey5 = 0; mey1 = 0
# num = int(input("교환할 돈은 얼마?"))
# mey50000 = num // 50000 ; num %= 50000
# mey10000 = num // 10000 ;num %= 10000
# mey5000 = num // 5000 ; num %= 5000
# mey1000 = num // 1000 ; num %= 1000
# mey500 = num // 500 ; num %= 500
# mey10 = num // 100 ; num %= 100
# mey5 = num // 50  ; num %= 50
# mey1 = num // 10  ; num %= 10
# print(f"교환한 돈은 얼마?{num}원 50000원,  {mey50000}장, 10000원 {mey10000}장, 5000원 {mey5000}장, 1000원 {mey1000}장, 500원 {mey500}장, 100원 {mey10}장, 50원 {mey5}장,10원 {mey1}장")
#



#
# change = int(input("교환할 돈은 얼마 ? "))
# m_list = [50000, 10000, 5000, 1000, 500, 100, 50, 10]
#
# for m in m_list:
#     cnt = change // m
#     change %= m
#     if m != 10:
#         print(f'{m}원 {cnt}장', end = ', ')
#     else :
#         print(f'{m}원 {cnt}장')
#         print(f"바꾸지 못한 돈 ==> {change}원")

#

# 3
# from random import randint
#
# a = randint(1,6)
# b = randint(1,6)
# if a < b:
#     print(f"A의 주사위 숫자는{a}입니다.\nB의 주사위 숫자는{b}입니다. \nA가 이겼다.")
# else:
#     print(f"A의 주사위 숫자는{a}입니다.\nB의 주사위 숫자는{b}입니다. \nb가 이겼다.")



# for i in range(5,0,-1):
#     i *= "*"
#     print(i)

for i in range(5,0,-1):
    for g in range(i):
        print("*", end =" ")
    print()


#
# for i in range(1,9):
#     i *= "*"
#     print(i)
```