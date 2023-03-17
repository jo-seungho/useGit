# Git 사용법

### 1. 새로운 브랜치 생성
```
git branch <브랜치 이름>
```   
<br/>


### 2. 새로운 브랜치 생성후 해당 브랜치로 전환
```
git switch -c <브랜치이름>
git checkout -b <브랜치이름>
```
<br/>

### 3. 브랜치 목록 확인
```
git branch
```
<br/>

### 4. 브랜치 목록과 각 브랜치의 최근 커밋 확인
```
git branch -v
```
<br/>

### 5. 브랜치 삭제
```
git branch -d <삭제할브랜치이름>
git branch -D       // 병합하지 않은 브랜치 강제 삭제
```
<br/>

### 6. 브랜치 전환
```
git switch <브랜치이름>
git checkout <브랜치이름>
```
<br/>

### 7. 브랜치 병합
```
git checkout <루트브랜치>
git merge <병합할브랜치>
```
<br/>

### 8. 로그에 모든 브랜치를 그래프로 표현
```
git log --branch --graph --decorate
```
<br/>

### 9. 아직 커밋하지 않은 작업을 stack에 임시로 저장
```
git stash
```
<br/>

### 10. 기존과 변경된 파일들을 확인하고 싶을 때
```
git status
```
