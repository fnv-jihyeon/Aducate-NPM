# Aducate-NPM
npm에 대한 학습, Webpack 사전 학습


## NPM(Node Package Manager) 이란?
 - [공식 페이지](https://www.npmjs.com/)
 - JS 라이브러리 관리 도구

## 라이브러리 패키지를 사용하는 이유 
1. 라이브러리 관리의 유연함이 있다
 
   - src/package.json에 정리되어 있다, 버전업을 할 경우에도 바로 적용되어 진다.

   - dependencies, devDependencies 구문 아래에 설치된 라이브러리 명과 버전이 표시된다. 

3. 스크립트로 직접 라이브러리를 CDN으로 설치할 필요가 없다.
  
   - node-module폴더안에 로컬로 설치되고 이것을 package.json을 통해 불러와서 사용한다.

```
{
  "name": "npm",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "description": "",
  "dependencies": {
    "jquery": "^3.7.1"
  },
  "devDependencies": {
    "vue": "^3.5.1"
  }
}

```
## 명령어
1. 초기화 명령어

```
npm init
```
   - package.json을 직접 설정 할 수 있음
```
npm init -y
```
   - package.json 기본값을 설정해서 생성한다.
     
3. 설치 명령어
4. 제거 명령어
5. 전역 설치 명령어
