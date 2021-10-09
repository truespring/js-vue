# Vue.js

## 프론트엔드를 이해하기 위한 Vue.js 학습하기


## Vuejs 더 잘다루기

Vue 를 더 잘다루기 위해서 필요한 환경이 존재한다.

### component 사용

> 컴포넌트는 일반 브라우저에 동작하지 않는다. CORS 정책 때문이다. 컴포넌트를 다루기 위해서는 HTTP 서버가 필요하다.

1. Node.js 설치
``` shall
$ brew install node
```
2. http-server 설치
``` shall
$ npm install http-server -g
```
3. 코드가 위치한 폴더에서 서버 실행
``` shall
// localhost 3000 포트에서 실행
$ http-server -p 3000
```
4. 브라우저에서 localhost:3000 실행