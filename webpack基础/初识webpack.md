### webpack是什么？
- webpack是一个模块打包工具，能够识别许多模块引入的方式
- eg. ES Moudule,CommonnJS,CMD,AMD
- 不单单可以打包JS模块
### webpack安装
- 全局安装(不推荐)
  - npm install webpack webpack-cli -g
  - 全局安装使得不同项目中不能使用不同版本的webpack
- 局部安装(推荐)
  - npm install webpack webpack-cli --save-dev
  - npm install webpack webpack-cli -D(简写)
  - 局部安装的时候不能直接运行webpack命令,可以通过npx webpack运行 webpack命令, npx可以找到目录下的webpack。
- 安装指定版本的webpack
  - npm install webpack@版本号
- 查看webpack的历史版本
  - npm info webpack

