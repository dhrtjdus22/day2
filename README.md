### day2
-------------------------------------------------------------------------

int() = 자료형을 정수로 변형   
str() = 자료형을 문자로 변형   
float() = 자료형을 소수로 변형   

-------------------------------------------------------------------------

```
score = int(input('점수를 입력하세요 : '))

if score>100 :
    print('점수를 다시 입력해주세요')
else :
    if score >= 90 :
        print('A')
    elif score >= 80 :
        print('B')
    elif score >= 70 :
        print('C')
    else :
        print ('F')
```
-------------------------------------------------------------------------

```name = '홍길동'
addr = '서울'
age = 20
print("내 이름은 {}이고, 주소는 {} 이고 나이는 {}".format(name,addr,age))
```

결과 : 내 이름은 홍길동이고, 주소는 서울 이고 나이는 20

-------------------------------------------------------------------------
