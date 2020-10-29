[과제] Typing Game (타자게임)
이건희 2020-10-29
****
# 설치 install npm modules
```$xslt
npm install
```

# 작동 start dev-server
```$xslt
npm run start
```

# 빌드 webpack build production mode
```$xslt
npm run build
``` 

# 테스트 jest test
```$xslt
npm run test
``` 

****
# 개발환경
* 빌드: webpack
* 개발언어: Typescript
* 테스팅 라이브러리: jest
```c
  "dependencies": {
    "babel-loader": "^8.0.6",
    "extract-text-webpack-plugin": "^3.0.2",
    "mini-css-extract-plugin": "^0.4.3",
    "html-webpack-plugin": "^3.2.0",
    "source-map-loader": "^0.2.4",
    "ts-loader": "^6.0.1",
    "typescript": "^3.4.5",
    "webpack": "^4.32.2",
    "webpack-cli": "^3.3.2",
    "webpack-dev-server": "^3.4.1",
    "webpack-merge": "^4.2.1",
    "whatwg-fetch": "^3.0.0"
  },
  "devDependencies": {
    "@babel/cli": "^7.4.4",
    "@babel/core": "^7.4.5",
    "@babel/plugin-proposal-class-properties": "^7.4.4",
    "@babel/plugin-proposal-object-rest-spread": "^7.4.4",
    "@babel/polyfill": "^7.4.4",
    "@babel/preset-env": "^7.4.5",
    "@babel/preset-typescript": "^7.3.3",
    "@types/jest": "^26.0.15",
    "babel-jest": "^26.6.1",
    "css-loader": "^1.0.1",
    "jest": "^26.6.1",
    "style-loader": "^2.0.0",
    "ts-jest": "^26.4.2"
  }
```
## Directory Architecture (디렉토리 구조 설명)
``` bash
# build(webpack)
base - 개발 공통 스펙 정의
dev - 개발 환경 로컬 서버 구동
build - 개발코드 빌드 실행
```

