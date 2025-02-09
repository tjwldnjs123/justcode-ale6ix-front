# ALE6IX PROJECT

## justcode 1차 프로젝트 

- 해외 유명 디자이너 브랜드 ALESSI (http://alessi.co.kr) 를 클론 코딩 하였습니다.
- 프로젝트 내의 짧은 기간동안 세션 복습과 새로운 기능을 도전해 보고자 디자인은 클론코딩 하였고 기능을 구현하는 데에 중점을 두었습니다.
- 개발은 최소한의 라이브러리를 사용하여 직접 구현하였고 영상에서 보여지는 부분 모두 Fetch함수와 api를 이용하여 백엔드와 통신하여 작업하였습니다.

### 개발 인원 및 기간

- 개발기간 : 2022/8/29 ~ 2022/9/8
- 개발 인원 : 프론트엔드 4명, 백엔드 2명
- [프론트엔드 github 링크](https://github.com/wecode-bootcamp-korea/justcode-6-1st-ale6ix-front)
- [백엔드 github 링크](https://github.com/wecode-bootcamp-korea/justcode-6-1st-ale6ix-back)

### 프로젝트 선정이유

- E-commerce는 필요한 부분을 컴포넌트화하여 섹션을 나누거나 fetch를 이용하여 api통신으로 데이터를 주고 받는등
  지금까지 학습한 부분을 각자 맡은 페이지내에서 복습할 수 있고 새로운 기능을 추가로 학습할 수 있기에 선정하게 되었습니다.

### 데모 영상(이미지 클릭)

*유투브 영상 링크나 캡쳐 이미지 넣어주세요.*

<br>



### 적용 기술

> - Front-End : React.js, sass, react-modal, react-dom, react-icons, react-paginate, react-router-dom


### 전체 프로젝트 구현 기능
- 로그인,회원가입
- 메인페이지
- 제품 페이지
- 제품 상세페이지
- nav,footer
- 검색창
- 장바구니


### 구현 기능

1. 메인페이지
- 전체 레이아웃
- MainSection1,2 레이아웃
- MainBanner1,2 레이아웃
- 중복 Title컴포넌트화
- Magazine 목데이터 사용

https://user-images.githubusercontent.com/100896832/190037169-28a7dff9-cf77-4e42-8583-b76d1ef0eb66.mp4

2. 제품 상세페이지
- 수량(+,-)버튼 구현, 상품수량이 상품재고보다 많아지면 재고 알림창 구현
- POST 요청 : 수량,제품번호 post 통신

[https://user-images.githubusercontent.com/100896832/190034745-3bc71213-3d35-449f-b8d6-559ff5bb8991.mp4](https://user-images.githubusercontent.com/100896832/190036250-5f0e6159-baae-4493-baab-3821ba085697.mp4
)

3. 장바구니
- 장바구니 레이아웃
- 조건부 렌더링으로 상품이 없을때 '장바구니 가 비어있습니다' 문구 구현
- GET : 장바구니에 담긴 상품들 화면에 렌더링
- PATCH : 장바구니 상품 수량변경 -> 유저 아이디,상품 아이디,변경된 수량을 담아서 요청 
- DELETE : 개별 상품 삭제, 체크된 상품 삭제, 전체삭제(장바구니 비우기)

https://user-images.githubusercontent.com/100896832/190058209-81c8bdc1-f5f7-4ec4-b3c1-a13d225d83fd.mp4


4. 검색창
- 검색창 레이아웃
- GET : 서버로부터 query문 사용하여 값을 가져옴
- GO!버튼 클릭 or Enter 검색한 상품들이 나오게 구현

<br>

## Reference

- 이 프로젝트는 [알레시](http://alessi.co.kr) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 모두 알레시 코리아의 동의하에 작업되었습니다.
