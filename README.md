Python 기본 문법 정리
----
# 변수 선언 & 할당  
  ### 사용  
    프로그램에서 데이터 저장하고 참조해야 할 때 사용  
    변수 값을 할당함으로써, 해당 값을 나중에 이름을 통해 쉽게 찾아 사용할 수 있음  

  ### 목적  
    데이터 저장, 프로그램의 다른 부분에서 그 데이터를 재사용하기 위함    


# 기본 자료형  
  ### int  
    정수 값 저장할 때 사용  
    ex) 사람의 나이, 물건의 개수 등 표현할 때 사용  

  ### float  
    실수 값을 저장할 때 사용  
    ex) 길이의 무게, 온도 등을 정확하게 표현할 때 사용  

  ## #str  
    문자열 데이터 저장할 때 사용  
    ex) 사용자의 이름, 도시의 이름 등 텍스트 정보를 저장할 때 사용  

  ### bool  
    논리적인 값을 저장할 때 사용  
    조건문에서 특정 조건이 참(True)인지 거짓(False)인지 판단할 때 사용  

# 연산자  
  ### 산술 연산자(+, -, *, / 등)  
    수학적 계산을 할 때 사용  
    ex) 두 수의 합을 구하거나, 어떤 값을 다른 값으로 나누어 평균을 구할 때 사용  

  ### 비교 연산자(==, ! =, ≠, <, >)  
    두 값이나 표현식을 비교할 때 사용  
    조건문에서 특정 조건을 만족하는지 확인하기 위해 사용 → 이를 통해 결정 구조를 구성  

  ### 논리 연산자(and, or, not)  
    두 조건이나 여러 조건을 조합할 때 사용  
    ex) 사용자가 특정 연령 이상이면서 회원인 경우에만 접근을 허용하는 등의 복잡한 조건을 표현할 때 사용  

# 변수 & 데이터 타입  
  ### 파이썬에서 변수 선언할 때 특별한 키워드 없이 바로 할당할 수 없음  
  ### 데이터 타입은 자동으로 인식됨  
---
x = 10              # int
y = 20.5            # float
name = "Alice"      #str
is_student = True   #bool
---

# 리스트, 튜플, 딕셔너리  
  ###리스트(List) : 변경 가능(mutable)한 데이터 컬렉션  
  ###튜플(Tuple) : 변경 불가능한(immutable)한 데이터 컬렉션  
  ###딕셔너리(Dictionary) : 키 - 값 쌍으로 이루어진 데이터 컬렉션  
---   
# 리스트  
fruits = ["apple", "banana", "cherry"]  
print(fruits[0])   #apple  

# 튜플  
coordinates = (10, 20)  
print(coordinates[1])  #20  

# 딕셔너리  
person = {"name" : "John", "age" : 30}  
print(person["name"])   #John  
---

# 제어 구조  
  ### 조건문 ( if - else ) : 조건에 따라 코드의 실행 경로를 결정  
  ### 반복문 (  for, while ) : 코드 블록을 여러 번 실행함  
---

# if - else 조건문  
age = 20  
if age >= 18:  
   print("You are an adult")  
else:  
   print("You are a minor")  
   
# for 반복문  
for fruit in fruits:  
   print(fruis)  
   
# while 반복문  
i = 0  
while i < len(fruits):  
   print(fruits[i])  
   i += 1  
---

# 함수  
  ### 파이썬에서 함수는 def 키워드를 사용하여 정의함  
  ### 함수는 코드의 재 사용성을 높여줌  
---  
def greet(name):  
      print("Hello, " + name + "!")  

greet("Alice")  
---  
