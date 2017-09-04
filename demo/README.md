# Node（从百度开始）
# 网站 TJ 
- [官网](http://nodejs.org/en/)
- [中文官网](http://nodejs.cn/)
- [社区](https://cnodejs.org/)
- node 是从09年开始才有的 
- 深入浅出Node.js (朴灵 著)

# 浏览器
- IE Chrome(V8引擎) 火狐 苹果浏览器 （HTML5 EcmaScript es）
- 浏览器  BOM DOM JS (V8引擎)
- Node JS (V8引擎)  单线程（多线程）
- 前端页面 （js） 服务器(js node)  数据库（js）

# Node 版本

- node以前就有两个版本 0.1       node.io(0.5)
- node 4、6、8(偶数 稳定版本)  5、7、9（奇数 预览版本）
- npm node package manager (node 包管理工具)
- nvm node version manager (node 版本管理工具)

# nvm环境变量 （3n安装方法 nvm npm nrm）

- 在cmd窗口中如果找不到nvm的应用，需要重新修改nvm的环境变量
- 电脑->属性->高级系统设置->高级->环境变量

# nvm使用

- nvm ls 查看有哪些node已经安装了
- nvm install <版本号> 64/32 安装对应的node
- nvm  uninstall  <版本号> 删除包
- nvm use 版本号 切换包

# REPL 可交互环境
- 1. 通过cmd 命令可以直接使用node编写代码，但是这种直接编写不能很方便的保存
- 2. 通过创建js文件，在js文件中编写js代码 然后通过 `node app.js` 运行你的代码

# node工具 加载本地文件 

- `npm install -g http-server`  http-server这个工具用来将你当前的文件，以服务器的方式加载

# node（服务器） 与浏览器不同
- 1. 没有dom bom  window 
- 2. this指向也不再指向window，空对象
- 3. node可以直接读取本地文件


# 上午回顾

- node用来做服务器
- node里面使用的js代码
- node是是应用环境同时也是服务器
- node（v8引擎） 全局对象` global` es6 ecmascript2015 es7 ecmascript2016 es8

# es6 
- [参考阮一峰](http://es6.ruanyifeng.com/)
- let const
- arrow fuction
- 字符串处理
- 遍历
- class