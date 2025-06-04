# git의 3공간
## git으로 버전관리 시작하기
- git으로 버전을 관리하기 위해서 -> 먼저 해ㅝ야 할 것
  - git아, 이 디렉토리 이제부터 니가 관리해!
  
```bash
git init
```

- 디렉토리별로 딱! 한번만 한다.


## git의 3공간


계속해서 저장할때마다 새로운걸 어떤걸 저장했는지 확인하기 위해 만든다


# git의 3공간
## git으로 버전관리 시작하기
- git으로 버전을 관리하기 위해서 -> 먼저 해줘야 할 것
   - git아, 이 디렉토리 이제부터 니가 관리해!
```bash
git init
```
- 디렉토리별로 딱! 한번만 한다.

## git의 3공간
- working directory : 작업공간, 분장실
- staging area : 대기공간, 무대 위
- repository : 변경사항이 기록되는 공간, 사진을 찍고 난 사진 목록

---
## 3공간을 넘나 들기 위해 쓰는 명령어
1. working directory -> staging area
   ```bash
   git add 파일명
   ```
2. staging area -> repository
    ```bash
    git commit -m "버전을 기록하는 이유"
    ```
### 상태와 기록을 확인하기 위한 명령어
- 파일 상태 확인
  ```bash
  git status
  ```
- 버전 기록 확인
  ```bash
  git log --oneline
  ```