# GposGitTutorial

## 프로젝트의 목적
이 프로젝트는 지포스 동아리의 깃 교육을 위해 생성되었습니다. 다음 과정을 거쳐서 깃의 기초적인 명령어를 배울 예정입니다.

## 깃 설치
시작에 앞서 깃을 설치해야 합니다. 필요한 경우, GCC 또한 같이 설치합니다. 이 과정은 깃 홈페이지에서 참고하세요.

## Git Clone, Git init
깃을 시작하는 방법은 git init이나 git clone으로 시작됩니다. 

## Git add
깃으로 파일을 관리하기 위해서는, add명령어로 관리대상에 추가해야 합니다. Git rm을 통해 관리 대상에서 제거할수도 있습니다. (이 경우, 파일이 삭제되므로, 이전 커밋으로 되돌리거나, 백업을 염두해야 합니다.)

자신의 이름을 적고, 그 안에 Txt 파일로 "something"을 만든 뒤, git add를 하세요.

## Git Commit 
git에서 관리되는 파일들은 값이 바뀌면 commit으로 저장할 수 있습니다. git commit를 하거나 git commit -m "(여기에 원하는 메세지 입력)"을 하시면 저장이 됩니다. 

## Git push
이제까지 git은 여러분의 컴퓨터에서 파일을 관리했습니다. github에 저장된 파일을 업로드하기 위해선 git push 를 사용해야 합니다. 이 과정은 다음과 같습니다. 
```
git remote add origin https://github.com/wt6248/GposGitTutorial.git
git push -u origin main
```
이 일련의 과정을 진행한 뒤, 깃허브 홈페이지에서 업로드 된 파일을 확인해보세요. 

https://github.com/wt6248/GposGitTutorial






## 백업
### …or create a new repository on the command line
```
echo "# GposGitTutorial" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/wt6248/GposGitTutorial.git
git push -u origin main
```
### …or push an existing repository from the command line
```
git remote add origin https://github.com/wt6248/GposGitTutorial.git
git branch -M main
git push -u origin main
```