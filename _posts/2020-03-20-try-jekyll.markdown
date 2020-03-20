---
layout: post
title:  "尝试一下Jekyll"
date:   2020-03-20 08:30:00 +0800
categories: jekyll update
---

上次尝试用静态博客框架Hexo做了[嵌入式系统与接口技术课程的课程记录](https://lightyears1998.github.io/gzhu-esit-course-record/)，现在就来尝试一下Jekyll吧。

Jekyll没有对Windows平台下的官方支持，所以在Windows平台上使用的体验不是很好。`_posts`的默认后缀名是`.markdown`而不是`.md`耶，Jekyll应该是有一段历史的了。

另外，默认的语法高亮格式跟现在的流行格式也有很大不同。

``` ruby
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}
```

先上车看看吧。
