# www.hongik.ac.kr을 입력하면 무슨 일이 일어날까?!
 - URI : Uniform Resource Identifier (위치를 알아내기 위한 방식) 
 - URL : Uniform Resource Location : 프로토콜(http) +DNS주소
 - URN : Uniform Resource Name

## 서버와 리소스
1. 길고 복잡한 IP 주소들을 외우거나 관리하기 힘들다
2. IP 주소는 사정에 따라 바뀔 수도 있다.


--> DNS서버의 등장 (Domain Name Server)

-Resource의 정체
HTML(자료), CSS(UI),JavaScript(제어)를 재료 삼아 브라우저가 그림을 그려준다.(랜더링)

HTML - 뼈대, CSS-살,옷 


# git의 명령어
- add

  git add는 작업 디렉토리(working directory) 의 변경 내용을 스테이징 영역(staging area)에 추가하기 위해서 사용하는 Git 명령어이다.
  또한 다음 변경(commit)을 기록할 때까지 변경분을 모아놓기 위해서 사용한다.
- commit

  git commit명령어는 파일 및 폴더의 추가/변경 사항들을 저장할 때 사용한다. staging 영역에 쌓인 변화들을 엮어 내어 이름을 지어줄 수 있다. 
- push

  git push명령어는 commit한 내용 (head의 변경내용)을 remote repo(원격 저장소)에 올린다.
  즉 local에서 변경한 내용을 원격 저장소로 업로드한다.
# git pull과 fetch의 차이점

  git fetch는 로컬 저장소에 원격 저장소에서 최신 메타데이터 정보를 확인하라는 명령을 전달한다. 단 fetch는 원격 저장소에 변경사항이 있는지 확인만 하고, 변경된 데이터를 로컬 저장소에 실제로 가져오지는 않는다.
 반면 git pull은 원격 저장소에서 변경된 메타데이터 정보를 확인할 뿐만 아니라 최신 데이터를 복사하여 로컬 저장소에 가져온다.
 즉, fetch는 가져온 변경내용이 로컬에 영향을 미치지 않으며, 병합하기전에 확인하는 용도로 사용하는 것이 좋다.
pull은 가져온 변경내용을 로컬에 병합한다. 하지만 로컬에서 작업하다가 변경된 내용을 pull할 경우 충돌이 일어날 수 있다.


# Branch란?
분기...실체는 - 포인터

- $git branch testing  - testing이라는 이름의 브랜치를 만든다.
- $git checkout testing - head를 testing브랜치로 옮김
- $git branch 현재 만들어 놓은 브랜치를 다 볼 수 있음

# 과제
1. 과제에 올라온 레포지토리를 Fork하여 내 레포지토리에 저장한다. 우측 상단쪽에 Fork를 누르면 된다.
2. Fork한 리포지토리를 git clone 명령어를 이용해 내 컴퓨터에 받는다.
3. local에 나의 깃허브 핸들로 된 브랜치를 만든다.Go to file옆에를 눌러 브랜치를 만들 수 있다.
4. 위 브랜치에서 내 핸들명으로 된 폴더를 하나 만들었다.
5. 폴더 안에 README.md를 만들어 자기 소개를 적었다.
6. 내 깃허브에 저장된 리모트 리포지토리에 새로운 브랜치의 내용을 push 했다.
7. 이 원본 레포지토리에 Pull Request를 보낸다.
- 끝
