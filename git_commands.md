# Git 필수 명령어 모음집

저장소 초기화: 새로운 로컬 Git 저장소를 생성합니다.
`git init`

원격 저장소 추가: 로컬 저장소에 새로운 원격 저장소(GitHub) 주소를 연결합니다.
`git remote add origin https://github.com/Leetg-debug/foresight.git`

원격 저장소 변경: 이미 연결된 원격 저장소의 주소를 다른 주소로 업데이트합니다.
`git remote set-url origin https://github.com/Leetg-debug/foresight.git`

원격 저장소 확인: 현재 연결되어 있는 원격 저장소의 이름과 주소 목록을 확인합니다.
`git remote -v`

상태 확인: 수정되거나 추가된 파일들의 현재 상태를 확인합니다.
`git status`

파일 추가: 변경된 모든 파일을 커밋할 준비 상태(Staging Area)로 올립니다.
`git add .`

커밋 생성: 추가된 파일들을 영구적인 작업 내역으로 확정하고 메모를 남깁니다.
`git commit -m "작업 내용 설명"`

브랜치명 변경: 현재 작업 중인 브랜치의 이름을 'main'으로 변경합니다.
`git branch -M main`

최초 업로드: 커밋 내역을 원격 저장소에 처음 업로드하며 기본 브랜치로 연결(Tracking)합니다.
`git push -u origin main`

일반 업로드: 이후 추가로 작업하고 커밋한 내역들을 원격 저장소에 업로드합니다.
`git push`

저장소 업데이트: 원격 저장소에 있는 최신 코드를 내 컴퓨터로 받아와 병합합니다.
`git pull origin main`

저장소 복제: GitHub에 있는 원격 저장소를 내 컴퓨터의 현재 폴더로 통째로 다운로드합니다.
`git clone https://github.com/Leetg-debug/foresight.git`

브랜치 생성 및 이동: 새로운 브랜치를 만듦과 동시에 해당 브랜치로 작업 환경을 바꿉니다.
`git checkout -b 새로운_브랜치명`

커밋 기록 확인: 지금까지 작업하고 확정(Commit)한 이력들을 확인합니다.
`git log`

마지막 커밋 취소: 방금 남긴 커밋을 취소하되, 작업했던 파일의 변경 내용은 그대로 유지합니다.
`git reset HEAD~1`