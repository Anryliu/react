# react 脚手架
# 开始开车
## create-react-app 
create-react-app是来自于Facebook出品的零配置命令行工具，能够帮你自动创建基于Webpack+ES6的最简易的React项目模板，有助于初学者快速上手实践。安装create-react-app的方式也非常简单，可以直接使用npm命令进行全局安装。
```shell
npm install -g create-react-app
```
```shell
create-react-app my-app

cd my-app/
npm start
```
执行完上述命令之后，你可以直接打开http://localhost:3000，即可以看到你React APP的运行效果。此时也是处于开发模式下，如果你要进行发布，则使用`npm run build`进行编译。
create-react-app生成的目录格式如下所示:

```shell
my-app/
  README.md
  index.html
  favicon.ico
  node_modules/
  package.json
  src/
    App.css
    App.js
    index.css
    index.js
    logo.svg
    
 ```
使用npm start来启动配置，那么自动会进入开发模式，此时热替换是处于自动激活状态，你也可以实时地在界面或者命令行中看到错误提示.
    
使用npm run build来编译得到生产环境，此时代码会被编译到build目录下，此时会自动将整个应用打包发布，它会自动使用Webpack控件进行优化与压缩.

