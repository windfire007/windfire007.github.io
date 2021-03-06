---
layout: post
title: iOS快捷指令分享
date: 2018-12-18
excerpt: 分享几个自用的快捷指令
tag: 
- iOS
- 软件
- 手机
- 原创作品
- 编程
---

快捷指令是一个提供工作流的软件，已经成为iOS13内置应用，来自于之前收购的[Workflow](http://www.workflow.is/)，并且可以和Siri深度整合。

本质上快捷指令是一个批量操作的脚本，利用一些简单的编程语言可以很方便的自己制作脚本。苹果官方提供了一些常用的快捷指令，或者可以从网上去找别人分享的快捷指令。这里提供几个分享快捷指令的网站：[Shortcuts Gallery](https://shortcuts.sspai.com/)、[捷径社区](https://sharecuts.cn/)、[捷径盒](https://jiejinghe.com/)、[捷径库](http://jiejingapp.cn/)，在这几个网站中基本上可以找到任何你想要的快捷指令。

自己写快捷指令还是很容易上手的，毕竟图形化的编程语言十分直观，在参考几个已有的快捷指令后，很快就能学会了。目前第三方应用对快捷指令的支持并不算多，很多还是需要利用URL Scheme进行调用，而URL Scheme又十分有限，希望未来能有更多的第三方应用直接支持快捷指令吧。

不过我一直没怎么想清楚快捷指令的定位，在网上查了很久别人都是怎么用快捷指令的，思来想去自己也写了六个快捷指令，在这里分享一下吧。

注：想要添加第三方快捷指令需要打开`设置-快捷指令-允许不受信任的快捷指令`。

---

## [剪贴板](https://www.icloud.com/shortcuts/30a0a48e9ea447e4b182473f2afd1a7e)

用来查看和修改剪贴板内容，大概是快捷指令中最实用的东西了吧，不过运行这个快捷指令会自动打开快捷指令app。

---

## [付款](https://www.icloud.com/shortcuts/692877ef7e5648cebf460a11b6d960ad)

整合的支付软件入口，主要在widget中使用，共包含了5个入口：支付宝付款码、支付宝扫码、微信扫一扫、Apple Pay、支付宝乘车码。可以看出支付宝的URL Scheme开放得比较全面，而微信只有扫码功能，并没有付款码。其余的支付软件一般我也用不到了。

---

## [使用Chrome](https://www.icloud.com/shortcuts/9bb943ecc54f4851931d343f15775ddd)

获取所选内容或剪贴板内容，如果其中包含链接，则直接用Chrome打开链接，否则用Chrome打开百度并搜索内容。可以选择文字，然后在共享中使用，主要是Chrome提供的共享接口竟然不支持用Chrome打开链接，这就很蠢了。

---

## [翻译](https://www.icloud.com/shortcuts/0e4785bbd59546a1a59825ba5b361117)

翻译所选内容或剪贴板内容至简体中文。快捷指令中有调用Microsoft翻译（竟然不是Bing？）的接口，可以自动识别语种，当然比有道好用。我还额外做了一个识别被翻译语言语种的步骤，其实挺多余的吧。

---

## [字符统计](https://www.icloud.com/shortcuts/a92009ed8d374d18ac94c539e4fe99ea)

统计所选内容或剪贴板内容的字符数。感觉或许是个有用的功能，不过只能统计字符数。

---

## [随机数](https://www.icloud.com/shortcuts/91a3125cee744d5d9573d9699e25c783)

生成随机数，大概写了几个常用的选项：0-1、1-3、1-4、1-6、1-10、1-100、自定义。其中自定义的数如果小于1，那么结果恒为0。摇骰子这种事还是很需要的，毕竟选择困难症根本无法做决定啊。