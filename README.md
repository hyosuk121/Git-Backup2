# Git Backup
## 용어
> `Local Repository`: 지역 저장소
> `Remote Repository`: 원격 저장소
> `Push`: 지역 저장소의 commit들을 원격 저장소에 옮김
> `Pull`: 원격 저장소의 commit들을 로컬 저장소로 당겨옴
> `clone`: 원격 저장소에 저장된 commit들을 다른 지역 저장소에 복제
## 연결
- `git remote`: 현재 등록된 원격 저장소를 보여줌
- `git remote -v`: 현재 등록된 원격 저장소를 상세히 보여줌
- `git remote add [name] [주소명]`: 원결 저장소와 현재 지역 저장소를 연결함
## PUSH
- github 계정 등록
- `git push origin master`: master 브랜치를 원격 저장소롤 push
 ## CLONE
 - `git clone [.git url]`: 원격 저장소 전체를 복제

## PULL
- `git pull`: 원격 저장소로 부터 전체 commit을 당겨옴
