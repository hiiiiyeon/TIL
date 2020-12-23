# Github 특강 - Basic

## git 이란?

## git 설치

1. git-scm.com 에서 다운로드
2. 계속 next로 설치

## git 사용법

### 최초 설정

처음 컴퓨터에 git을 설치하면 사용자의 이메일과 이름을 적어준다. 이는 앞으로 일어나는 커밋에 서명을 하기 위해서 필요하다.

```
$git config --global user.name "<당신의 이름>"

$git config --golbal user. email ''<당신의>@<이메일>"
```

잘 설정되었나 확인하려면

```
$git config. user. name
이름 출력

$git config user.name
이메일 출력
```



### 초기화

초기화는 `git init`을 통해 진행한다. 

```
$ git init
```



### add하기

```
$ git add . 
```



### commit 하기

```
$ git commit -m '<message>'
```



### Log보기

```
$ git log
(나갈때 q)
```



### 원격저장소 등록하기

```
$ git remote add origin <URL> # 원격 저장소 등록하기

$ git remote -v # 원격 저장소 확인하기
origin <URL>... # origin remote 저장소의 이음

$ git remote rm <remote_repo_name>

$ git remote -V # 없어진것 확인
```



### 원격 저장소에 push 하기

```
$ git push origin master # remote 이용이 origin일 경우
```



## Summary

| 명령어                              | 설명                                                |
| ----------------------------------- | --------------------------------------------------- |
| `$ git init`                        | 반 디렉토리(폴더)를 git 저장소(repo)로 초기화 한다. |
| `$ git add <filename>`              | < filename>을 stage에 올린다.                       |
| `$ git commit -m < commit massage>` |                                                     |
|                                     |                                                     |



