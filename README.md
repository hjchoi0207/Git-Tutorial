# Git-Tutorial

## 1.Git 버전 확인
```
> git --version
git version 2.23.0.windows.5
```

## 2.(config)환경설정 (global)옵션 - 컴퓨터 전체에서 사용할 수 있도록설정
```
>git config --global user.name hjchoi0207
>git config --global user.email @gmail.com
```

3. 이후 컴퓨터에서 작업 할 경로로 이동 (cd명령어)

```
>clone [저장소주소]
```

파일생성 - 변경사항을 반영 - 프로젝트가 존재하는 폴더로(/Git-Tutorial) 이동 - 
```
>git add a.txt
>git commit -m "커밋 메세지"
```

이후 원격저장소(깃헙 웹페이지)에 푸시하는 과정
```
>git push
```
