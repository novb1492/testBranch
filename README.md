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

<<<<<<< HEAD
=======
깃 브랜치 테스트를 위해 만듬  
브랜치임  

>>>>>>> exp
git  명령어  

git init  
-현재 위치에 저상송생성 .git(숨긴파일)  

git log/-p/ --branches --deconrate --graph  (--oneline)  
-깃로그 보여줌 p가 붙으면 바뀐내용보여줌  
브랜치별로 이름이붙어서 보임  

git add 파일이름.파일형식  
-스테이지 추가  (커밋직전)  

git commit -m"커밋메세지"  
-commit시도     

git diff/git diff commitid..commitid or branch..branch  
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

git merge 브랜치이름  
-브랜치=>master로 병합  

git branch -d 브랜치이름  
-해당 브랜치 삭제  

<<<<<<< HEAD
vscode가 알아서 해주고 있던것들이였다  

=======
vscode가 알아서 해주고 있던것들이였다   

fast-foword  
-별도의 커밋이 생성되지 않음  
>>>>>>> exp

병합완료  겁나신기하다  

git stash save  
-예를들어 master/branch가 공유중에 checkout을 master로 넘어가서  
작업해야하는데 master가 영향을 받을때  사용  (감추기)  

git stash apply  
-감춘 파일 부활 명시적 삭제가 아닌이난 이명령어로 부활가능  

git stash list  
-감춘 파일 리스트  

git stash drop  
-숨긴파일삭제  

git stash pop  
-apply+list  2
