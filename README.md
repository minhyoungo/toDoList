# work

## Requirements

html, css, js

- variable, object

## Requirements

- Momentum

## Your first JS Variable

- 변수

  - a=2
  - b= a-1
  - result -> 1

- Create -> Initialize -> Use

- let 초기화

처음에 a에 10 을 넣어도 다음 코드에서 1을 넣으면 a는 1이 된다.

    ex)
    let a=10
    let b= a-1
    let a= 1
    console.log("a, b")
    result -> 9 1

## let, const, var

- const

  - 변수의 값이 변하지 않길 원할 떄 사용
  - 상수
  - 값이 변함x
  - 위에서 써진 코드에서 a 앞에 const였다면 에러남

- var
  - 값이 변함 o

## Data Types on JS

- 코맨트

  - 주석
  - 주석 처리 된 모든 코드는 프로그램이 실행하려고 하지 않는다.
  - 메모 기능
  - // ~~~~
  - // ~~~~ //

- 변수를 선언 할때는 const를 사용한다.
- 필요하기 전까지는 let을 사용하지 않는다.

- 데이터 타입
  - String : 택스트
    Boolian : true or false / NOT TEXT
    Number : 1, 2, 3, 4, ... / NOT " "
    Float : 떠돌이 소숫점 / ex) 55.1

## Organizing Data

- camel case

  1. 소문자로 시작
  2. 띄어쓰기가 필요한 부분에서 다음단어의 첫번째 문자를 대문자로 해주는 것으로 대신함

  - ex) lowerOfWeek

* 데이터 타입 정렬

  - Array

    - 데이터를 리스트처럼 저장
    - ex) const dayOfWeek =["Mon", "Tue", "Wed", "Thu", "Fri", "sat", "Sun"] / console.log(dayOfWeek[2]) / Wed
    - 0부터 카운트 시작

- Object

  - ex) const omhInfo = {
    name:"OMH",
    age:18,
    gender:"Male",
    isHandsome: true
    }
    console.log(omhInfo.gender)

    Result : Male

    - 원한다면 바꾸기 가능
      - ex) omhInfo.gender = female

* Array 안에 Object

  - ex) const asdf {
    abc : ["A", "B", "C"]
    def : ["D", "E", "F"]

    console.log(asdf)
    }

## Your first JS Function

- function

  - 가져다가 사용할 수 있는 한 조각의 코드
  - ex) function say Hello() {
    console.logo{"Hello!"}
    }

  sayHello();

- argument

  - 함수 뒤에 붙은 괄호 안에 들어가는것
  - 변수와 비슷함 우리가 주는 값을 저장
  - 함술ㄹ 써주는 시점에서 ()에 이름을 넣는다.

  - ex) function say Hello(potato) {
    console.logo{"Hello!", potato}
    }

  sayHello ("OMH")

  result : Hello OMH

  - OMH 라는 데이터가 potato에 담기고 실행 할때 그 담긴 값이 나오면서 콘솔에 다음과 같이 찍히는 것이다.

  ## More Function Fun

* function

  - function sayHello(name, age) {
    console.log(`Hello ${name} you are ${age} years old`);
    }
    const greetOMh = sayHello("OMH", 15);
    console.log(greetOmh)
  - greetOmh는 sayHello의 리턴값이다.

* calculator

  - const calculator = {
    plus: function (a, b) {
    return a + b;
    },
    };

  const plus = calculator.plus(5, 5);
  console.log(plus);

## DOM Function

- 타이틀 변경하기
  1. DOM을 title라는 변수에 담는다.
  2. 변수이름.innertext = "바꿀 내용" 으로 바꾼다.

## Modifying the DOM with JS

- console.dir : 이벤트를 보여준다.

- querySelector
  - 노드의 첫번째 자식을 반환한다. 즉 document로 가서 모든 자식들중에서 찾으러고 한다.

## Events and event handlers

- js의 탄생 이유

  1. html과 css를 바꾸기 위해
  2. 이벤트애 반응 하기 위해서

- 이벤트 : 웹사이트에서 발생하는 것들

  - ex) click, resize, submit, input chane ....

## If, else, and, or

- if, else

  - if(조건){
    실행할 코드1
    } else{
    실행할 코드2
    }

- 조건이 참이면 코드1이 조건이 거짓이면 코드2가 실행된다.

- else if로 더 많은 조건문을 만들 수 있다.

  - ex) if(조건1) {
    코드1
    } else if(조건2) {
    코드2
    } else {
    코드3
    }

- 조건문에서의 &&

  - 하나의 조건문에 조건을 더 추가해서 걸 수 있다.
  - ex) if(20===20 && "A"==="B") {
    코드1
    }

  - 위와 같은 상황에서 두개의 조건중 두번재 조건이 거짓이므로 코드1은 실행되지 않는다.
    (즉 &&로 조건을 추가했을 시에는 모든 조건이 충족 되야 밑에 있는 코드가 실행 된다.)

  - and

- 조건문에서의 ||

- 하나의 조건문에 조건을 더 추가해서 걸 수 있다.
- ex) if(20===20 || "A"==="B") {
  코드1
  }

- 위와 같은 상황에서 두개의 조건중 하나라도 참이 되므로 코드1은 실행된다.
  (즉 ||로 조건을 추가했을 시에는 한 조건이라도 충족 되면 밑에 있는 코드가 실행 된다.)

- or

- 조건문에서의 변수의 사용

  - 변수에 데이터를 담고 조건문에서 사용한다.
  - ex) const abc = 15
    if(abc > 10)

## DOM - If else - Function practice
