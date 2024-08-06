# :four_leaf_clover:  BICHENA
###### 비채나 : 비우고 채우고 나누다.
<br><br>
## :blush: 프로젝트 소개 

'전통의 맛, 현대의 감성 - 트렌디한 전통주!'

'좋은 사람, 좋은 자리, 좋은 음식 그리고 좋은 술'
 
<br><br><br>

## :date: 개발 기간
- 2024.04.26 ~ 2024.05.23
- 인원 : 7명
<br><br><br>

## :bulb: 주요 기능
#### 일반 회원 기능
- __회원가입__
- 로그인, 카카오/네이버 로그인
- 아이디찾기, 비밀번호 찾기
- 회원정보 수정
- 회원 탈퇴
- 나의 주문 내역 확인, 취소
- 리뷰 작성
- 상품 리스트 조회
- 장바구니 담기
- __주문(결제 API사용)__
- __주문 내역 조회__
- __회원 등급제(할인율 적용)__
#### 관리자 기능
- 상품 조회, 등록, 수정, 삭제
- __주문 내역 조회__
- __주문 상태 변경__
- __결제 취소__
- 공지사항 조회, 작성, 수정, 삭제
- 리뷰 조회, 삭제
- 게시판 조회, 작성, 수정, 삭제
- 매출 통계
<br><br><br>

## :wrench: 사용 기술
![개발환경](https://github.com/user-attachments/assets/72813eb3-3d25-46b0-93e8-1dc7b9a38116)
<br><br><br>
## :movie_camera: 프로젝트 결과
<br>


### :cocktail: 메인 화면

https://github.com/user-attachments/assets/e3f377b4-f32f-4410-80dc-f7c1cef87ec0

<br><br><br><br>
### :raising_hand: 회원 가입

- 약관 동의를 진행한 후에 PortoneAPI를 통해 본인인증을 진행할 수 있도록 하였고 미성년자일 경우 홈페이지의 메인으로 되돌아 가도록 제작하였습니다.
- javascript의 함수를 사용하여 유효성 검사를 체크하고 ajax를 통해 아이디, 닉네임, 이메일의 중복검사를 진행하였습니다.
<br>

![본인인증](https://github.com/user-attachments/assets/922df960-f930-4a38-8b30-0d2ddc6c5c55)

https://github.com/user-attachments/assets/e7e7937a-cc70-40a1-82e8-b41c94d7724b
<br><br><br><br>
### :money_with_wings: 주문

- 결제는 포트원 API를 사용하였습니다.
- https://developers.portone.io/docs/ko/pg/payment-gateway/inicis?v=v1 (참고)
<br>

https://github.com/user-attachments/assets/d9e2d520-21b0-484c-8276-a95f399a863e

![결제완료](https://github.com/user-attachments/assets/b45e629b-ee78-43fa-9694-38256dabf65d)

<br><br><br><br>
### :page_with_curl: 주문 내역 조회, 결제 취소

- 고객이 주문한 주문 내역은 마이페이지에서 확인할 수 있고, 배송상태가 '상품준비중'인 상태에 한하여 주문취소가 가능합니다.
<br>

https://github.com/user-attachments/assets/8240b26d-e2b1-46cf-bea0-dd7c18c68d45

<br><br><br><br>
### :page_with_curl: 회원 등급, 할인 적용

- 고객이 구매했던 구매금액만큼을 누적하여 누적금액을 설정하였고, 누적금액에 따른 회원등급이 부여됩니다.
- 회원등급은 각각 실버, 골드, 다이아 등급이 있으며 골드는 전체금액의 5%, 다이아는 10%의 할인율이 적용됩니다.
- 실버 : 기본등급
- 골드 : 누적금액 50만원 달성 시 승급
- 다이아 : 누적금액 200만원 달성 시 승급
<br>

![할인](https://github.com/user-attachments/assets/10a4f4ef-8765-4b88-a647-1b71120f8ade)

<br><br><br><br>
### :cookie: 관리자 : 주문 내역

- 주문의 상세 정보를 확인할 수 있습니다.
- 주문의 주문상태를 '취소'를 제외한 나머지 상태로 변경할 수 있습니다.
<br>

https://github.com/user-attachments/assets/155f6fea-5d90-457c-a3d9-7fafe41d8894

https://github.com/user-attachments/assets/266ab8b5-7770-4978-b32e-77ce02692ffa

<br><br><br><br>
상품 이미지 출처 : 담화컴퍼니 주식회사
