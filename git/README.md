# Git 사용과 이해
1. Git이란?
분산 버전관리 시스템(Distributed Version control Systems - DVCS)

2. 장점
- 협업에서 수정하는 여러 변경사항들을 쉽게 관리 할 수 있다. (버전을 관리함으로 써)
- 인터넷 연결이 되지 않은 곳에서도 개발을 진행 분산 버전관리이기 때문에 중앙 저장소가 삭제되어도 원상복구
(각 협업자들은 원래 소스코드의 내용에서 각자 본인이 바꾼 부분의 버전을 가지고 있다.)

3. 기본 용어
- Repository : 저장소
- Staging Area : 저장소에 commit하기 전에 commit을 준비하는 위치
- Commit : 현재 변경된 작업 상태를 점검을 마치며 확정하고 저장소에 저장하는 작업
- Head : 현재 작업중인 Branch를 가리킨다.
- Branch : 가지 도는 분기점 작업을 할때에 **현재 상태를 복사**하여 Branch 작업을 한 후에 완전하다 싶을 때 Merge하여 작업을 한다.
- Merge : 다른 Branch의 내용을 현재 Branch로 가져와 합치는 작업

4. git 기본 명령어
- git help : 도움말 기능 (사용법이 궁금한 명령어 -> 'git help [궁금한 명령어]' 를 타이핑 시, 설정과 사용에 대한 도움말 출력
- git init : 깃 저장소를 초기화. 저장소나 디렉토리 안에서 이 명령을 실행하기 전가지 일반적인 폴더 -> 한 후에 추가적인 깃 명령어 입력 가능
- git status : 저장소 상태 체크. 어떤 파일이 저장소에 있는지, 커밋이 필요한 변경사항이 있는지, 현재 저장소의 어떤 브랜치에서 작업하고 있는지 등의 상태정보 출력
- git branch : 새로운 브렌치 생성. 여러 협업자와 작업할 시, 이 명령어로 새로운 브랜치를 만들고, 자신만의 변경사항과 파일 추가 등의 커밋 타임라인을 생성, 완성 후 협업자의 branch와 merge
- git add : 'staging 영역'에 변경 내용 추가. 다음 commit 명령 전까지 변경분을 staging 영역에 보관하여 변동 내역을 저장.
![image](https://user-images.githubusercontent.com/105041834/187134112-e71b2822-c75a-4d6d-943e-abfbba849874.png)
- git commit : staging area에 있는 변경 내용 묶음 및 정의.
git commit -m [커밋 메세지] : staging area에 있는 내용은 "커밋 메세지"를 반영한 수정본 파일의 묶음
- git log : 커밋 내역 확인
- git push : 로컬 컴퓨터에서 서버로 변경사항을 "push"
- git pull : 서버 저장소로부터 최신 버전을 "pull" (서버 저장소의 데이터를 가져와, 현재 브렌치와 merge)
- git clone : 서버 저장소의 데이터를 로컬 컴퓨터로 복사.
- git checkout : 작업하기 원하는 브랜치로 이동
cf1) git checkout Yana : Yana 브렌치로 이동
cf2) git checkout -b 야나 : '야나' 라는 브렌치를 생성 후 야나 브렌치로 이동(생성과 이동 동시에)
- git merge : 개별 branch에서 마친 작업을 master branch로 병합.


5. References
- [참고](https://yanacoding.tistory.com/4)
- [참고](https://it-eldorado.tistory.com/4)
