# TIL (Toady I Learned)

## 깃허브

### README.md(제대로 된 깃허브 페이지)

> 개발자들의 문서 작성 양식

- TIL 연동→ 깃허브 → 잔디
- 노션 블로그 작성
- `#` 문서의 논리적 흐름 

|                    단축키                    |                사용방법                |
| :------------------------------------------: | :------------------------------------: |
|                      #                       |                 큰주제                 |
|                      ##                      |               중간 주제                |
|                     ###                      |                 소주제                 |
|                     ```                      | 코드블럭(파이선 등 여러가지 언어사용)  |
|                     ---                      |                 수직선                 |
| ``     |   인라인 블럭(빽틱으로 감싸기) `집` |                                        |
|                    \`#\`                     |     백슬백틱백슬백틱 그대로 나타냄     |
|                  컨트롤 + /                  |              문장 쓴것 확              |
|                   `` ` ``                    |         백틱백틱 백틱 백틱백틱         |
|                     캡처                     |            윈도우+ 쉬프트 s            |
|                      >                       |                 인용문                 |
|                   \| \| \|                   | 엔터위에 3개(띄어쓰기) 입력하면 표나옴 |
|                  윈도우+ 점                  |                이코티콘                |
|                      **                      |                  볼드                  |
|                                              |                                        |



## 깃&깃허브  

> 깃?

- 깃은 분산 버전 관리 프로그램이다
  - 버전관리 보안성
    - 각자의 버전을 보유 삭제 복구 용이함 

  - 작업파일 관리 효율성
    - 버전 1 ~ 4 넘어 갈때마다 변경 사항만 저장 


- 깃 허브는  개발자들에 포토폴리오다 

  - 잔디 관리(매일 코딩)

- CLI(Commana Line inteface) 

- 깃 배쉬(명령어 입력 방식)

  |   숙지사항   |                 사용방법                  |
  | :----------: | :---------------------------------------: |
  | 홈 폴더 사용 |        컴퓨터 바탕화면 ↑, ↑  user         |
  |   CLI 환경   |          ~ 노란색 부분 위치 확인          |
  |      LS      |           현재폴더 리스트 확인            |
  |    LS -a     |            숨김 파일까지 확인             |
  |     date     |               현재시간 확인               |
  |      .       |                 현재위치                  |
  |    cd ..     |                 상위위치                  |
  |      cd      |            어느 위치든 홈폴더             |
  | 탭 자동완성  |          cd Desktop/(De 까지만)           |
  |    clear     |                현재창 정리                |
  | touch a.txt  | 현재 폴더 위치에 메모장 생성(여러개 가능) |
  | mkditr test  |                 폴더 생성                 |
  | start a.txt  |                메모장 실행                |
  |   cd paste   |           경로 입력 / 경로 변경           |







- GUI(Graphic User interface)  환경 
  - 유저가 눈으로 보고 명령을 내릴 수 있는 환경

- 





## 깃 배쉬& Visual Studio Code

>깃 배쉬 를 통해 Visual Studio Code 사용



| 순번   |                            명령어                            |                             내용                             |
| ------ | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 1      |                    mkdir TIL   life cycle                    |               홈 폴더 에서 실행 mkdir TIL 입력               |
| 2      |                          ls, cd TIL                          |             ls 입력 후 cd TIL   입력  TIL폴더로              |
| 3      |                            code .                            |                   code . 입력하여 VSC 실행                   |
|        |                 git config  --global --list                  |                     이메일 유저 정보확인                     |
|        |          git config --global user.name "kimchanwo"           |                 유저 정보 깃허브랑 같아야함                  |
| 2      |          git config --global user.email "메일 주소"          |                  메일주소 깃허브랑 같아야함                  |
| 4      |                          컨트롤 + `                          |                        터미털 띄우기                         |
| 5      |                         touch a.txt                          |                          메모장생성                          |
| 6      |                       touch mu1cam.txt                       |                          메모장생성                          |
| 7      |                           git init                           | 특정폴더를 깃으로 관리를  시작하겠다! (홈폴더에서 사용 불가) 관리시작(마스터 가뜸) |
| 8      |                              ls                              |                         메모장 확인                          |
| 9      |                            ls -a                             |                     . git 생성 관리시작                      |
| 10     |                              U                               |              왼쪽 상단 메모장들 옆에 untracked               |
| 11     |                          mu1cam.txt                          |                      blue hat 입력 저장                      |
| 12     |                          git status                          |                빨간색 메모장 untracked 파일 !                |
| 13     |                      git add mu1cam.txt                      |           배우 분장실(a,~~mu1cam~~) → 무대(mu1cam)           |
| 14     |                          git status                          |          상황확인  a는 분장실 mu1cam 무대로 가있다           |
| 15     | git commit -m 'first' (commit R까지만 입력하면 오류남  esc :Wq  로 나와야함) | 메세지를 적는다 → 버전관리시작  무대 있는 멀캠이를 사진 촬영 저장소로 넘기는것 |
| 16     |                          git status                          |                         한번더 확인                          |
| 17     |                           git log                            |                         올린거 확인                          |
| 19     |                      git log --oneline                       |                 12번으로 돌아가서 다시 하기!                 |
| 18     |                         yellow shoes                         |                   2번째 입력  m(modified)                    |
|        |                                                              |                                                              |
| 확인   |                     git checkout 08dbe6                      |             이렇게 하면  커밋 햇던곳 으로가 간다             |
| 확인   |                     git checkout master                      |                    이렇게 하면 돌아온다!                     |
| 지우기 |                      이메일 정보 지우기                      |            git config --global --unset user.name             |
| 온라인 |                        깃허브 올리기                         |                        온라인방만들기                        |
| 1      |                      Repositories(new)                       |                      방계약(왼쪽 상단)                       |
| 2      | git remote add origin https://github.com/kimchanwo/lifecyce2.git |           6번째 주소! 복사 후 비주얼로 가서 복붙!            |
| 3      |                        git remote -v                         |                           주소연결                           |
| 4      | origin  https://github.com/kimchanwo/lifecyce2.git (fetch)<br/>origin  https://github.com/kimchanwo/lifecyce2.git (push) |              깃 허브랑 로컬 작업이랑 연결된것!               |
| 5      |                    git push origin master                    |                       깃 으로 보내기!                        |
| 6      |             그리고 깃허브 새로 고침하면 업로드됨             |                         잔디도 찍힘                          |
| 7      |                       오른쪽 히스토리                        |                  그럼 이력 한거 시간도 나옴                  |
|        |                                                              |                                                              |
|        |                       md 올리기 시작!!                       |                                                              |
|        |                          mkdir TIL                           |                         홈폴더 배쉬                          |
|        |                            cd TIL                            |                       그 폴더로 들가기                       |
|        |                           git init                           |                      그 폴더 관리 하기                       |
|        |                       touch README.md                        |                        md 파일 만들기                        |
|        |                          git status                          |                         빨간색 나옴                          |
|        |                 그리고 TIL 폴더를 VS 로 열기                 |                                                              |
|        |                          git status                          |                          (un)빨강이                          |
|        |                          git add .                           |                         (new)초록이                          |
|        |                 git commit -m 'readme added'                 |                       저장소로 넘기기                        |
|        |                     원형으로 VS 넘어감!                      |                                                              |
|        |                      git log --oneline                       |                             확인                             |
|        |  git remote add origin https://github.com/kimchanwo/TIL.git  |         깃 허브 방만들기 후 주소복사 gn VS 붙여 넣기         |
|        |                        git remote -v                         |                             확인                             |
|        |                    git push origin master                    |                       깃 허브 보내기!                        |
|        |                                                              |                                                              |
|        |                갓의 추적을 피하고싶을때 작성                 |                          gitignore                           |
|        |         https://www.toptal.com/developers/gitignore          |                                                              |
|        |                                                              |                                                              |

## 복습 

|      목      | 복습현황 |
| :----------: | :------: |
|    파이썬    |    😊😊    |
|      깃      |    🤣🤣    |
| 자바스크입트 |    🙌🙌    |
|              |          |
|              |          |



|                             순번                             |      |
| :----------------------------------------------------------: | :--: |
| 온1. 로컬에서 시작한다 -> git init(홈폴더 init 금지) -> add commit -> 온라인으로 가서 방을 받고 주소를 받는다 -> git remote add로 연결한다.

2. 온라인에서 시작한다 -> git clone 주소(홈 폴더해도 상관 없음) -> 해당 클론 받은 곳에 폴더가 생기며 그 폴더는 이미 깃의 관리를 받고 있다.

결론 : 둘다 git init 과 git clone 은 한번만 작성하는 명령어이다 |      |
|                  git clone  주소 클론 받기                   |      |
|                B 시작 git pull origin master                 |      |
|                                                              |      |
| word relay

수정사항(끝말잇기) -> git add -> git commit -> git push => B 분들에게 연락

B분들 : git pull origin master
수정사항 -> git add . -> git commit -m 'han2' > git push ->git push origin master -> git log --oneline |      |
|                                                              |      |
|                                                              |      |
|   git branch 현재 어떤 브랜치가 내작업 공간에 있는지 확인    |      |
|                  git branch 브랜치명 - 생성                  |      |
|                     git switch 브랜치명                      |      |

asdads