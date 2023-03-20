# Zoopiter

프로젝트 파일 업로드 :)

## [진행상황]

- 동물병원 검색화면(지도API) 테스트 중 (23.02.17)

- 구현해야할 화면 :

  1. GNB-로그인 시 '로그인|회원가입'-> '마이페이지' 변경, 반응형 화면
  2. 동물병원 검색 / 게시판(펫가이드, 커뮤니티, 동물병원 후기) / 로그인 / 회원가입 / 마이페이지 / 관리자화면

- 각 화면 담당자 정보
  - 동물병원 찾기 : 유원진
  - 로그인 / 회원가입 : 함현식
  - 마이페이지 : 최은아
  - 게시판[커뮤니티] : 박경진
  - 게시판[병원후기] : 김영훈
  - 게시판[펫가이드] : 박청경

* 메인페이지 진행 상황: css 스타일 98% 완료, 햄버거 메뉴 오류 수정 필요, 각 페이지 연결 필요 (마이페이지 메인, 수정화면 연결 중)

---

### _공지사항_

1. 폴더를 용도 별로 정리했습니다.(03.21 업데이트)

- html, js(자바스크립트), css, img(이미지 파일)
  > old 붙은 폴더들은 과거에 작업했던 파일 입니다. 지금은 사용하지 않지만 혹시 몰라 남겨뒀습니다. :)
- css > theme 폴더 : color.css, common.css, font.css, reset.css
- 파일명 변경 : layout2.css -> layout.css, main2.html -> index.html

2. id명, class명은 '6. UI 구현 표준안\_2팀.docx' 파일을 참고하셔서 작성해주시기 바랍니다.

- 해당 파일 확인방법
  - 구글 드라이브 '슬기로운반려생활' 공유문서
  - 팀 단체 카톡방에 올린 '팀프로젝트' 압축파일

---

- 03.15 : 메인화면 본문 내용 추가 및 footer 레이아웃 반응형 반영, color.css 회색, 검정색 계열 색상 추가

* 문제점
  1. 본문 3번째 이미지 화면 폭 줄었을때 높이값이 사라지는 오류 -> 해결
  2. 본문 2번째 화면 폭 줄었을 때 슬라이드 이미지 겹침, 슬라이드 화살표 버튼 컬러 변경 안됨 -> 본문 2번째 슬라이드 이미지 안보이게 변경
  3. GNB메뉴 오류 -> 해결 안됨
  - 메뉴 화면 폭 줄이고 다시 늘렸을 때 로그인|회원가입 이 사라지는 오류
  - 햄버거 메뉴 펼쳤을 때 2dept 메뉴 클릭 오류 : 버벅거림, 해당하지 않는 메뉴 오픈

- 03.20 : 파일 내용 변경
  - common.css - header, footer css 내용은 여기에 있습니다.
  - layout2.css - 기본 레이아웃 입니다.(전체 그리드)
  - main2.css - 배너 부터 메인 컨텐츠 영역 레이아웃 입니다.
