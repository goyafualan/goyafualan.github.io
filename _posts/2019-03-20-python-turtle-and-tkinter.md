---
title: 在Python中体验Turtle和Tkinter
layout: post
category: [技术, Python]
---

在这个学期开始，我们上信息课的时候，我们的信息老师（技术一般，英文很菜）带我们体验了Python + Turtle，非常简单，不过我只是算在机房的电脑上写过Python的代码。

今天，我安装好了[Python](https://www.python.org/)，多亏有了在信息教室使用Python的经验，我终于搞明白Python的代码该怎么运行了:)有点可笑。
上午的时候看到了Tkinter，非常方便使用；刚才又惊奇的发现信息课上使用的Turtle居然也是Python里自带的，于是完成了在信息课没有完成的 ```y = x²```
```python
from turtle import *

gr    = Turtle()
gr2   = Turtle()
num   = 150           #设定以num像素为1单位；也就是精确到1/num

gr.speed("fastest")
gr2.speed("fastest")

for x in range(2 * num):         #画出3个单位
    y = ( x * x ) / num          #计算函数值
    gr.goto(x, y)                #绘图
    y = ( x * x ) / num
    gr2.goto(-x, y)
```

运行结果：

![Python Turtle](/files/img/python-turtle-1.png)
未完待续