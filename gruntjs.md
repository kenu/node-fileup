# 개발도구로 JS 삽질 피하기
## JS 개발 도구 후보
* 크롬브라우저
  * JS Debugger
  * Console
* JS Beautifier
* Node inspector
* GruntJS 빌드 도구

## 크롬브라우저
  * JS Debugger
  * Console
### 설치
http://www.google.com/chrome
* IE의 장점
  * 크롬브라우저를 다운받을 수 있습니다.
* 크롬의 미래버전
  * Canary(라고 쓰고 까나리 라고 읽음)
  * https://www.google.com/chrome/browser/canary.html
  * 크롬의 베타기능

### 개발도구 실행
* 요소검사
* F12
* Ctrl+Shift+I (windows, linux)
  * Cmd+Alt+I (Mac)
## JS Beautifier
* http://jsbeautifier.org

## GruntJS 빌드 도구

## Node inspector
* http://okjsp.tistory.com/tag/node-inspector
* npm install -g node-inspector

====
# GruntJS 빌드 도구
http://nodeqa.com/nodejs_ref/66
## 요구사항
* npm
* node.js

## 설치
```
npm install -g grunt-cli
```

```
{
  "name": "my-project-name",
  "version": "0.1.0",
  "devDependencies": {
    "grunt": "~0.4.2",
    "grunt-contrib-jshint": "~0.6.3",
    "grunt-contrib-nodeunit": "~0.2.0",
    "grunt-contrib-uglify": "~0.2.2"
  }
}
```


## 빌드 파일 구조
* The "wrapper" function
* Project and task configuration
* Loading Grunt plugins and tasks
* Custom tasks


## ref

* https://github.com/octoberskyjs/home
* http://jstherightway.org/
* http://www.dofactory.com/javascript-memento-pattern.aspx

