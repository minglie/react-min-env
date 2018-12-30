# react-min-env
react最小环境

新建package.json文件内容如下

{
  "name": "hello-world",
  "version": "0.1.0",
  "private": true,
  "devDependencies": {
    "react-scripts": "0.8.4"
  },
  "dependencies": {
    "react": "^15.4.1",
    "react-dom": "^15.4.1"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test --env=jsdom",
    "eject": "react-scripts eject"
  }
}


src添加

App.js
App.css
index.js

public下添加

index.html


主要全靠
react-scripts
eject可把webpack配置文件显示处理