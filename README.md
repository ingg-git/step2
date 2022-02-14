# mission2

#### step2

- 다른 브랜치로 이동
  - `git checkout main`
- 머지된 브랜치 제거
  - `git branch -D inkyojeong`
- `git remote add [저장소_별칭] [base_저장소]`
  - ex) `git remote add upstream git remote add upstream https://github.com/ingg-git/mission2.git`
- 내 브랜치 가져오기(갱신)
  - `git fetch upstream inkyojeong`
- rebase로 동기화
  - `git rebase upstream/inkyojeong`
- step2:새로운 브랜치 생성
  - ex) `git checkout -b step2-inkyojeong`
