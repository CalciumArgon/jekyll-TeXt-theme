---
layout: article
sidebar: 
  nav: side_bar_1
  showPicture: true
# aside:
#   toc: true
# titles:
#   # 设置本篇文章的标题, 但这篇 md 文档可以自己用`#`写标题
#   en      : &EN       Left Side Bar
#   zh-Hans : &ZH_HANS  带左侧边栏
key: page-about
lang: en
---

在 `html` 框架自带标题下直接写的内容

# MD里的一级标题

一级标题下的内容简介
卡片样式的图片展示：

<div class="card">
  <div class="card__image">
    <img class="border rounded" src="ai_meeting.png"/>
  </div>
  <div class="card__content">
    <div class="card__header">
      <p>我是陶瑞（Ray Tao）, 目前就读于上海交通大学 IEEE 试点班-计算机科学与技术方向, 大二本科生.<br>我对分布式系统和网络感兴趣, 但目前还没有相关的项目或科研经验.</p>
    </div>
  </div>
</div>

<a class="button button--outline-info button--rounded button--lg" href="/assets/2023-2024-1.pdf" target="_balnk"><i class="fas fa-download"></i>  我的简历</a>

`我的简历`{:.success}

## MD里二级标题

  二级标题下带缩进的内容

与不缩进内容好像没什么区别

{% highlight ss %}
bundle install
bundle exec jekyll s
{% endhighlight %}

带行号的代码块？

```python
def foo():
  return 42
```