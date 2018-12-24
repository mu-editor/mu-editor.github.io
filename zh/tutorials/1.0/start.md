---
layout: zh
title: Start Here! 
i18n: zh
---

# 从这里开始! 

**欢迎使用 Mu！**

Mu是一个为初学者程序员打造的Python代码编辑器。
这意味着当你学习用 Python 编写代码时，Mu 可以很容易地创建、运行和修改你的 Python 程序。

Mu 非常简单易懂。 这是它的界面：

<div class="row">
  <img src="/img/en/tutorials/mu_ui.png" alt="The first bug" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

虽然上面的图片中似乎有很多内容，但如果我们将其分解一下，你会发现 Mu 很容易学习。

Mu 的最顶端是标题栏（如下图所示）。
这可能在您的计算机上看起来有所不同，但它的功能始终相同：
显示你正在使用的 Mu 版本（如果你需要告诉我们你是否发现了Mu的问题，这很有用）以及 您正在编辑的当前 Python 文件的名称。

就是这样！

<div class="row">
  <img src="/img/en/tutorials/mu_window_top.png" alt="The Mu title bar" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

接下来是按钮栏：

<div class="row">
  <img src="/img/en/tutorials/mu_buttons.png" alt="The Mu button bar" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

如您所见，它包含着一堆圆形按钮。
如果将鼠标悬停在按钮上（不是点上去啊！），你会看到一个提示信息，其中包含有关按钮功能的更多信息。
试试吧！

大多数的按钮是不变，但有些按钮会根据您当时正在做的事情而改变。

这些按钮按分组组合在一起:

* 模式（Mode）：这个按钮非常重要，它是单独的一组。
  单击它可以更改 Mu 的当前模式。每种模式都有不同的功能，具体取决于你想要实现的目标。
  如果您想了解有关模式的更多信息，这里有一份[关于“模式”的教程](modes)供你接下来参考阅读。

* 文件系统：这组中的“新建”、“加载”和“保存”按钮，可以让你与电脑硬盘上存储的文件进行交互。
  * 新建（New）：创建一个新的空白文件。
  * 加载（Load）：打开文件选择器来选择要加载到 Mu 的文件。
  * 保存（Save）：将文件保存到你的电脑硬盘中。如果文件还没有命名的话，则会需要你填写一下文件名。
  如果文件已经命名，则通常每5秒自动保存一次。

* 代码操作：这组按钮会根据你当前所使用的模式儿改变。
  他们为你所写的代码提供了有趣的交互方式。
  在上面的示例中，“运行(Run)”、“调试(Debug)”、“REPL”和“绘图器(Plotter)”按钮属于这一组。
  每个模式的按钮详细信息会在每个模式单独的教程中详细讲解。

* 显示设置：有时改变 Mu 的外观很重要。
  这里的三个按钮（“放大(Zoom-in)”、“缩小(Zoom-out)”、“主题(Theme)”）
  可以改变可以改变 Mu 的呈现方式，“放大”和“缩小”按钮可让文本变大或变小。
  如果你需要协助阅读代码时会非常有用。
  “主题”按钮可以切换三个不同的显示“主题”：
  * 日间：一个浅色的主题，看起来很轻松。（就是上面示例中所使用的主题）
  * 夜间: 一个深色的主题，可以让你看起来像是好莱坞电影中的程序高手。
  * 高对比度：黑白色的主题，适合那些有特别需求的人的用户界面。

  当你重启编辑器时，Mu 会记得你最后使用的主题。

* 编辑器支持：“检查(Check)”、“帮助(Help)”和“退出(Quit)”按钮为 Mu 提供了一些途径来帮助你使用 Mu。
  * 检查(Check)：分析您的代码并提出改进建议。
  * 帮助(Help)：在你的默认浏览器中打开 Mu 的帮助页面。
  * 退出(Quit)：退出编辑器。如果你还没保存的话，可能会要求你保存文件。

按钮下方是“选项卡”, 显示你已打开的文件, 并突出显示你当前正在处理的文件:

<div class="row">
  <img src="/img/en/tutorials/mu_tabs.png" alt="The tabs in Mu" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

*单击选项卡即可切换你当前要编辑的文件*。

要关闭文件，只需单击文件选项卡中的“X”。你还可以单击并左右拖动选项卡来重新对他们进行排序。

如果要重命名文件, 可以直接*在选项卡中*双击文件名称, 系统将要求您提供新的名字。

在选项卡下面是 Mu 里最大和最重要的部分 —— 文本编辑器:

<div class="row">
  <img src="/img/en/tutorials/mu_editor_widget.png" alt="The text editor in Mu" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

这里会显示当前选定的选项卡中的代码。
当你切换选项卡时，这个区域的代码会随之更改。
如果你单击这个区域并开始输入，你将会看到你所输入的代码会显示在这里。
当你输入代码时，Mu 将即时的更改文本颜色，以帮助你读取代码。
左边一列是行号的显示区域，这些行号信息对 Python 的错误报告会很有用（报错信息一般会包括行号）。

最后, 在底部的是页脚。

<div class="row">
  <img src="/img/en/tutorials/mu_footer.png" alt="The footer in Mu" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

页脚包含三个内容:

* 在左边是 Mu 向你输出信息的区域。
  在示例中，Mu 在说：“诶嘿！检查结果显示，没有问题。”
* 右侧的第一项是当前模式的名称。在示例中，Mu 处于 Python 模式。
* 在最右手边的是一个齿轮图标。如果你点击它, 你会看到一个管理窗口, 在大多数情况下, 你可以安全地忽略它的处在。

## 来自 Mu 的问候！

让我们用 Mu 创建第一个 Python 程序吧。

1. 确保 Mu 处于 Python 3 模式（在页面右下角确认！）。如果不是的话，点击“模式”按钮，双击启用“Python 3”模式。
2. 单击“新建”按钮, 然后在输入内容之前, 单击“保存”按钮, 并为您的文件指定一个名称 (比如：“hello.py”)。
3. 在文本区域中输入以下 Python 代码:
   ```
   print("Hello from Mu!")
   ```
4. 单击“运行”按钮, 程序的输出将显示在文本编辑器和页脚之间的新的 "输出" 区域中。
5. 点击“停止”按钮返回编辑你的代码。

步骤3、4、5如下所示:

<div class="row">
  <img src="/img/en//mu.gif" alt="Hello from Mu!" class="img-responsive center-block img-rounded movie"/>
  <br/>
</div>

恭喜你！你刚刚使用 Mu 编写并运行了第一个 Python 程序。
接下来, 为什么不了解一下 [Mu 中的模式](modes)呢？
