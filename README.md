# To Do List

* https://chrome.google.com/webstore/detail/momentum/laookkfknpbbblfpciffpaejjkokdgca?hl=ko

* Momentum application의 일부 기능을 구현했습니다

## 프로젝트 구조

![file tree](https://raw.githubusercontent.com/insight88/microapp-todo-vanillajs/master/images/project%20file%20tree.jpg)

* index.html, index.css로 구성된 single page app
* images 폴더에서 랜덤 이미지를 배경화면으로 설정하는 bg.js
* 현재 시간을 실시간으로 보여주는 clock.js
* 사용자가 처음 app을 사용할 때 이름을 입력받아 메세지를 출력하는 gretting.js
* 오늘 할 일을 입력받아 list로 출력하는 todo.js
* openweathermap.com API를 이용하여 사용자의 현재 위치 정보를 받고 날씨를 표시하는 weather.js

## 프로젝트 설명

![screenshot#1](https://github.com/insight88/microapp-todo-vanillajs/blob/master/images/screenshot%201.jpg?raw=true)
* 사용자의 위치 정보와 사용자 이름을 입력 받는다

![screenshot#2](https://github.com/insight88/microapp-todo-vanillajs/blob/master/images/screenshot%202.jpg?raw=true)
* 사용자 이름과 날씨 정보를 출력한다

![screenshot#1](https://github.com/insight88/microapp-todo-vanillajs/blob/master/images/screenshot%203.jpg?raw=true)
* To Do List를 입력받아 List 형태로 출력한다
* trash icon을 클릭하면 해당 항목이 List에서 삭제된다

**사용자의 name, todos 정보는 localStorage에 저장된다**

## 사용한 기술

* 기초 HTML/CSS
* 기초 Vanilla JavaScript

## 배포

[github.io](https://insight88.github.io/microapp-todo-vanillajs/)

## 기타 정보

### 제작 이유

* Nomad Coder 바닐라JS 2주 완성반 Challenge Course 최종 작업물
* Challenge Course Repository : https://github.com/insight88/challengecourse-2week.js-vanillajs

### 제작 기간

* 2020.04.20 ~ 2020.05.03

### 제작자

* 김기표