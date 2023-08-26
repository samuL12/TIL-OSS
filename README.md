# TIL

## TIL

### TIL

chat gpt 에서 아래처럼 백틱 사용해야 코드로 인식 더 잘함
아래 코드에서 버그를 찾아줘.

---
### 백틱 이란?

키보드 물결표시에 있는 막대기

---

````js
function fetchName(){
}
````

이 저장소를 진행하시려면 클론받은 경로로 이동하고,
xxx 합니다.

IntelliJ 커밋 명령어
````bash
Ctrl + k + l
````

````bash
cd TIL
````

``fetchName``

|   | id | name | phone |   |
|---|----|------|-------|---|
|   | 1  | kkd  |       |   |
|   | 2  | lld  |       |   |
|   | 3  | kyi  |       |   |

---
## 브랜치 정의
1. A branch in Git is simply a lightweight movable pointer to one of these commits. 
    - 참고: https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell
2. Git branches are effectively a pointer to a snapshot of your changes.
    - 참고: https://www.atlassian.com/git/tutorials/using-branches
---
## 브랜치 합치기
- 이슈에 해당하는 작업을 수행할 때, 별도의 브랜치를 만들고 작업
- 작업이 끝난 후에넌, Pr(Pull request)을 사용해 내가 작업한 브랜치를 중요 브랜치(`main`, `master`, `development`, `devel로` 병합

### 명령어
- `git merge`
- 주의할 점: `A`브랜치를 `B`브랜치로 합치려고 할 때는 `A`브랜치를 체크아웃 한 상태에서 `git merge B`를 입력