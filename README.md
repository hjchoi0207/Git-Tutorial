# Git-Tutorial

### 1.Git 버전 확인 (cmd창에서 실행)
```
> git --version
git version 2.23.0.windows.5
```   
   
### 2.(config)환경설정 (global)옵션 - 컴퓨터 전체에서 사용할 수 있도록설정
```
>git config --global user.name hjchoi0207
>git config --global user.email @gmail.com
```   
   
### 3. 이후 컴퓨터에서 작업 할 경로로 이동 (cd명령어)

```
>clone [저장소주소]
```
   
### 4. 폴더에 파일(gugudan.py)을 생성한 뒤 변경사항을 반영하기 위해 프로젝트가 존재하는 폴더로(/Git-Tutorial) 이동하였음
```
>git add a.txt
>git commit -m "커밋 메세지"
```   
   
### 5. 마지막으로 원격저장소(깃헙 웹페이지)에 푸시하는 과정
```
>git push
```

<hr/>

예전부터 깃헙 저장소와 내 컴퓨터를 연동하고 싶었지만 git을 설치해서 cmd창에서 git명령어를 인식하지 못했고 번번히 실패했다.
그러나 구글링을 하던 중 git의 환경변수를 설정해 문제를 해결할 수 있었고 처음으로 (IDE를 활용한 것은 제외) 내 데스크탑과 깃을 연동할 수 있었다.   
[환경변수 설정에 도움을 준 블로거님](https://cofs.tistory.com/421)   
[Git 사용법을 알려주신 동빈나님 영상](https://www.youtube.com/watch?v=rhP5pseOJc0)
