# ve

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


실행방법

node설치(16.0.0 버전 사용했음), git 설치, visual studio code 설치

1번 방법.

vue add vuetify /
vue add electron-builder /
yarn electron serve
순서로 실행

(yarn 명령어를 터미널에 실행시키면 필요한 파일 모두 설치가 된다던데
내가 했을때는 에러가 많이나서 다시 새로 설치하고 1번방법으로 했음)


2번 방법.

powershell 실행 /
원하는 파일 위치로 이동 /
vue create ve 실행/
history 부분만 no로 하고 파일 생성/
이후 1번방법 실행


에러 해결방법.

vuetify 이름으로 트집잡을때 eslintrc.js 들어가서
rule에
'vue/multi-word-component-names': 0
복붙

노드 버전 오류는 명령프롬프트에 nvm 으로 해결
구글링하면 nvm사용법 나옴

https://www.youtube.com/watch?v=jafdNfriWpU&list=PLjpTKic1SLZutycpZRs6qS5L_CZ3f2ON1&index=1 보고 했음


