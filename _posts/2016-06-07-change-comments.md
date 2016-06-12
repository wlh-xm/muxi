---
layout: post
title: "更改评论系统为“多说”"
description: "dicus--->duoshuo"
category:  
tags: []
---
{% include JB/setup %}

**参考其他文章得到如下步骤：**


1. 注册多说账号，得到一个short_name。

2. 获得一段js代码，保存在_includes/JB/comments-providers下，并修改相关内容，注意确保short_name为注册时得到的。

3. 更改_config.yml文件中相应的位置。



4. 博客文章名为中文时，github报警称未utf8编码，根据它提供的连接，需在_config.yml中添加encoding:UTF-8语句。试了下，不管用啊，还是改回字母，不用中文名了。。。
