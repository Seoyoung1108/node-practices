## 02. 패키지 관리

1. 프로젝트 초기화

```sh

$ mkdir ex02
$ cd ex02
$ npm init -y

```


2. 패키지 설치

```sh

$ npm i ejs           [지역, 일반]
$ npm i -D nodemon    [지역, 개발]
$ npm i -g gulp       [전역, 일반]
$ npx gulp --version

```


3. 패키지 삭제

```sh
   
$ npm un ejs          [지역]
$ npm un nodemon      [지역]
$ npm un -g gulp      [전역]       

```