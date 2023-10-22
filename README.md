# 도란도란
| 프로젝트 개요 |


##  팀원 소개

| 이름   | 깃허브                                       |
| ------ | -------------------------------------------- |
| 이순재 | [@leesoonjae](https://github.com/leesoonjae)       |
| 김명준 | [@chorongs](https://github.com/chorongs)       |

<br/>
<br/>

##  규칙

- **커밋 컨벤션 (유다시티 커밋 컨벤션 참고!)**
  | 키워드 | 설명 |
  | --- | --- |
  | feat | 새로운 기능을 추가한 경우 |
  | fix | 버그를 고친 경우 |
  | refactor | 코드 리팩토링 |
  | docs | 문서를 수정한 경우 |
  | perf | 성능개선 |
  | chore | 그런트 작업 업데이트, 프로덕션 코드 변경 없음 |

- **코드 컨벤션**
  1. prettierrc로 prettier 설정 통일
  2. 변수명은 직관적으로 짜기 (파스칼케이스 기반)
    - 함수명은 동사+명사 addPost
    - 그 외 컴포넌트 명은 알아보기 쉽게 작성하기 writeButton

<br/>
<br/>

##  깃허브 협업 방식

Git Flow 방식을 이용했습니다.

- `main` : `dev` 브랜치로부터 최종병합되는 브랜치. (배포용)
- `dev` : 주된 작업들이 합쳐지는 브랜치
- `dev`에서 뻗어나온 개인 브랜치 : 각자의 작업이 진행되는 브랜치

<br/>
<br/>

##  구현 기능

- Home
  - 입장 버튼

- SignIn
  - 로그인 
  - 회원가입
  - 유효성 검사

- SignUp
  - 회원가입
  - 유효성 검사


- MainPage
  - 오늘 날씨 확인(API)
  - 최근 글 목록
  - 마이페이지 이동

- MyPage
  - 유저 프로필 이미지 변경
  - 이름 수정
  - 로그아웃 (로그아웃시 첫화면으로 나가짐)
  - 작성 글 목록

- AddPost
  - 글 작성하기
  - 마이페이지 이동

- ViewPost
  - 글 수정하기
  - 글 삭제하기


  <br/>
  <br/>
