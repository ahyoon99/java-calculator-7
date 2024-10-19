# java-calculator-precourse

<br>

## 📌 동작 흐름
1. 문자열 입력하기
   1. 쉼표(,) 또는 콜론(:)을 구분자로 가지는 경우
      1. 구분자를 기준으로 숫자 나누기
   2. 커스텀 구분자를 지정한 경우
      1. "//"와 "\n" 사이에 있는 커스텀 구분자를 구하기
      2. 구분자를 기준으로 숫자 나누기
2. 나눈 숫자를 모두 더하기

<br>

## 📌 필요 기능

- 문자열 입력받기
- 입력받은 문자열 종류 구분하기
  - 쉼표(,) 또는 콜론(:)을 구분자로 가지는 문자열인지, 커스텀 구분자를 가지는 문자열인지
- 커스텀 구분자를 콜론(:)으로 바꾸기
- 구분자(쉼표나 콜론)를 기준으로 숫자 나누기
- 나눈 숫자를 모두 더하기
- 정답 출력하기

<br>

## 📌 예외 처리
1. 잘못된 문자열을 입력했을 경우, IllegalArgumentException 발생시킨 후 애플리케이션 종료시키기
   1. 문자열이 숫자로 시작하지 않고, "//"로 시작하지 않는 경우
   2. 구분자를 제외한 문자열이 숫자가 아닌 입력을 포함한 경우
   

<br>

## 📌 프로젝트 구성

### 📁 calculator package

- **`Application.java`**
- **`calculatorProcess.java`**
  - 문자열 덧셈 계산을 진행하는 클래스

<br>

### 📁 utility package

- **`Constant.java`**
  - 상수를 관리하는 클래스 (하드 코딩 방지)
- **`StringError.java`**
  - Exception에 사용할 에러 메시지 관리하는 클래스
