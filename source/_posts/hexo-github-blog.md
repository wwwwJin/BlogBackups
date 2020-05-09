---
layout: post
title: "使用hexo搭建github博客"
date: 2020-05-08 22:10:55
comments: false
tags: 
	- hexo
---


#### 一 、环境 ####

>安装git 和 node.js

#### 二 、GitHub ####

> #### 1. 创建一个新的仓库,仓库名格式：账户名.github.io ####
![Alt text](/assets/img/setting_blog_github.PNG)

> #### 2. 进入仓库Settings页面,找到GitHub Pages部分，来源选择主分支，随便选个主题 ####
![Alt text](/assets/img/setting_blog_github2.PNG)

#### 三 、hexo ####
>1. 安装脚手架 `$ npm install -g hexo-cli`
>2. 初始化项目 `$ hexo init`
>3. 添加插件 `$ npm install hexo-deployer-git --save`
>4. 在_config.yml 中配置github
![Alt text](/assets/img/setting_blog_hexo.PNG)
>5. 本地运行项目 `$ hexo s`
>6. 发布项目 `$ hexo deploy`