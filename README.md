# git push 연습
### Repository 정보등록
- 컴퓨터를 포맷 했을 때 최소 한 번만
- username 등록 : **git config --global user.name hykim6856**
- email 등록 : **git config --global user.email hykim6856@gmail.com**
### 원격 Repository 생성
- **github**에서 **+** 버튼을 통해 **New Repository** 생성
### 로컬 Repository 생성
- **bash shell**에서 **git init** 명령 실행 : .git 폴더 생성
### 로컬 폴더 압축하여 로컬 Repository에 저장
- **git add README.md** 
### 왜 push 하는지 comment 부착하기
- **git commit -m "comment"**
### 원격 Repository 와 로컬 Repository 연결하기
- git remote add origin https://github.com/hykim6856/2023-11-pushpractice.git
### 원격 Repository 에 push하기
- **git push -u origin main** 명령 실행하여 github에 push
- 최초 push이후 **git push**만으로 push가능 