# 20190104

# CLI

- CLI - 커맨드 라인 인터페이스, 키보드만으로 컴퓨터를 조작
- GUI - 그래픽 유저 인터페이스, 키보드와 마우스로 조작

## which os??

- Unix based OS (Linux,MacOS 등등)
  - unix -> 서버 관리하는 시점에서 무조건 사용한다.

## Prompt

- $ :컴퓨터가 명령을 받을 준비가 됨 
- echo : 메아리 쳐준다
  - 나갈 땐, Ctrl + C으로 탈출!

```prompt
student@DESKTOP MINGW64 ~
$ echo "hello
> ^C
```

## 명령어

본문 - 표, ctrl 엔터 : 줄 추가

| 명령어           | 설명                      | 사용법         | 출력              |
| ---------------- | ------------------------- | -------------- | ----------------- |
| echo             | 다음에 들어오는 내용 리턴 | echo "hello"   | hello             |
| ctrl-C           | 작업 중지                 | ctrl-C         | ^C                |
| 방향키 ↑,↓       | 이전 명령어 들고 옴       | ↑ 또는 ↓       |                   |
| ctrl-L , Clear   | 터미널 깔끔하게 정리      | ctrl-L , CLEAR |                   |
| mkdir            | 폴더 생성                 | mkdir 폴더이름 |                   |
| change directory | 폴더 안으로 들어가기      | cd 폴더        |                   |
| tab키 한 번      | 자동 완성                 | ~~ c+ tab      | ~~ copy_hello.txt |
| tab키 두 번      | 목록 출력                 |                |                   |

## 파일 조작

| 명령어                             | 설명                                      | 사용법                                                 |
| ---------------------------------- | ----------------------------------------- | ------------------------------------------------------ |
| `>`                                | 왼쪽의 출력물 오른쪽 파일로 전송하기      | $ echo "hello" > hello.txt                             |
| `>>`                               | 왼족의 출력물을 오른쪽 파일에 붙이기      | $ echo "hihi" >> hello.txt                             |
| `cat 파일명`                       | 파일을 블러서 읽어줌 (여기선 출력 확인용) | $ cat hello.txt                                        |
| ls                                 | 파일/ 디렉토리들의 목록을 보여줌          | ls                                                     |
| ls -a                              | 숨김파일 포함해 목록을 보여줌             | ls -a                                                  |
| ls -t                              | 최근의 파일/디렉토리들의 목록을 보여줌    | ls -t                                                  |
| `mv <old> <new>`                   | 파일의 이름을 바꿔준다 . mv 수정전 수정후 | mv hihi hihi.txt                                       |
| `cp <old> <new>`                   | old를 new로 복사                          | cp hello.txt copy_hello.txt                            |
| `rm <file>`                        | file 파일 삭제                            | rm copy_hello.txt                                      |
| `rm -r <dir>`  또는 `rm -rf <dir>` | ㅎㅏdir하위 폴더와 파일 까지 전부 삭제    |                                                        |
| `rm -i`                            | 파일 지울 때 질문 하나 하기               | rm *.py                                                |
| curl                               | url과 상호작용                            |                                                        |
| curl -O 주소                       | 주소에있는 내용 다운받기                  | $ curl -O https://educhang.github.io/test/bohemian.txt |
| `head <file>`(b tab)               | 파일 내용의 앞부터 10줄만 보여준다.       | $ head bohemian.txt                                    |
| `tail <file>`                      | 파일 내용의 끝부터 10줄만 보여준다.       | $ tail bohemian.txt                                    |
| `wc <file>`                        | 파일의 즐, 바이트, 단어를 카운트 해준다.  | $ wc bohemian.txt                                      |

## 디렉토리

| 명령어     | 설명                    | 사용법            |
| ---------- | ----------------------- | ----------------- |
| ls         | 파일/폴더 내용 출력     | $ ls              |
| pwd        | print working directory | $ pwd             |
| `cd <dir>` | `<dir>` 위치로 이동     | $ cd bohemian.txt |
| cd ..      | 상위 폴더로 이동        |                   |
| cd ~       | 홈 디렉토리로 이동      | $ cd ~            |
|            |                         |                   |
|            |                         |                   |
|            |                         |                   |
|            |                         |                   |

- `/`: 최상위 루트
- `~`: 홈 디렉토리



햣 