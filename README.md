# lzk-cli

cli study

## 学习搭建 cli 脚手架

## 安装

### 全局安装

$ npm install lzk-cli -g

# or yarn

$ yarn global add lzk-cli

### 借助 npx

创建模版
$ npx create lzk-cli <name> [-t|--template]
示例
$ npx create lzk-cli hello-cli -template study-demo

## 使用

创建模版
$ lzk-cli create <name>
示例
$ lzk-cli create hello-cli

## 发布到npm
npm login
npm publish
npm version patch
