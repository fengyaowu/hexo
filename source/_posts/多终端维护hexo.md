---
title: 多终端维护hexo
date: 2016-06-14 10:32:24
tags:
  - hexo
categories: github
---

##  先安装git node.js
到准备存放hexo博客的文件夹下进行git初始化，并与远程repo关联。再安装hexo,hexo-server.
```
  git init
  git remote add origin git@github.com:fengyaowu/hexo.git
  git fetch --all
  git reset --hard origin/master
  hexo g
  npm install hexo --save
  npm install hexo-server --save
  npm install #如果当前路径下存在package.json的依赖的包描述文件，则可以直接执行 npm install 既可以把所有需要的包安装上。
  hexo new test
  hexo g
  hexo s
  hexo d
  git add .
  git status
  git commit -m 'new text'
  git push
  git push --set-upstream origin master
  git pull
```
##  相关链接
  [hexo 同步](http://chitanda.me/2015/06/18/hexo-sync-in-multiple-pc/)
