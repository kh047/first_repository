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
8. 원격저장소 설정
    * git remote add first_remote_repo https://github.com/.../first_repository.git
9. workspace 폴더 내 README.md 파일 생성 및 내용 작성
10.상태 확인
    * git status
11. 저장소에 변경된 파일을 관리할 수 있도록 추가
    * git add .
    * git add README.md
12. Local Repository에 저장
    * git commit -m "first_commit"
    * commit 이름은 해당 작업에서 추가/변경된 사항을 간략히 작성
   * 다른 작업자가 알아볼 수 있도록 되도록이면 영어로 작성하는 것을 추천
13. Remote Repository에 저장
    * git push first_remote_repo master

# README.md 파일
* README.md 파일은 주로 프로필 혹은 Repository에 대한 설명을 나타내기 위해 작성
* 소스를 정리하는 데에 큰 도움

* 마크다운 문법
    - 사용이 쉽고, 마크업 언어인 HTML 태그에 비해 간단하기 때문에 문서 작성이 편리
    - 마크다운을 지원하는 프로그램이나 사이트에서만 사용 가능
    ## Header
    ... h{n} : #과 글자 사이에는 띄어쓰기로 구분

    ## 줄바꿈
    Enter키 2번

    ## 순서가 있는 목록(ol : Ordered List)

    ## 구분선(Division Line)
    하이픈(-) 혹은 asterisk(*) 3개 이상 사용

    ## 코드블럭(Code Block)
    코드를 기준으로 위아래 빈 한 줄씩 추가
    코드를 기준으로 4칸 공백

        private String str;
        private int count;

    ## 하이퍼링크(Hyperlink)
    <>(앵글브라켓) 안에 HTTP(S)를 포함하는 주소 입력
    <https://www.naver.com>

