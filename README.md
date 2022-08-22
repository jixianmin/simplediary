# 인프런의 강의 한입 크기로 잘라 먹는 리액트

## Simplediary를 feature/simplediary 에서 제작하는중입니다!

Redux를 사용하였습니다.

## feature/hyeonmin 에서 Router을 이용한 감정일기장를 제작하는중입니다!

React초기세팅에서 ESLint, Prettier 설치 및 설정을 노션에서 ESLint + Prettier 세팅 가이드를 참고하였습니다!

## Git사용법에 대한 연구중입니다.

git remote -v는 현제 git에 등록된 원격 저장소 리스트를 보여줍니다

원격 저장소 해제 git remote remove <name>명령어는 원격 저장소를 git의 설정에서 삭제합니다.저의경우 <name>을 origin 으로 해놨습니다 git remote remove origin

원격 저장소 등록 git remote add <name> <url>명령어는 url으로 원격 저장소를 등록합니다.

기존 origin 제거 git remove origin

기본 세팅을 한뒤 git init => git remote add origin https://github.com/jixianmin/simplediary.git

=> add . => commit => push를 진행했습니다,

다른브랜치로 이후 진행할 계획입니다

git checkout -b feature/simplediary

Readme의 경우 초반 세팅 이후 다시 작성했기 때문에 해당 브랜치에서 변동한 Readme의 경우

git pull origin master를 진행 합니다

또한 해당 브랜치에서 error없이 기본작업이 된것을 master 브랜치에서

git merge feature/simplediary 해보니 해당 작업이 문제없이 병합된걸 확인했습니다!

또한 이러한 많은 작업을 진행하면서 메인 브랜치에 커밋이 3개가 쌓여있는것을 확인했고

그문제를 해결하기 위해 Squash를 진행하였습니다

git rebase -i (git log맨처음 커밋) => 중간 과정 생략 => git push

어떻게 해도 스쿼시가 안되는걸 보니 메인 브랜치는 안되는것 같습니다.
