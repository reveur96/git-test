# Wecode Git Test

git command에 대한 개념 정리 
- `git init` : 현재 디렉토리를 기준으로 git 저장소를 생성, 초기 세팅하는 단계
- `git remote add origin <remote repository url>` : 원격저장소의 레파지토리를 로컬 저장소와 연결
- `git add <file name>` : 새로운 파일을 해당 이름으로 생성
- `git commit`: 로컬에서 원격 저장소로 push하기 전 변경된 파일을 로컬에 저장해서 기록을 남긴다. commit message를 통해 어떤 변경 사항이 있는지 기록할 수 있다. 커밋으로 버전 관리가 용이하다.
- `git push origin <branch name>` : 원격 저장소의 해당 브랜치로 push, 로컬에서 원격 저장소로 보낸다. 
- `git pull origin <branch name>` : 원격에서 로컬로 해당 브랜치의 파일들을 받아온다.
- `git merge <branch name>` :  현재 파일 브랜치의 파일들과 merge 뒤의 브랜치의 파일들을 merge 한다. 
