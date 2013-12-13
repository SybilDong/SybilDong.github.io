---
layout: blog-post
title: "Jekyll之道，Geek之道"
description: ""
category: blog
tags: [jekyll, geek]
---
{% include JB/setup %}

## 自由的Jekyll
---
初见Jekyll时它是和Github Pages在一起的，从一开始它在我耳畔就萦绕起geek的声音三日不绝。江南三月，杨柳依依，春风拂面，Jekyll就此婀娜行来~

嗯，好好说话。Geek之道，在于热于探索，追求自由，Jekyll主要技术如[YAML][]、[MarkDown][]、[Liquid][]都不属烂大街的东西，门槛有但都简单，在这个世界里你可以主宰所有，导航来个固定布局，主区域左右分栏，哦footer还要卖个萌，内容无论是以多媒体还是以文字为主，如[本站][1]的阅读或博客分类，Jekyll毫无压力。

## 自由的味道是什么？
---
* **久旱逢甘霖** - 简洁的[MarkDown][]语法

    [MarkDown][]的设定从最一开始就是适用于Web写作的工具，提供简洁的语法以便转换为HTML。
    
    传统的HTML方式，把正文与tag混杂到一块，为了突出显示粗体不得不相开始和结束一个strong标签`<strong></strong>`，更别论引用、代码高亮之类了。Docbook虽然标准，仍属XML系统，摆脱不了编写过于繁琐的劣势。

* **他乡遇故知** - 文本载体，易于版本控制

    动态语言一般都会选择数据库来保存内容，相信CSDN、JavaEye等博客内容都是如此处理的，即使能够导出估计最后导出的格式也是百花怒放之象。

    Jekyll则是通过post生成静态的HTML以供部署，原始内容是以html或[MarkDown][]组织的正文，特别适合纳入版本控制特别是Git这种分布式的版本控制体系，尽情享用！

* **洞房花烛夜** - 编辑器之殇

    想想在号称所见即所得的Web上编写博客的场景吧，不能tab，设计个列表需要在工具栏上找啊找，你想做个链接，哦，他想加个图片，这些都不是灾难性的，当你点击发布或者保存草稿时,Oh Shit! 网络异常？服务器错误？这时，你肯定会有一种欲哭无泪的绝望，可惜无能为力。

    再想象一下用你最得心应手的编辑器来写博客，你可以使用由此带来的所有特性。使用vi我可以毫不费力地处理去除粘贴过来代码多余的前置空白，可以使用宏，多么美好的一天啊~

* **金榜提名时** - Github

    毫无疑问的压轴大戏。对我这种超轻度博客作者来讲，免费再加上Github这几个字母就足够了。你可以选择把site部署到其他服务器上，所以其实Github也不算是必选项。

    然后，你可以用到之前提及的所有特性来建立你的项目主页、分享你的知识，并部署到各种http容器中，纯静态的内容从性能上来讲也拉开那些动态内容几条街，唯一的缺点是静态内容是基于你的post、page在部署前生成的，所以比较适合个人和中小企业。

## 入门指南
---
* [Jekyll Github Wiki](https://github.com/mojombo/jekyll/wiki)
* [The Quickest Way to Blog on GitHub Pages](http://jekyllbootstrap.com/)
* [Markdown语法说明][MarkDown]
* [MaHua 在线Markdown编辑器](http://mahua.jser.me/)
* [搭建一个免费的，无限流量的Blog----github Pages和Jekyll入门](http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html)
* [Google "Jekyll" 更多...](https://www.google.com.hk/search?q=Jekyll&aq=f&oq=jekyll&aqs=chrome.0.59j65j61j65l2j60.1630&sourceid=chrome&ie=UTF-8)

[YAML]: http://www.yaml.org/
[MarkDown]: http://wowubuntu.com/markdown/
[Liquid]: http://www.liquidmarkup.org/
[1]: http://hqingyi.github.io "青衣秀士的博客"
