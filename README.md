# Getting Started with Create React App


header.page - 성원
  => 로그인,로그아웃.page(+카카오 로그인api, 네이버 로그인api)
  => 회원가입.page - 성원

main.sec1.page(유튜브) - 화진
  => 캘린더.page(전시회 일정 표시,swiper) - 희성

main.sec2.page(swiper) - 화진
  => 예약.page(티켓 구매) - 성원 
  => 결제 연동(KG이니시스) - 희성

main.sec3.page(Map) 
  (카카오 지도api - 전시회 위치 지도에 표시, 
  GeoLocation api - 현재 위치 검색 ) - 희성

main.sec4.page(swiper,찜하기..) - 화진 
  => 장바구니.page(상품 구매) - 화진

footer.page - 희성 -> (수정: 성원) 

오른쪽 하단 - messenger.page(고객센터) - 희성
           - 스크롤 이동 - 성원



< 2023.03.10. 발표 >

팀장/팀원 : 서희성/김성원 채화진
개발 동기 및 의도 : 1) 내 위치 주변의 전시회를 편하게 찾을 수 있게 하기 위해
		2) 굿즈와 전시회를 동시에 결제할 수 있도록 하기 위해

웹 페이지 구성
0) header - 로그인, 회원가입, 각 메뉴
1) main 01 - 전시 일정 확인
2) main 02 - 수도권 지역별 전시 확인
3) main 03 - 내 위치 주변의 전시회 확인
4) main 04 - 굿즈샵

웹 페이지 기능 및 시연 시나리오
1) 로그인    ---> 카카오api, 네이버api 사용
    (ID: kws04181@naver.com / PW: react1818@)
2) 회원가입
3) 고객센터(챗봇)
4) 전체 전시일정 확인
5) National exhibition
  (1) 각 지역별 탭을 눌러 확인
  (2) 바로예약 눌러서 날짜 선택 및 확인 -> 로그인
6) Location exhibition
  (1) 내 위치 확인    ---> 카카오지도 api
  (2) 내 위치 주변 전시회 지도에 나타남 .... 이동은 불가
7) Goods shop
  (1) 찜하기 기능(하트)
  (2) 장바구니 구현
8) 장바구니 메뉴
  (1) 수량 변경 및 삭제 가능
  (2) 결제하기    ---> KG이니시스
