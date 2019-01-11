# Basic Workflow
```sh
$ git init
$ git status # 빨간색 확인
$ git add .
$ git status # 초록색 확인 (초록색만 커밋됨)
$ git commit -m '짧고 간결하고 현재형'

# github, bitbucket, gitlab etc... remote repo 를 생성
$ git remote add origin <REMOTE REPO URL.git>
$ git push (-u origin master) # 첫 번째만

# 다른 컴퓨터라면
$ git clone <REMOTE REPO URL.git> # downloadZIP => .git 없음
# 작업작업
$ git add . && git commit -m 'MSG' && git push
$ git add . ; git commit -m 'MSG' ; git push 

$ git pull
```