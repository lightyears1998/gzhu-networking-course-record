---
layout: page
title: About
permalink: {{ "/about/" | escape }}
---

上次尝试用静态博客框架Hexo做了[嵌入式系统与接口技术课程的课程记录](https://lightyears1998.github.io/gzhu-esit-course-record/)，这次就来尝试一下Jekyll吧。

Jekyll没有对Windows平台下的官方支持，所以在Windows平台上使用的体验不是很好。`_posts`的默认后缀名是`.markdown`而不是`.md`耶，Jekyll应该是有一段历史的了。

另外，默认的语法高亮格式用{% templatetag openblock %} highlight lang {% templatetag closeblock %}和{% templatetag openblock %} endhighlight {% templatetag closeblock %}作为定界符，跟现在的流行格式也有很大不同。

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

GitHub Pages对Jekyll的集成非常好，构建速度飞快。

先上车看看吧。
