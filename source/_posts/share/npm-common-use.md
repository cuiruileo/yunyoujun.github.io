---
title: npm 常用工具包
tags:
  - node.js
  - 分享
id: 537
categories:
  - 云游的大安利
date: 2017-10-06 15:56:20
---

NPM是随同NodeJS一起安装的包管理工具，能解决NodeJS代码部署上的很多问题，常见的使用场景有以下几种：
- 允许用户从NPM服务器下载别人编写的第三方包到本地使用。
- 允许用户从NPM服务器下载并安装别人编写的命令行程序到本地使用。
- 允许用户将自己编写的包或命令行程序上传到NPM服务器供别人使用。

摘自：[http://www.runoob.com/nodejs/nodejs-npm.html](http://www.runoob.com/nodejs/nodejs-npm.html)

<!-- more -->
* * *

> nvm

*   简介：可用来安装与管理 `node.js`与 `npm` 版本。(严格来说，并不算npm的工具包，不过是管理 `node.js` 与`npm` 的好工具。)
*   GitHub : https://github.com/creationix/nvm
*   使用方法 ： 参见GitHub主页说明。（推荐使用git方式安装，更新方便。）

    //从github克隆nvm项目代码
    git clone https://github.com/creationix/nvm.git
    //安装稳定版本
    nvm install stable 或者 latest

Windows 系统下，可下载 [nvm-setup.zip](https://github.com/coreybutler/nvm-windows/releases) 解压后使用 exe 文件直接安装即可。

> nrm

*   简介： nrm可以帮助你方便快捷地在不同的 `npm registries` 中切换。(不同npm工具包下载源) 现包括: `npm`, `cnpm`, `taobao`, `nj(nodejitsu)`, `rednpm` .
*   GitHUb : [https://github.com/Pana/nrm](https://github.com/Pana/nrm)
*   使用方法 ： 可参见GitHub主页说明。

> express

*   简介： 基于 `Node.js` 平台，快速、开放、极简的 web 开发框架。
*   GitHub : [https://github.com/expressjs/express](https://github.com/expressjs/express)
*   使用方法 ： 可参见GitHub主页说明。
*   安装方法 ： `npm install express`
*   官网 ： [https://expressjs.com/](https://expressjs.com/)
*   中文网 ： [http://www.expressjs.com.cn/](http://www.expressjs.com.cn/)

* * *

To Be Continued.