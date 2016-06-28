---
layout: page
title: 小明的 - BLOG
tagline: 做事只有三分钟热度的小明。。。
---
{% include JB/setup %}
## Under Construction...

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

时间太短，只争朝夕。

快速启动[Jekyll ](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

完全使用手册: [Jekyll Bootstrap](http://jekyllbootstrap.com)

### 一些有用的网站链接

[http://jekyll.bootcss.com/docs/github-pages/](http://jekyll.bootcss.com/docs/github-pages/a)

[http://www.tuicool.com/articles/Yr6RjuJ](http://www.tuicool.com/articles/Yr6RjuJ)

[http://www.thomaszhao.cn/2015/01/08/how-do-i-build-this-jekyll-blog/](http://www.thomaszhao.cn/2015/01/08/how-do-i-build-this-jekyll-blog/)



