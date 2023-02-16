# Git에 대한 정의

1. Git이란?
- 분산형 버전 관리 시스템
- 소스 코드의 버전 관리를 위해 개발됨
- 리눅스 커널의 소스 코드 관리를 위해 Linus Torvalds가 개발
- 현재 대부분의 소프트웨어 개발 프로젝트에서 사용

2. Git의 기능
- 소스 코드 변경 사항 추적
- 변경 이력 관리
- 언제든지 이전 버전으로 되돌릴 수 있는 기능
- 여러 개발자들이 동시에 개발을 진행할 때 충돌 방지
- 독립적으로 작업한 내용 병합 기능

3. Git의 인터페이스
- 명령 줄 인터페이스(Command Line Interface)
- 웹 기반 호스팅 서비스(GitHub 등)를 이용하여 저장소 관리

4. Git의 라이선스
- 자유로운 라이선스로 배포
- Windows, macOS, Linux 등 다양한 운영 체제에서 사용 가능


# GitHub에 대한 정의

1. GitHub이란?
- Git 기반의 코드 호스팅 플랫폼
- 오픈 소스 소프트웨어를 지원하는 플랫폼
- 코드 저장소를 호스팅하고 관리할 수 있음
- 이슈 트래킹, 코드 검토, 웹호스팅 등 다양한 기능 제공

2. GitHub의 기능
- 코드 저장소 호스팅
- 코드 검색 기능
- 이슈 트래킹 기능
- 코드 검토 기능
- 웹호스팅 기능
- 다양한 협업 기능(풀 리퀘스트, 머지 등)

3. GitHub의 인터페이스
- 웹 기반 인터페이스
- Git과 CLI(Command Line Interface)를 이용한 인터페이스

4. GitHub의 라이선스
- GitHub의 소스 코드는 Git과 마찬가지로 자유 소프트웨어 라이선스를 따름
- 다양한 유형의 라이선스 설정 가능

# Git과 GitHub의 차이

1. Git과 GitHub란?
- Git: 분산형 버전 관리 시스템
- GitHub: Git 기반의 코드 호스팅 플랫폼

2. 기능
- Git: 코드의 버전 관리, 변경 이력 추적, 병합, 충돌 방지 등의 기능
- GitHub: Git의 기능에 더해, 코드 저장소 호스팅, 이슈 트래킹, 코드 검토, 웹호스팅 등 다양한 기능 제공

3. 인터페이스
- Git: 명령 줄 인터페이스(Command Line Interface)
- GitHub: Git과 CLI(Command Line Interface)를 이용한 인터페이스를 제공하는 동시에, 웹 기반 인터페이스도 제공

4. 사용자
- Git: 개발자, 프로젝트 매니저 등 코드 버전 관리에 관심 있는 사용자
- GitHub: Git을 이용하여 코드를 호스팅하고, 코드에 기여하며, 오픈 소스 소프트웨어에 참여하려는 사용자

5. 라이선스
- Git: 자유로운 라이선스로 배포
- GitHub: Git의 라이선스에 더해, 다양한 유형의 라이선스 설정 가능

# GitHub Token이란?

- GitHub API를 사용하여 데이터를 검색, 업데이트 또는 삭제할 때 사용되는 액세스 토큰입니다.

## GitHub Token 생성 방법

1. GitHub 계정에 로그인합니다.
2. 상단 메뉴에서 'Settings'를 클릭합니다.
3. 왼쪽 사이드바에서 'Developer settings' -> 'Personal access tokens'을 클릭합니다.
4. 'Generate new token'을 클릭합니다.
5. 토큰의 이름과 스코프를 설정하고, 생성합니다.
6. 생성된 토큰은 한 번만 보여지므로, 안전한 곳에 보관합니다.

## GitHub Token 사용 방법

1. GitHub API에 요청을 보낼 때, 요청 헤더에 생성한 토큰을 포함시킵니다.
2. 생성한 토큰의 스코프에 따라 API의 기능을 사용할 수 있습니다.
   - 스코프를 더 많이 설정할수록 API를 더 많이 사용할 수 있습니다.

## 주의사항

- 생성한 토큰은 안전한 곳에 보관해야 합니다.
- 토큰은 API 요청을 통해 삭제되거나 만료될 수 있습니다.
- 토큰이 노출될 경우, 다른 사람이 API를 통해 데이터에 접근할 수 있으므로, 안전한 곳에 보관해야 합니다.


# Git clone에 대한 정의

1. Git clone이란?
- 원격 저장소에 있는 Git 저장소를 로컬로 복사하는 명령어
- 로컬 저장소를 새로 생성하고, 해당 저장소를 원격 저장소의 복사본으로 만듦

2. Git clone 명령어
- `git clone <url>` 명령어를 사용하여 클론을 실행
- `<url>`은 원격 저장소의 URL 주소를 입력하는 부분으로, 클론을 실행할 원격 저장소의 URL을 입력

3. Git clone 기능
- 로컬 저장소 생성 및 초기화
- 원격 저장소의 파일 및 폴더를 복사
- 원격 저장소와 연결

4. Git clone 사용 예시
- `git clone https://github.com/user/repo.git` 명령어를 사용하여 GitHub의 `user` 계정에 있는 `repo` 저장소를 로컬에 복사
- `git clone git@github.com:user/repo.git` 명령어를 사용하여 SSH 프로토콜을 이용하여 `user` 계정의 `repo` 저장소를 로컬에 복사

# Git add에 대한 정의

1. Git add이란?
- Git 저장소에서 작업한 변경 사항 중 스테이징 영역에 추가하고, 커밋할 준비를 하는 명령어

2. Git add 명령어
- `git add <file>` 명령어를 사용하여 변경된 파일을 스테이징 영역에 추가
- `git add .` 명령어를 사용하여 변경된 모든 파일을 스테이징 영역에 추가
- `git add -u` 명령어를 사용하여 변경된 파일 중 삭제된 파일을 제외한 모든 파일을 스테이징 영역에 추가

3. Git add 기능
- 스테이징 영역에 파일을 추가하여, 커밋할 준비를 함
- 수정된 파일만 스테이징 하기 위해 선택적으로 파일을 추가할 수 있음

4. Git add 사용 예시
- `git add file.txt` 명령어를 사용하여 `file.txt` 파일을 스테이징 영역에 추가
- `git add .` 명령어를 사용하여 변경된 모든 파일을 스테이징 영역에 추가
- `git add -u` 명령어를 사용하여 변경된 파일 중 삭제된 파일을 제외한 모든 파일을 스테이징 영역에 추가

# Git commit에 대한 정의

1. Git commit이란?
- Git 저장소에 변경된 내용을 기록하는 명령어
- 변경된 파일들의 스냅샷을 생성하여 Git 저장소에 저장

2. Git commit 명령어
- `git commit -m "Commit message"` 명령어를 사용하여 커밋 생성
- `-m` 옵션은 커밋 메시지를 입력하는 옵션으로, 커밋의 변경 내용을 간략하게 작성

3. Git commit 기능
- 변경 내용의 스냅샷을 생성하여 Git 저장소에 저장
- 커밋 메시지를 작성하여, 변경 내용을 이해할 수 있도록 함
- 이전 커밋과 현재 커밋 사이의 차이를 비교 가능

4. Git commit 사용 예시
- `git commit -m "Add new feature"` 명령어를 사용하여 "Add new feature"라는 커밋 메시지와 함께 변경 내용을 스냅샷으로 커밋 생성
- `git commit -m "Update file contents"` 명령어를 사용하여 "Update file contents"라는 커밋 메시지와 함께 변경 내용을 스냅샷으로 커밋 생성


# Git push에 대한 정의

1. Git push란?
- 로컬 Git 저장소의 커밋 기록을 원격 저장소에 업로드하는 명령어
- 커밋 기록을 원격 저장소에 적용하여 다른 개발자들과 변경 사항을 공유

2. Git push 명령어
- `git push <remote> <branch>` 명령어를 사용하여 로컬 Git 저장소의 커밋 기록을 원격 저장소에 업로드
- `<remote>`는 원격 저장소의 이름을, `<branch>`는 업로드할 브랜치의 이름을 입력

3. Git push 기능
- 로컬 Git 저장소에서 변경된 내용을 원격 저장소에 적용하여 다른 개발자들과 변경 사항을 공유
- Git pull 명령어를 사용하여, 원격 저장소의 변경 사항을 로컬 Git 저장소로 가져올 수 있음

4. Git push 사용 예시
- `git push origin master` 명령어를 사용하여 `origin`이라는 이름의 원격 저장소의 `master` 브랜치로 커밋 기록을 업로드
- `git push origin develop` 명령어를 사용하여 `origin`이라는 이름의 원격 저장소의 `develop` 브랜치로 커밋 기록을 업로드


# Git checkout에 대한 정의

1. Git checkout이란?
- Git 저장소에서 브랜치를 변경하거나, 특정 커밋으로 이동하는 명령어
- 변경된 파일의 버전을 이전 상태로 되돌릴 수 있음

2. Git checkout 명령어
- `git checkout <branch>` 명령어를 사용하여 브랜치를 변경
- `git checkout <commit>` 명령어를 사용하여 특정 커밋으로 이동

3. Git checkout 기능
- 브랜치를 변경하여, 코드의 변경 사항을 관리
- 커밋을 이동하여, 코드를 이전 상태로 되돌릴 수 있음

4. Git checkout 사용 예시
- `git checkout feature` 명령어를 사용하여 `feature` 브랜치로 변경
- `git checkout develop` 명령어를 사용하여 `develop` 브랜치로 변경
- `git checkout <commit>` 명령어를 사용하여 `<commit>`에서 변경된 내용을 확인할 수 있음

# Git merge에 대한 정의

1. Git merge란?
- Git에서 브랜치를 병합하는 명령어
- 브랜치를 병합하여 변경 이력을 합치고, 충돌을 해결함

2. Git merge 명령어
- `git merge <branch>` 명령어를 사용하여 브랜치를 병합
- `<branch>`는 병합할 대상 브랜치의 이름을 입력

3. Git merge 기능
- 브랜치를 병합하여, 변경 이력을 합침
- 충돌이 발생하면, 충돌을 해결하여 병합 가능

4. Git merge 사용 예시
- `git merge feature` 명령어를 사용하여 `feature` 브랜치를 현재 브랜치로 병합
- `git merge develop` 명령어를 사용하여 `develop` 브랜치를 현재 브랜치로 병합

# Git rebase에 대한 정의

1. Git rebase란?
- Git에서 브랜치를 변경하거나 병합하는 명령어
- 커밋 기록을 수정하여, 이력을 더 깔끔하게 관리할 수 있음

2. Git rebase 명령어
- `git rebase <branch>` 명령어를 사용하여 브랜치를 변경하거나 병합
- `<branch>`는 변경하거나 병합할 브랜치의 이름을 입력

3. Git rebase 기능
- 커밋 기록을 수정하여, 이력을 더 깔끔하게 관리할 수 있음
- 브랜치를 변경하거나 병합하여, 변경 이력을 합침

4. Git rebase 사용 예시
- `git rebase develop` 명령어를 사용하여 `develop` 브랜치의 변경 내용을 현재 브랜치에 반영
- `git rebase -i HEAD~3` 명령어를 사용하여 최근 3개의 커밋을 대상으로 인터랙티브하게 rebase 수행


# Git merge와 rebase의 차이

1. Git merge와 rebase란?
- Git에서 브랜치를 병합하거나 변경하는 명령어
- merge는 브랜치를 병합하여 새로운 커밋을 생성, rebase는 브랜치를 변경하여 커밋 이력을 수정하여 변경 이력을 합침

2. Git merge의 특징
- 브랜치를 병합하여 새로운 커밋을 생성
- 병합된 커밋이 새로운 브랜치를 생성하거나, 다른 브랜치에 머지되는 형태로 저장됨
- 충돌이 발생하면 충돌을 해결하여 병합 가능

3. Git rebase의 특징
- 브랜치를 변경하여 커밋 이력을 수정하여 변경 이력을 합침
- rebase가 수행된 브랜치의 기록이 새로운 기록으로 덮어씌워짐
- 기존 커밋을 수정하므로, conflict가 발생할 수 있음

4. Git merge와 rebase 사용 시 고려사항
- merge는 변경 이력을 새로운 브랜치에 저장하므로, 다른 개발자들과 변경 이력을 공유하고 싶을 때 사용
- rebase는 커밋 이력을 수정하므로, 다른 개발자들과 변경 이력을 공유하지 않고, 혼자 작업할 때 사용
- 브랜치를 병합할 때, merge는 항상 새로운 커밋을 생성하고, rebase는 커밋 이력을 수정할 수 있는지 고려하여 사용


# Git reset에 대한 정의

1. Git reset이란?
- Git에서 이전 커밋으로 되돌리거나, 스테이징 영역에서 파일을 제거하는 명령어
- Git 저장소에서 변경 이력을 삭제

2. Git reset 명령어
- `git reset <commit>` 명령어를 사용하여 이전 커밋으로 되돌림
- `git reset HEAD <file>` 명령어를 사용하여 스테이징 영역에서 파일을 제거

3. Git reset 기능
- 이전 커밋으로 되돌려, Git 저장소에서 변경 이력 삭제
- 스테이징 영역에서 파일을 제거하여, 커밋하지 않도록 함

4. Git reset 사용 예시
- `git reset HEAD~1` 명령어를 사용하여 마지막 커밋을 삭제
- `git reset HEAD file.txt` 명령어를 사용하여 `file.txt` 파일을 스테이징 영역에서 제거

# Git push --force에 대한 정의

1. Git push --force란?
- Git에서 원격 저장소에 강제로 변경된 내용을 푸시하는 명령어
- 원격 저장소의 변경 이력을 덮어쓰기 가능

2. Git push --force 사용 시 고려사항
- 다른 개발자와 공유하고 있는 원격 저장소의 변경 이력을 덮어씌우므로, 사용 전 반드시 주의가 필요
- 다른 개발자와 공유하고 있는 원격 저장소의 변경 이력을 덮어쓰면, 이전 이력은 영구적으로 삭제됨
- 대부분의 경우, push --force 대신 revert나 reset을 사용하여 이전 변경 이력을 복구할 수 있음

3. Git push --force 사용 예시
- `git push --force origin master` 명령어를 사용하여 `master` 브랜치의 변경 내용을 강제로 푸시함
- `git push -f origin feature` 명령어를 사용하여 `feature` 브랜치의 변경 내용을 강제로 푸시함
- `git push --force-with-lease` 명령어를 사용하여 원격 저장소의 변경 이력을 확인하고, 충돌이 발생하지 않을 때에만 강제로 푸시함


# Git pull에 대한 정의

1. Git pull이란?
- Git에서 원격 저장소의 최신 변경 내용을 로컬 저장소로 가져오는 명령어
- fetch와 merge가 결합한 명령어

2. Git pull 명령어
- `git pull` 명령어를 사용하여 원격 저장소의 변경 내용을 가져옴
- 가져온 변경 내용을 로컬 브랜치에 병합하여, 로컬 저장소에 반영

3. Git pull 사용 시 고려사항
- pull 명령어는 merge를 수행하기 때문에, 충돌이 발생할 수 있음
- pull 명령어를 사용하면, 현재 브랜치가 원격 저장소의 최신 상태와 일치하게 됨

4. Git pull 사용 예시
- `git pull origin master` 명령어를 사용하여 `master` 브랜치의 변경 내용을 로컬 저장소로 가져옴
- `git pull origin feature` 명령어를 사용하여 `feature` 브랜치의 변경 내용을 로컬 저장소로 가져옴


# Git conflict 해결 방법

1. Git conflict란?
- 동일한 파일의 다른 부분을 수정하고, 변경 이력을 푸시하면 충돌이 발생하는 현상

2. Git conflict 해결 방법
- `git status` 명령어를 사용하여 충돌이 발생한 파일 확인
- 충돌이 발생한 파일에서 `<<<<<<`과 `>>>>>>` 사이에 있는 내용을 수정하여 충돌 해결
- 충돌을 해결한 파일을 `git add` 명령어를 사용하여 스테이징 영역에 추가
- `git commit` 명령어를 사용하여 커밋 생성
- `git log` 명령어를 사용하여 변경 이력 확인

3. Git conflict 예방 방법
- 코드 작성 전에 다른 개발자와 코드 작업 일정 및 구조에 대해 미리 논의하여 충돌을 예방
- 작업 전에 최신 변경 내용을 가져와서, 작업 도중 충돌이 발생하지 않도록 함
- 작업 도중 충돌이 발생했을 경우, 가능한 빠르게 해결하여 코드 변경 내용이 최신 상태를 유지하도록 함


# Git revert에 대한 정의

1. Git revert란?
- Git 저장소에서 특정 커밋을 취소하고, 이전 상태로 되돌리는 명령어
- 변경 이력을 삭제하지 않고, 변경 이력을 새로 생성하여 이전 상태로 돌아감

2. Git revert 명령어
- `git revert <commit>` 명령어를 사용하여 커밋을 취소하고, 변경 이력을 새로 생성
- 새로운 커밋이 생성되며, 해당 커밋에서 삭제된 변경 내용을 확인 가능

3. Git revert 기능
- 이전 커밋에서 변경된 내용을 삭제하지 않고, 새로운 커밋을 생성하여 이전 상태로 되돌림
- 변경 이력을 삭제하지 않으므로, 다른 개발자와 변경 사항 공유가 가능

4. Git revert 사용 예시
- `git revert HEAD` 명령어를 사용하여 마지막 커밋을 취소하고, 변경 이력을 새로 생성
- `git revert <commit>` 명령어를 사용하여 `<commit>`에서 변경된 내용을 삭제하고, 변경 이력을 새로 생성


# 소스트리에서 Git 사용법

1. 저장소 clone 하기
- 소스트리 상단 메뉴에서 'File' -> 'Clone / New'를 선택합니다.
- 원하는 Git 저장소의 URL과 저장될 로컬 경로를 입력하고, 'Clone' 버튼을 클릭합니다.

2. 변경 사항 확인하기
- 소스트리 좌측 메뉴에서 'Git'을 선택하면, Git 저장소 목록이 표시됩니다.
- 해당 저장소를 선택하면, 저장소에 있는 파일 목록이 표시됩니다.
- 수정된 파일이 있는 경우 파일 이름이 볼드체로 표시됩니다.

3. 파일 수정 및 커밋
- 저장소에서 수정하고 싶은 파일을 선택하고, 수정합니다.
- 소스트리에서 수정된 파일을 확인한 후, 'Stage' 버튼을 클릭합니다.
- 'Commit' 버튼을 클릭하고, 커밋 메시지를 입력한 후 'Commit' 버튼을 다시 클릭합니다.

4. 브랜치 관리하기
- 소스트리 좌측 메뉴에서 '브랜치' 탭을 선택합니다.
- 브랜치 목록에서 브랜치를 선택하면, 해당 브랜치에서 작업할 수 있습니다.
- 브랜치를 새로 생성하거나, 브랜치를 병합하는 등의 작업도 가능합니다.

5. Pull Request 작성하기
- GitHub 등의 원격 저장소에서 Pull Request를 생성하면, 소스트리에서도 Pull Request를 확인할 수 있습니다.
- Pull Request를 클릭하면, 변경 사항을 확인하고 Merge할 수 있습니다.


# Git branch를 이해하는데 도움이 되는 사이트 소개

1. Atlassian Git Branching
- Git branch를 처음 접하는 사용자를 대상으로, Git branch의 기본 개념과 사용 방법 등을 다룹니다.
- 링크: https://www.atlassian.com/git/tutorials/using-branches

2. Visualizing Git
- Git branch와 merge에 대한 개념을 시각적으로 이해할 수 있는 사이트입니다.
- 링크: https://git-school.github.io/visualizing-git/

3. Learn Git Branching
- 인터랙티브한 Git branch 학습 플랫폼으로, Git branch의 기본 개념부터 심화적인 내용까지 다양한 학습 콘텐츠를 제공합니다.
- 링크: https://learngitbranching.js.org/

위 세 가지 사이트는 Git branch를 이해하고 학습할 수 있는 무료 온라인 플랫폼입니다. Git branch의 기본 개념부터 원리와 기능까지 다양한 내용을 다루며, Git을 보다 더 효율적으로 사용할 수 있도록 도와줍니다.


# Git을 이해하는데 도움이 되는 강좌

1. 생활코딩 Git
- Git의 기초적인 개념부터 브랜치, 병합, 협업 등 Git의 전반적인 사용법을 다룹니다.
- 링크: https://opentutorials.org/course/2708

2. Visual Studio Code로 배우는 Git & GitHub
- Visual Studio Code를 사용하여 Git의 기본적인 사용법부터 원리와 고급 기능까지 다룹니다.
- 링크: https://www.inflearn.com/course/git-and-github-davinci-codes#

3. Git 강좌 - Try Git
- Git의 기본 개념부터 브랜치, 병합, 협업, Pull Request 등 Git의 사용법을 다룹니다.
- 링크: https://try.github.io/
