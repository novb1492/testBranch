# vue-cli

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

git  명령어  

git init  
-현재 위치에 저상송생성 .git(숨긴파일)  

git log/ git log -p  
-깃로그 보여줌 p가 붙으면 바뀐내용보여줌  

git add 파일이름.파일형식  
-스테이지 추가  (커밋직전)  

git commit -m"커밋메세지"  
-commit시도     

git diff/git diff commitid..commitid  
-add전 바뀐사항을 볼수있음 마지막 기회  
add후에 스테이지에 올라가면 안보임   
commtid..commitid가 붙으면 커밋후   
그사이 변경사항이 무엇인지 나타내줌  

git reset commitid --hard  
-commitid까지 commit이 취소됨  
ex)1,2,3,4,5 4선택한다면 4,5 사라짐  
실제 삭제되는게 아님 복구가능  

git branch 브랜치이름  
-브랜치이름으로 브랜치가생김  

git checkout 브랜치이름  
-브랜치이동  
ex)f1,f2 두개중 f2는 branch에 있다면   
checkout master시 f2는 사라지고 안보이게 된다 미쳤다  

vscode가 알아서 해주고 있던것들이였다  
