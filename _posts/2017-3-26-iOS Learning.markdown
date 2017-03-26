---
layout: post
title:  "iOS学习-Cocoa Touch 框架"
subtitle: "Cocoa Animation 让你的APP动起来"
date:   2017-03-26 21:10:45
categories: [tool]
---


# Cocoa Tounch 中最常用的框架

常用框架一览：
- Core Animation 框架 (核心动画框架)
- Core Audio 框架 （核心音频框架）
- Core Data 框架 （核心数据框架）.

> 以上就是 Cocoa Tounch 框架中常用框架，可以说他们是一个APP中的三大支柱。

————————

## Core Aimation 框架

通过 Core Animation 我们可以实现一些酷炫的动画效果，提升用户的使用体验。


Example code:

{% highlight javascript %}
var light = new Light();
var switchUp = new FlipUpCommand(light);
var switchDown = new FlipDownCommand(light);
var s = new Switch();

s.storeAndExecute(switchUp);
s.storeAndExecute(switchDown);
{% endhighlight %}



Want to suggest something? Please [Send me a request](https://github.com/kronik3r/daktilo/issues/new).
