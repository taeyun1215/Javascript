# Javascript

### Javascript 기본 문법

#### 1. 변수
- 변수(Variable)는 값(value)을 저장(할당)하고 그 저장된 값을 참조하기 위해 사용한다.
- 변수를 선언할 때 var 키워드를 사용한다. 할당 연산자 =는 변수에 값을 할당하기 위해 사용한다.

```JavaScript
var x; // 변수의 선언
x = 6; // 정수값의 할당
```

```JavaScript
var a;
var b = 123;
var c = "123";
var d = false;
var e = null;
```

- 최신 자바스크립트에선 let이라는 가변형 블럭 지역 변수와 const라는 불변형 블럭 지역 변수가 추가되었다.

```JavaScript
let x = 123;
x = "123";

const y = false;
y = null; // error
```

#### 2. 연산자
- +, -, *, /, % 등의 기본 연산은 물론 ++, --와 같은 증감 연산자도 사용할 수 있다.

```JavaScript
a = a + 1 (x)
a += 1 (o)
```

- 자바스크립트에서 a = a + 1 과 같은 표현은 쓰지 말라고 돼있다.
  - - [ ] 안되는 이유 확인하기
- 자바스크립트는 자바와 마찬가지로 스트링 컨케트네이션이 되므로 문자열을 덧셈기호로 간단히 붙힐 수 있다.

```JavaScript
var s = "String1" + "String2";
console.log(s); // String1String2
```

#### 3. 조건문
- ==, !=, &&, ||, >, < 등의 기본 관계연산자를 사용하여 조건문을 만들수 있다.

```JavaScript
a==b
a!=b
a==b && a==c
a==b || a==c
a > b
```

```JavaScript
if (a > b) {
    console.log("a is more than b.")
} else if (a == b) {
    console.log("a is the same as b.")
} else {
    console.log("a is less than b.")
}
```





[참고 링크] https://blex.me/@baealex/%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8javascript-%EA%B8%B0%EB%B3%B8-%EB%AC%B8%EB%B2%95-%EC%A0%95%EB%A6%AC







