---
title: 该写点什么了
layout: post
category: [技术, 杂七杂八]
---

~~快一个月~~，并不是，上次的文章写完之后忘记了更改日期，以至于前两次的文章有一样的日期。今天到家之后，我总觉得该写点什么了。

先从前两天折腾python开始吧。既然python这么容易使用，我想把.py编译为.exe，于是我上网寻找方法。相关的文章全部都是使用PyInstaller来编译的。我开始尝试着安装PyInstaller
安装PyInstaller最简单的方法就是：

直接在命令行用pip安装 pyinstaller
```pip install pyinstaller```

我打开cmd，输入了以上代码，得到了以下的输出。
```
'pip' 不是内部或外部命令，也不是可运行的程序
或批处理文件。
```
于是我历经千辛万苦在Python的安装目录中寻找pip.exe，而最后我找到了，它在