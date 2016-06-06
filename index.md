---
layout: page
title: 小明的 - blog
tagline: 小明从小伴随我们成长。。。
---
{% include JB/setup %}
## 博客还在建设中。。。
快速启动[Jekyll ](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

完全使用手册: [Jekyll Bootstrap](http://jekyllbootstrap.com)


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

### 一些有用的网站链接

http://jekyll.bootcss.com/docs/github-pages/
http://www.tuicool.com/articles/Yr6RjuJ
http://www.thomaszhao.cn/2015/01/08/how-do-i-build-this-jekyll-blog/

### To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


