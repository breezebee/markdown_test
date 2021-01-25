# 마크다운 언어로 정리
## **Git과 Github의 차이점**
- **Git이란** - 로컬에서 소스코드를 버전으로 관리하는 시스템
- **Github란** - 로컬에서 관리한 소스코드를 업로드하고 공유할 수 있는 공간
---
## **init, add, commit -m**
- `git init` - 폴더를 깃 저장소로 만들고 싶을 때 사용하는 명령어
- `git add` - 수정한 파일들을 add로 스테이지에 추가하는 명령어
- `git commit -m "commit message` - 스테이징 한 파일들을 커밋하는 명령어
---
## **remote, clone, push, pull**
- `git remote` - 원격 저장소를 관리 할 수 있는 명령어 add, rename, rm 등의 옵션이 있다.
- `git clone <url>` - 서버의 프로젝트를 로컬에 내려받을 때 사용하는 명령어
- `git push <name> <branch` - 깃허브에 내 로컬에 있는 코드를 올릴때 사용하는 명령어
- `git pull <remote> <branch>` - 다른 사람이 코드를 업데이트 했을때 내 로컬과 다른 부분이 있기 때문에 pull로 새로 바뀐 코드를 가져와야할때 사용하는 명령어
---
![image](https://i.ytimg.com/vi/0nqJKEh3YCc/maxresdefault.jpg)
---
## **branch, checkout**
- `git branch` - 브랜치란 원래 코드와 독립적으로 개발을 진행할 수 있도록 독립적인 공간을 새로 만드는 것이다. 
- `git checkout <branch name>` - 존재하는 어떤 브랜치로 checkout을 하게 되면 해당 브랜치로 이동할 수 있게 된다. 
---
## **merge (fast-forward/Merge conflict)**
- **merge** - 깃을 관리하면서 다른 브랜치에서 생성된 파일들을 하나로 합쳐야 할 일이 발생한다. 그것을 merge하는 과정이라고 한다. 
- **Fast-forward** - 동일 내용이 포함되는 브랜치일 경우 브랜치 이동만으로 병합해서 따로 commit을 생성하지 않는 merge
  - `git merge <NAME>`
- **Merge conflict** - 서로 다른 파일을 수정하거나 같은 파일을 수정한 후 merge하는 과정에서 다른 내용으로 인한 충돌이 발생하는 경우 
---
