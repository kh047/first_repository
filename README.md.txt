# 설치과정
1. git 프로그램을 Download하고 설치(default).
2. git을 설정하기 위한 workspace 폴더 생성.
3. gitHub 사이트에 접속하여 회원가입 및 로그인 진행.
4. 우측상단 "new Repository" 클릭
    - 내용을 입력하고 생성 -> 생성된 주소를 복사
5. workspace 폴더 내에서 "git Bash" 실행
6. 초기 설정
    : git config --list
    : git config --global user.name "idExample"
    : git config --global user.email "idExample@gmail.com"
    * Git을 설치하고 나서 제일 먼저 해야 하는 것은 "계정정보" 설정
    * Git은 commit할 때마다, 이 정보를 사용(한 번 커밋한 뒤, 정보를 변경할 수 없음)
7. 초기화
    : git init