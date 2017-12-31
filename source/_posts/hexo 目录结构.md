---
title: hexo 目录结构
date: 2017-12-31 11:15:31
tags:
- hexo
- tree
categories: Study-hexo
---
```
.
├── layout             #布局，根目录下的*.ejs文件是对主页，分页，存档等的控制
|   ├── _partial       #局部的布局，此目录下的*.ejs是对头尾等局部的控制
|   └── _widget        #小挂件的布局，页面侧边栏的控制
|   └── *.ejs
├── source             #源码
|   ├── css            #css源码
|   |   ├── _partial   #*.styl局部css 
|   |   ├── _util      #*.styl基础css
|   |   ├── fonts      #字体
|   |   ├── images     #图片，banner.jpg是header的背景图
|   |   |   ├── banner.jpg
|   |   └── style.styl #*.styl引入需要的css源码
|   ├── fancybox       #fancybox效果源码
|   └── js             #javascript源代码
├── _config.yml        #主题配置文件
└── README.md          #用GitHub的都知道
```

```
.deploy：执行hexo deploy命令部署到GitHub上的内容目录
public：执行hexo generate命令，输出的静态网页内容目录
scaffolds：layout模板文件目录，其中的md文件可以添加编辑
scripts：扩展脚本目录，这里可以自定义一些javascript脚本
source：文章源码目录，该目录下的markdown和html文件均会被hexo处理。该页面对应repo的根目录，404文件、favicon.ico文件，CNAME文件等都应该放这里，该目录下可新建页面目录。
_drafts：草稿文章
_posts：发布文章
themes：主题文件目录
_config.yml：全局配置文件，大多数的设置都在这里
package.json：应用程序数据，指明hexo的版本等信息，类似于一般软件中的关于按钮
```
