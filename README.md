# javascript-study [Day 1]
-------------------------------------------------------------------------

## const와 let의 차이점
1. const는 constant(상수)라는 것이고, 값이 바뀔 수 없다. 만약 const로 variable을 만들었다면, 절대 값을 업데이트 할 수 없음!
2. let은 변수에 재할당이 가능함.
3. const와 let이 생기기 전엔 var만 있었음. var는 생성되고 나서 원할 때 언제든지 업데이트 할 수 있음.      <문제점> 언어를 통한 보호를 받지 못함. 업데이트를 해도 말해주지 않음 = const와 let이 생긴 이유!
6. 규칙! 기본적으로 const를 쓰고 필요할 때만 let을 쓰되, var는 쓰지 말 것.


## null은 '아무것도 없음'을 의미 
>그 변수에 아무것도 없다는 것을 뜻함 
>> false랑 다름.
>>>(false는 false라는 값이 존재하는 것. null은 여기 아무것도 없다는 것. 비어있다기 보다는 아무것도 없는 상태로 채워진 것!!!!

## undefined는 컴퓨터 메모리 안에는 존재하고 공간이 있는데 값이 들어가지 않은 것.
```javascript
let something; 
```
something이라는 variable을 만들고 있지만, 값을 주고 있지 않은 상태

## 기억해야할 것 ! 
>null은 절대 자연적으로 발생하지 않음. 
- null은 우리가 variable 안에 어떤 것이 없다는 것을 확실히 하기 위해 쓰는 것. 여기엔 값이 "없다"라는 것을 알려줄 때 씀 = "비어있어요"를 의도적으로 표현하는 것
------------------------------------------------------

## 자바스크립트 array로 나열할 때 지켜야 할 규칙
1. 시작과 끝에 대괄호 []를 사용해야 함.
2. array안 각각의 항목은 쉼표로 분리되어야 함.

## array 만드는 방법
대괄호[] 를 사용하고 문자나 값 뭐든 입력 전에 대괄호 열어주고 끝에 닫아주기.
array 안 데이터에 접근하고 싶다면, variable의 이름을 적어주고 array를 갖는 variable 이름을 적고
대괄호를 열어서 우리가 얻고 싶은 항목의 번호를 넣고, 대괄호 닫아주기!

push 쓰면 항목 하나를 array안에 추가됨.
ex) daysOfWeek.push("sun");

![image](https://user-images.githubusercontent.com/93191287/138886853-5663212f-5220-4c94-bab6-0b6cf021c688.png)

## array의 목적 
하나의 variable 안에 데이터의 list를 가지는 것



