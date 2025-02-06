## Node Practices

#### 01. node 프로젝트 만들기 - (예제: ex01)
1. 자바스크립트 애플리케이션 또는 라이브러리를 개발하기 위해 node(또는 javascript) 프로젝트를 만들고 설정해야 한다.
2. npm(node package manager)를 사용하여 프로젝트를 생성하고 설정할 수 있다.
3. 프로젝트 구조
   - package.json         [프로젝트 페니페스트]
   - package.json.lock    [설치 패키지 의존성 lock]
   - /src                 [개발 소스] 
   - /static              [개발 리소스]
   - /node-modules        [외부모듈(라이브러리 + 개발도구)]
4. node 모듈
   - 코어 모듈: node에서 제공하는 모듈(fs, os, process, http, ...)
   - npm 모듈: npm을 통해서 node_modules에 설치하고 사용하는 모듈    
   - 파일 모듈: 파일 경로로 불러올수 있는 모듈. 보통 자바스크립트 소스 파일이다.

#### 02. package - (예제: ex02)
1. 재사용되는 자바스크립트 모듈은 패키지 형태로 배포되고 설치되고 관리된다. 
2. 보통 패키지는 완전한 어플리케이션(babel, webpack, nodemon, Lint, ...) 또는 라이브러리(ejs, react, axios, express, ...)가 된다.
3. 패키지 설치/삭제 관리를 위해 npm을 사용한다.
4. npm에서는 패키지를 의존성이라는 이름으로 관리하는데 패키지와 같은 의미다.
   - 일반 의존성: 개발 프로젝트의 런타임 때 사용되는 패키지로 꼭 빌드나 배포에 포함되어야 한다.
   - 개발 의존성: 빌드나 배포에 포함되지 않지만 개발에 필요한 애플리케이션이나 라이브러 패키지다.
5. 설치
   - 일반/개발: 일반 또는 개발로 의존성을 구분하여 설치하고 빌드나 배포시 패키지 포함여부를 결정할 수 있다. 
   - 지역/전역: 특정 프로젝트에만 아니면 모든 프로젝트에서 사용하는 패키지를 구분하여 설치 할 수 있다.    

#### 03. Module Programming I: common.js(require) - (예제: ex03)
1. common.js(require) 기반: ES6 이전 JavaScript 자체 Module 지원이 없을 때 시작한 JavaScript Module 지원 프로젝트
2. node 서버 프로그래밍은 전통적으로 require 기반 모듈 기반으로 서버 애플리케이션과 관련 라이브러들이 발전

#### 04. 서버 프로그래밍(JavaScript Backed Web) 맛보기 -  (예제: ex04)
1. 초간단 서버(ex01.js)
2. static 리소스 서버(ex02.js)
