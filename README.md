# calc-exam-1

# 목표
- 브랜치를 이용해 기능을 구현하고 merge하는 방법 익히기
  - 브랜치를 생성해 기능을 구현. 해당 브랜치에서 merge하고 테스트 한 뒤, 테스트가 끝나면 master 브랜치에 다시 merge.

# 예제 가이드
- master 브랜치의 head(최신 커밋)에서 브랜치를 생성합니다.
- 브랜치의 이름은 맡은 기능에 따라 feature/minus, feature/multiple 등 feature/[기능] 으로 지어주세요.
- 생성한 브랜치(feature/기능)를 checkout하고 해당 기능을 구현하고 커밋.
- 다시 master 브랜치를 체크아웃하고 방금 구현했던 코드를 수정하고 커밋합니다.(merge 충돌 상황을 만들기 위해)
- 다시 feature/기능 브랜치를 체크아웃한 상태에서 master 브랜치를 merge.
- merge confilct를 해결하라는 메세지가 뜨면 해결하고 기능이 정상인지 확인.
- 다시 master 브랜치를 체크아웃해 feature/기능 브랜치를 merge하고 feature/기능 브랜치 삭제


참고 : feature 브랜치를 로컬에서 지웠지만 원격 저장소에는 해당 브랜치가 아직 남아있을 수 있음.
그럴 경우
```
git push origin --delete feature/add 
```
와 같은 방식으로 지울 수 있음.


