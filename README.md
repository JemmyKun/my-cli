# my-cli
cli study 
# 学习搭建 cli 脚手架

## 安装

### 全局安装

$ npm install -g my-cli

# or yarn

$ yarn global add my-cli

### 借助 npx

创建模版
$ npx create my-cli <name> [-t|--template]
示例
$ npx create my-cli hello-cli -template study-demo

## 使用

创建模版
$ my-cli create <name> [-t|--template]
示例
$ my-cli create hello-cli -t study-demo
