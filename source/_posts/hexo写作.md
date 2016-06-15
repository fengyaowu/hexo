---
title: hexo写作
date: 2016-06-13 13:49:36
tags:
  - hexo
categories: github
---
![](/img/Penguins.jpg)
 ## 新建
 ```
  $ hexo new page tilte #新建页面
  $ hexo new post title #新建文章
  $ hexo new draft title #新建草稿
 ```
 ## 发布
 ```
 $ hexo g #部署之前预先生成静态文件 
 $ hexo s #启动静态服务器
 $ hexo d #部署网站
 ```
 ## 标签
 文章中添加标签
 <!--more-->
 ```
 title: 标签测试文章
 tags:
   - Testing
   - Another Tag
  ---
 ```
 ### 新建标签页面
 ```
 $ hexo new page tags
 ```
 ### 设置页面类型
 ```
 title: 标签
 date: 2014-12-22 12:39:04
 type: "tags"
 ---
 ```
 ### 修改菜单（编辑主题配置文件）
```
menu:
     home: /
     archives: /archives
     tags: /tags
```
 ### 添加图片
 在source文件夹下新建目录img,文章中使用到图片是使用`![](/img/Penguins.jpg)`格式插入。
 
 ## 相关链接
 [hexo 官方文档](https://hexo.io/zh-cn/docs/commands.html)
 [hexo github 搭建](http://kiya.space/2015/11/10/use-Github-Pages-Hexo-duoshuo-to-set-up-a-blog-basic-steps/)
 


