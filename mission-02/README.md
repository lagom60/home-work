# Mission-02
로그인 폼 완성
(../mission-01/images/mission-02_complete.png)

## Login Form
- Markup:
  1. form 태그를 활용, h2(title) & fieldset로 틀을 잡음.
  2. legend 태그 : a11yHidden 클래스를 주어 접근성을 높임.
  3. div 태그 안에 label, input 태그를 넣어 입력폼 세트를 만듦.

- CSS:
  1. .header = 타이틀 스타일 지정
  2. .login & fieldset = 백그라운드 스타일 지정
  3. label과 input엔 각각 inline-block을 주어 일렬로 배치되게 만듦. 
  4. `position` .box_login에 relative를 주고,
      .btn에 absolute를 줘서 버튼을 position으로 배치함.


## Login Apend
- Markup:
  1. ul 태그 안에 li > a > i(아이콘) 태그를 배치함.
  2. 회원가입 및 비밀번호 찾기는 다른 페이지로 연결하기 위해 a태그 사용.
  3. 접근성을 위해 i 태그 안에 aria-label을 넣음.

  -CSS:
    1. .login_apend(ul) 태그에 전체적인 배경 및 폰트 스타일 지정
    2. .login_apend li 태그에 inline-block을 지정해 한 줄로 배치함.
    3. li:first-child 첫 번째 li 태그에 margin-right를 주어
        회원가입/비밀번호 찾기 사이에 간격을 띄움.