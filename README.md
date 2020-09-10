# 자동차 렌트 서비스

<img src="https://user-images.githubusercontent.com/62331803/92744440-79239e00-f3bc-11ea-9cda-dfcfd22a1eb7.png" width="50%">

<br>

## 프로젝트 개요
### 1. 차량 렌트 서비스 개요
- 고객이 빌리고 싶은 차량을 선택
- 서버 측에서 DB로부터 렌트 가능한 날짜, 시간대를 불러와 전송
- 고객은 원하는 날짜와 시간대를 선택하여 주문을 완료
-  해당 주문의 총액을 계산하여 고객에게 전송
-  결제까지 끝나면 렌트 완료

### 2. 주요 기능
-  회원가입
-  로그인
-  렌트카 주문
-  결제
-  고객의 주문 정보 관리 (주문내역, 주문취소)

### 3. Database 구성
- 회원 테이블 | RENT_MEMBER
- 차량 테이블 | RENT_CAR
- 주문 테이블 | RENT_ORDER

<img src="https://user-images.githubusercontent.com/62331803/92733348-8dfb3400-f3b2-11ea-8d0e-8b7294733d14.png" width="70%">

<br>

## 시연
### 1. 회원가입

#### >> 이미 존재하는 아이디를 입력한 경우 <br>

<img src="https://user-images.githubusercontent.com/62331803/92733830-f2b68e80-f3b2-11ea-8061-90acd0714a14.png" width="50%">

<br>

#### >> 존재하지 않는 아이디로 회원가입 <br>

<img src="https://user-images.githubusercontent.com/62331803/92734220-4c1ebd80-f3b3-11ea-88c7-261df71f81c1.png" width="50%">

<br>

###  2. 로그인
#### >> 멤버 테이블 <br>

<img src="https://user-images.githubusercontent.com/62331803/92735853-b5eb9700-f3b4-11ea-8340-365aa64477d2.png" width="50%">
<br>

#### >> 존재하지 않는 정보 입력 <br>

![image](https://user-images.githubusercontent.com/62331803/92734953-f565b380-f3b3-11ea-87f1-bc607eeef527.png)

<br>

#### >> 존재하는 정보 입력 <br>

![image](https://user-images.githubusercontent.com/62331803/92736057-e3384500-f3b4-11ea-9128-8d2c17fb966d.png)

<br>

### 3. 주문
#### >> 주문할 차량과 날짜를 입력
- 해당 날짜에 해당 차량이 가능한 시간대 출력 (현재 12시부터 16시까지는 이미 대여완료) <br>
![image](https://user-images.githubusercontent.com/62331803/92737299-fac3fd80-f3b5-11ea-9958-042f0a475989.png)

<br>

#### >> 주문 완료 <br>

![image](https://user-images.githubusercontent.com/62331803/92737563-3959b800-f3b6-11ea-99d6-16fde776c364.png)

<br>

#### >> 주문 목록 출력 <br>
- 주문정보와 결제유무를 나타냄
![image](https://user-images.githubusercontent.com/62331803/92737764-6017ee80-f3b6-11ea-87a0-8b45e5ca1b71.png)

<br>

#### >> 결제 <br>

![image](https://user-images.githubusercontent.com/62331803/92739220-9efa7400-f3b7-11ea-866f-c67744a33a5f.png)
<br>

- 결제완료 <br>
![image](https://user-images.githubusercontent.com/62331803/92740944-1f6da480-f3b9-11ea-8b99-3a5592de9388.png)

#### >> 주문취소 <br>

![image](https://user-images.githubusercontent.com/62331803/92739718-23e58d80-f3b8-11ea-9172-552f7942e10d.png)

<br>

- 목록에서 주문 삭제됨 <br>

![image](https://user-images.githubusercontent.com/62331803/92739911-4a0b2d80-f3b8-11ea-9202-0537dde47378.png)
<br>

#### >> 종료 
- 서버측 콘솔 <br>

![image](https://user-images.githubusercontent.com/62331803/92740044-66a76580-f3b8-11ea-9626-71f26432c226.png)
