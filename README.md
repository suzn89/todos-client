# todos-client
vue.js todo 예제 실습


## npm을 이용할때 vue-cli 설치
```
npm install vue-cli -g
```

## Webpack 템플릿을 이용한 템플릿 생성
```
vue init webpack todos-client

생성 중 옵션 선택
? Project name (todos-client)
? Project name todos-client
? Project description (A Vue.js project)
? Project description A Vue.js project
? Author (suzn89 <ssostory@gmail.com>)
? Author suzn89 <ssostory@gmail.com>
? Vue build (Use arrow keys)
? Vue build standalone
? Install vue-router? (Y/n)
? Install vue-router? Yes
? Use ESLint to lint your code? (Y/n) n
? Use ESLint to lint your code? No
? Set up unit tests (Y/n) n
? Set up unit tests No
? Setup e2e tests with Nightwatch? (Y/n) n
? Setup e2e tests with Nightwatch? No
? Should we run `npm install` for you after the project has been created? (recom
? Should we run `npm install` for you after the project has been created? (recom
mended) npm

```

## 로컬 서버로 확인
```
To get started:
     cd todo-client
     npm install
     npm run dev
```

## src폴더
### 구조
```
src
├── assets
│   └── logo.png
├── components
│   └── HelloWorld.vue
├── router
│   └── index.js
├── App.vue
└── main.js
```

#### assets
외부에서 가지고온 css,js,이미지나 파일 등을 넣는 폴더

#### components
Vue.js에서 사용하는 확장명 `.vue` 파일을 생성,구현 하는 폴더

#### router/index.js
라우팅을 할 수 있도록 도와줌.
페이지를 서버에 요청하지 않아도 새로운 페이지로 이동가능

#### App.vue
프로젝트가 다루는 컴포넌트가 표시되는 Root 컴포넌트

#### main.js
프로젝트의 Base 파일, 전역 설정을 하려면 main.js를 수정




