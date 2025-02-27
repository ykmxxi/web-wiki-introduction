# 자기소개 위키 페이지 만들기

레벨1 공통 교육 - 자기 소개 위키 페이지 만들기

## 기능 요구사항
- [x] 자기소개를 작성한다
- [x] 9가지 사진을 정사각형으로 배치한다
- [ ] 나를 울린 작품 최소 2가지를 소개한다
- [ ] 우측 프로필 사진을 변경한다 
- [ ] 우측 목차를 작성한다
  - 목차 하이퍼링크 설정
- [ ] 댓글 입력창을 최하단에 구성
  - 댓글 입력창 구성요소를 감싸는 태그는 <form> 태그를 사용한다.
  - 힌트: <input type="text">
  - 등록 버튼은 <button type="button"></button>으로 구성한다.
  - 취소 버튼은 <button type="reset"></button>으로 구성한다.
  - 댓글 입력을 완료하면 댓글이 목록에 추가된다
  - 댓글 입력을 완료하면 "댓글이 등록되었습니다"라는 메시지를 Alert 창에 띄운다

## 프로그래밍 요구사항
- root 디렉터리에는 웹 문서만 저장할 수 있다.
  - html 인코딩은 UTF-8 방식을 이용한다.
    - <head> 태그 안에는 <meta charset="utf-8"> 코드를 삽입한다.
    - <title> 태그 안에는 적절한 제목을 재량껏 고민하여 삽입한다.
    - 웹 문서를 구성할 때는 시멘틱 태그 및 <div>로 적절히 화면을 나눈다.
    - 웹 문서의 본문 영역은 <h#> 태그를 사용하여 섹션을 구분한다.
  - 리소스를 불러오는 경로는 상대 경로로 지정해야 한다.
- images 디렉터리에는 이미지 파일만 저장할 수 있다.
- css 디렉터리에는 스타일링 파일만 저장할 수 있다.
- 레이아웃은 제공되는 템플릿 파일을 따르되, 본인이 원하는 대로 자유롭게 스타일링할 수 있다.
  - 단, 다음날 데일리 미팅 전까지 본 미션을 완성할 수 있는 분량으로 제한한다.
- 학습 목표가 HTML인 만큼, JavaScript에서 과도한 리팩터링은 지양하고 기능을 구현하는 데에만 의의를 둔다.
