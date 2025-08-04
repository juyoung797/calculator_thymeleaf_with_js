# 🧮 Calculator with Js and Thymeleaf

이 프로젝트는 Spring Boot와 Thymeleaf, JavaScript를 활용하여 만든 웹 기반 계산기이다.

## ✨ 주요 기능

- 덧셈, 뺄셈, 곱셈, 나눗셈 연산 수행
- 클라이언트에서 숫자와 연산자를 입력하고, 서버에서 계산 처리
- `fetch` API를 사용한 비동기 POST 요청 처리
- 반응형 스타일과 커스텀 폰트 적용

## 🖼️ 화면 예시

![계산기 데모](assets/demo.gif)

## 🗂️ 프로젝트 구조

```
calculator_thymeleaf_with_js/
├── src/
│   ├── main/
│   │   ├── java/com/j797/calculator_thymeleaf_with_js/
│   │   │   ├── CalculatorThymeleafWithJsApplication.java
│   │   │   └── controller/
│   │   │       └── CalculatorController.java
│   │   └── resources/
│   │       ├── static/
│   │       │   ├── style.css
│   │       │   └── main.js
│   │       └── templates/
│   │           └── index.html
├── assets/
│   └── demo.gif
├── README.md
└── pom.xml
```

## 🛠️ 실행 방법

1. 이 프로젝트를 클론한다.
2. IDE에서 열거나 `./mvnw spring-boot:run`으로 실행한다.
3. 브라우저에서 `http://localhost:8080`으로 접속한다.

## 💡 사용한 기술

- Spring Boot
- Thymeleaf
- JavaScript (ES6)
- CSS