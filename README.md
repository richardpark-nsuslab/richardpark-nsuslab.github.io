# [참고 깃허브](https://github.com/yyyongdev/gitflow-practice)

---

# gitflow-practice
### git flow 흐름을 한번 똑같이 해보자.

## 개발도구
- Window OS, Git, WebStorm
### yyyongdev님의 경우 Mac OS를 사용하고, OpenDiff를 사용하고 계신다. 나는 Mac OS를 사용할 수 없는 환경인데다, OpenDiff를 꼭 써야하는지는 진행 하면서 찾아봐야겠다.

---

### 처음 깃허브 프로젝트를 생성하면 main 브랜치 하나밖에 없다.
```$ git branch -a```
### 웹 스톰에서 위 코드를 입력 해 보겠다.  

```
$ : '$' 용어가 cmdlet, 함수, 스크립트 파일 또는 실행할 수 있는 프로그램 이름으로 인식되지 않습니다. 이름이 정확한지 확인하고 경로가 포함된 경우 경로가 올바른지 검증한 다음 다시 시도하십시오.
위치 줄:1 문자:1
+ $ git branch -a
+ ~
    + CategoryInfo          : ObjectNotFound: ($:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
```

### ??? 이번에는 '$'를 빼고 입력 해 보겠다.

```
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
```
### 뭔가 잘 나온것 같으니 다음 파일을 하나 생성 해 보겠다.

