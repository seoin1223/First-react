# First-react
## 목차

1. [준비](#1._준비하기)
2. [리엑트 개념](#)
3. [리엑트 실습](#)
4. [JSX](#)
5. [Components and Props](#)
6. [State and Lifecycle](#)
7. [Hooks](#)
8. [Handling Events](#)
9. [Conditional Rendering](#)
10. [List and Key](#)
11. [Form](#)
12. [Lifting State Up](#)
13. [Composition Vs Inheritance](#)
14. [Context](#)
15. [Styling](#)
16. [Mini Project](#)
17. [Appendix A](#)

<br>

## 1. 준비하기
### a. HTML & CSS
#### 1) html
   - 웹 사이트의 뼈대를 구성하기 위해 사용하는 마크업 언어
   - Tag를 이용하여 구조를 형성
   - `<html></html>`


#### 2) CSS
- Cascading Style Sheets


#### 3) JavaScript
1. 특징
      - 런타임인터프리터 언어 : 인터프리터 언어이지만, 웹 브라우저 대부분에는 JIT 컴파일러(실행 시간에 js코드를 컴파일함)가 내장되어 있어, 실행 속도가 매우 빠르다.
      - 객체 기반의 script 언어
      - 동적 프로토타입 기반 객체 지향 언어 : 클래스가 아닌, 프로토타입을 상속.
      - 일급 객체 함수 : 고차 함수를 구현할 수 있어 함수형 프로그래밍이 가능. => 객체 지향형 프로그래밍과 함수형 프로그래밍을 모두 표현할 수 있다.
      - 동적 타입 언어 : 변수 타입이 없기 때문에, 프로그램 실행 도중 변수에 저장되는 데이터 타입이 동적으로 바뀔 수 있다. (Type Coercion)
      - single thread 기반 언어 : stack 위에 함수를 올려 실행하고, 끝나면 stack에서 제거한다. (한 번에 하나의 task만 처리, 동기적.)
      - non-blocking 언어 : event loop와 callback queue가 있기 때문에, single thread 기반이어도 다른 이벤트를 비동기적으로 처리할 수 있다. (ex. setTimeout, async await..)

2. 문법
     - 자료형 : var, let, const

3. 연산자
     - 대입 연산자 : =
     - 산술 연산자 : +, -, *, /, ** , %
     - 증감 연산자 : ++, --
     - 관계(비교) 연산자 : < , > , <= , >=
     - 동등 연산자 : ==, !=
     - 일치 연산자 : ===, !===
     - 이진 논리 연산자 : &&, ||,  => treu false 연산
     - 조건부(삼항) 연산자 : 조건식? true일 경우 : false일 경우
  

#### 4) JS function
1. 함수 : 입력을 받아서 정해진 출력을 하는 것
      - Parameters || Arguments
   ```javascript
   
    // function statement 사용
    function sum(a, b) {
         return a+b;
   }
   
    // arrow function expression 사용
    const multiply = (a,b) => {
         return a * b;     
    }
    ```

 
