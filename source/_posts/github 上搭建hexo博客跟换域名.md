---
title: github 上搭建hexo博客跟换域名
tags:
  - hexo
categories: github
---
# github 上搭建hexo博客更换域名
博客主页网址默认问username.github.io,下面记录跟换域名的过程。
# 购买域名
便宜的4块钱第一年。
[新网网址](http://www.xinnet.com/)
# 域名解析
192.30.252.153 和192.30.252.154 就是github 的外网ip地址，当在浏览其中第一次输入www.fengyaowu.pw后，会向f1g1ns1.dnspod.net.进行dns查询。从这里返回github ip地址。
<!--more-->
![](/img/xinwang.png)

# github 添加CNAME
 在自己本地的hexo目录下的source文件夹中，新建一个CNAME文件（注意，没有后缀名。），内容为www.fengyaowu.pw。重新上传自己的博客。浏览器中输入新配置的网址进行访问看是否成功。（可能需要几分钟）
# 更详细内容
[史上最详细的Hexo博客搭建图文教程](https://xuanwo.org/2015/03/26/hexo-intor/)
