---
layout: post
title: iOS捷径分享
date: 2018-12-18
excerpt: 分享几个自用的捷径
tag: 
- iOS
- 软件
- 手机
- 原创作品
- 编程
---

捷径是一个提供工作流的软件，iOS12主打的新功能，来自于之前收购的[Workflow](http://www.workflow.is/)，并且可以和Siri深度整合。不过并不是系统应用，还需要额外去app store[下载](https://itunes.apple.com/cn/app/%E6%8D%B7%E5%BE%84/id915249334)。

本质上是一个批量操作的脚本，利用一些简单的编程语言可以自己写脚本。苹果官方提供了一些已经写好的捷径，或者可以从网上去找别人分享的捷径。这里提供几个分享捷径的网站：[Shortcuts Gallery](https://shortcuts.sspai.com/)、[捷径社区](https://sharecuts.cn/)、[捷径盒](https://jiejinghe.com/)、[捷径库](http://jiejingapp.cn/)。在这几个网站中基本上可以找到任何你想要的捷径。

不过我一直没怎么想清楚捷径的定位，在网上看了很久别人都是拿捷径来干什么的，思来想去自己也写了六个捷径，在这里分享一下吧。自己写捷径上手还是很容易的，毕竟图形化的编程语言很直观，在看了几个已有的捷径后，很快就能学会了。

---

## [剪贴板](https://www.icloud.com/shortcuts/4bc574ea29e947d7a824e12dd6a92a0f)

用来查看和修改剪贴板的捷径，大概是捷径中最实用的东西了吧，不过运行这个捷径需要打开捷径app。

---

## [付款](https://www.icloud.com/shortcuts/f0ed472210094c7dbad2b8b0fb9f501c)

整合的支付软件入口，主要在widget中用，包含了5个入口：支付宝付款码、支付宝扫码、微信扫一扫、Apple Pay、支付宝乘车码。可以看出支付宝的url scheme开放的比较全，而微信只有扫码功能，并没有付款码。其余的支付软件一般我也用不到了。

---

## [使用Chrome](https://www.icloud.com/shortcuts/06f3879c527046829a2aa1a3522ac48a)

可以获取所选内容或者剪切板内容，如果其中包含链接，则直接用chrome打开链接，否则用chrome打开百度搜索内容。选择文字，然后在共享中使用，主要是chrome自己提供的共享接口竟然不支持用chrome打开链接，这就很蠢了。

---

## [翻译](https://www.icloud.com/shortcuts/9cfe617dc8524379b8d703de4cbcf1ab)

翻译所选内容或剪贴板内容。捷径中有调用microsoft翻译的接口，（竟然不是bing？）可以自动识别语言，当然比有道好用。我还额外做了一个识别被翻译语言语种的步骤，其实挺多余的吧。

---

## [字符统计](https://www.icloud.com/shortcuts/b65f530a1e47474183da0c75d6e67270)

统计所选内容或剪切板内容的字符数。感觉或许是个有用的功能，不过只能统计字符数。

---

## [随机数](https://www.icloud.com/shortcuts/5a39981f3bea4a45954860fd04f027d5)

随机数生成，大概写了几个常用的选项吧：0-1、1-3、1-4、1-6、1-10、1-100、自定义。其中自定义的数如果比1小，那么恒定为0。摇骰子这种事还是很需要的，毕竟选择困难症根本无法做决定啊。