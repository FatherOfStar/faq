# 자주 묻는 질문

Q. 제출 완료 이후에 추가된 Commit 이 존재해요.  
A. 기한을 감안하며 코드를 확인합니다. 기한 이후에 작업된 내용들은 평가 대상이 아닙니다.


### Create, Push

#### …or create a new repository on the command line

```
echo "# Hello World" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kakao-insurance-quiz/hello-world.git
git push -u origin main
```

#### …or push an existing repository from the command line

```
git remote add origin https://github.com/kakao-insurance-quiz/hello-world.git
git branch -M main
git push -u origin main
```


