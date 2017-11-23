# vayne-plugin-angularjs
vayne angularjs 插件

## Installation
```
yarn add vayne-plugin-angularjs -D
npm i vayne-plugin-angularjs -D
```
## Usage
在__.vaynerc.js__ 引入
```js
module.exports = {
  plugins: [
    'vayne-plugin-angularjs' // 或者简写 angularjs
  ]
}
```

## include
* __html-loader__ ^0.5.1
* __ng-annotate-loader__ ^0.6.1
* __ng-annotate-patched__ ^1.6.0
* __ngtemplate-loader__ ^2.0.1