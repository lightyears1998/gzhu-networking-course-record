---
layout: page
title:  "关于"
permalink: /about/
---

这里的文章是{{ site.description }}

做网站的初衷是希望能将自己的经验分享给更多人。另外，上次尝试用静态博客框架Hexo做了[嵌入式系统与接口技术课程的课程记录](https://lightyears1998.github.io/gzhu-esit-course-record/)，这次就想来尝试一下Jekyll。

Jekyll没有对Windows平台下的官方支持，所以在Windows平台上使用的体验不是很好。`_posts`的默认后缀名是`.markdown`而不是`.md`耶，Jekyll应该是有一段历史的了。

另外，除了Markdown里面默认的标记代码段的格式，语法高亮也可以使用Liquid tag。

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

GitHub Pages对Jekyll的集成非常好，构建速度飞快。

先上车看看吧。
