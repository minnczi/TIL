# Javascript 기초 문법 2: 조건문과 반복문

## 조건문

### 조건문의 종류

- if statment
	- if나 else if 뒤에 오는 괄호안에 있는 값이 참이면, 중괄호에 있는 식을 수행한다
	- 파이썬과는 달리 `elif`가 아닌 `else if`를 사용한다
- switch statment
	- 나올 수 있는 결과값들을 case로 나누어 분기하고, switch 뒤에 오는 표현식을 계산한 후 어느 case에 해당하는지에 따라 해당 case의 중괄호에 있는 식을 수행한다
	- `break`를 사용하여 switch 구문에서 빠져나올 수 있다
- Ternary operator (삼항 연산자)
	- 짧은 조건식의 경우 삼항 연산자를 이용하여 간단하게 표현이 가능하다
	- 삼항 연산자의 결과값을 변수에 저장할 수 있다

### 조건문 문법

#### if statement

```javascript
if (condition) {
  // something
} else if (condition) {
  // something
} else {
  // something
}
```

#### switch statement
#### 삼항 연산자
```javascript
condition ? value_when_true : value_when_false

// example
a = []
a.length === 0 ? console.log("빈 배열") : console.log("안 빈 배열");

// 변수에 저장하기
const isEmpty = a.length === 0 ? "empty" : "not empty"

// example2 삼항 연산자 중첩하여 사용하기
score >= 90
	? console.log("A+")
	: scope >= 50
	? console.log("B+")
	: console.log("F")
```



