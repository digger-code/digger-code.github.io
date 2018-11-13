---
title: hexo 简明使用教程
date: 2018-11-13 13:40:00
tags:
- 帮助文档
categories:
- hexo
- 使用指南
---
# 一. 克隆代码
1. git clone git@github.com:digger-code/digger-code.github.io.git
2. cd ./digger-code, 一定要进入该目录, 后续的操作都是在该目录下执行
3. git checkout blog, blog分支为博文源码, master分支静态网页

# 二. 安装npm, hexo
1. npm install hexo
2. npm install
3. npm install hexo-deployer-git

# 三. 使用
> - 所有博文都在./source/_posts目录下

1. 新建blog
> - hexo new "新建博文的名称"
> - 直接进入博文目录新建文件

2. 编写blog
> - 按照markdown的模式, 编写文件

3. 提交
> - 先将博文源码提交, git push origin blog
> - hexo g, 生成静态网页
> - hexo d, 将生成的静态网页部署到github上

4. 其他问题
> - 通过hexo s, 可以启动一个本地的server, 直接点击可以看到效果

# 四. 注意事项
1. 一定要在blog分支下操作
2. 新建博文时, 最好将头部的categories, tags写完整, 便于后期查找
3. 提交到github之前, 最好先通过hexo s本地查看下效果
