---
layout:     post                    # 使用的布局（不需要改）
title:      引用Gitalk评论插件           # 标题 
subtitle:   Hello Issues, Hello Gitalk！ #副标题
date:       2020-03-14              # 时间
author:     BY jiubao98                     # 作者
header-img: img/post-bg-coffee.jpg    #这篇文章标题背景图片
catalog: true                       # 是否归档
tags:                               #标签
    - blog经验
---

## 为博客快速集成评论功能

> 引用Gitalk评论插件📑

&emsp;参考了🖥[插入gitalk教程](https://blog.csdn.net/weiwosuoai/article/details/90573929)   
&emsp;只需更改**_config.yml**里面的参数，gitalk的主要参数**clientID**和**clientSecret**等等。
 
       
		clientID: `Github Application clientID`,
		clientSecret: `Github Application clientSecret`,
		repo: `存储你评论 issue 的 Github 仓库名`,
		owner: 'Github 用户名',
		admin: ['Github 用户名'],
		id: '页面的唯一标识，gitalk会根据这个标识自动创建的issue的标签',
	   




