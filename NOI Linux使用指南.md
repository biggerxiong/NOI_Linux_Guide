## NOI Linux 使用指南

### 前言

今年江西省的 CSP 认证第二轮使用的是 `NOI Linux` 系统，这也是我们江西近几年来第一次在复赛中使用这个系统，以往我们都是使用 `windows7` 系统。

说到 `NOI Linux` 系统，参加过 `NOI` 系列比赛的同学肯定不陌生，因为在 `NOI` 比赛中，使用的就是这个系统。而对于第一次参加比赛、或者之前没有参加过 `NOI` 的同学来说，这个系统可能 “听都没听说过”。其实这个新系统和我们平时用的 `windows` 系统并没有多大区别，不要对他有畏惧心理，要勇于尝试新事物。

本文将带你快速上手 `NOI Linux` 这个系统。

### 操作上的区别

`NOI Linux` 系统是基于 `Ubuntu 14.04` 的，它的基本操作和 `Ubuntu` 系统没有什么区别。

但如果你之前没有用过 `Ubuntu` 系统，那么下面的文章对你就是有用的。

在 `NOI Linux` 系统中，每个窗口的 “最大化”、“最小化”、“关闭” 按钮都是在左上角的（`windows` 系统的在右上角“），这就是两个系统在操作上最大的区别了。如下图所示：

![](G:\Desktop\codes\NOIP\NOI Linux的使用\2-文件管理器.png)

我们可以看到，界面和你平时使用的 `windows` 系统非常的相似，甚至让你直接操作，你都能试着去点点点。

所以你完全可以把 `NOI Linux` 系统当成是一个 “换了皮肤的 windows 系统”，大胆地去使用它吧。



###界面布局

![](G:\Desktop\codes\NOIP\NOI Linux的使用\1-1主界面.png)

这是 `NOI Linux` 系统的桌面，可以看到，桌面空荡荡，一点东西也没有。你可能需要用到的东西全在左上角：

![左上角](G:\Desktop\codes\NOIP\NOI Linux的使用\1-2主界面-左上角.png)

“应用程序” 中有你比赛要用的编程软件、常用工具等。

“位置” 中有常用的路径，你可以把它理解成是 `windows` 系统中的 “我的电脑”。

![](G:\Desktop\codes\NOIP\NOI Linux的使用\1-2主界面-应用程序-编程.png)

![](G:\Desktop\codes\NOIP\NOI Linux的使用\1-2主界面-应用程序-附件.png)

在 “应用程序” —— “编程” 这个菜单下（如上图），有很多编程软件供你选择，如果你平时使用 `Dev c++` 作为你的编程软件的话，那么在 `NOI Linux` 上我推荐 `GUIDE` 这个编程软件，它在操作上和 `Dev c++` 是很像的。

![](G:\Desktop\codes\NOIP\NOI Linux的使用\1-2主界面-应用程序-编程-GUIDE.png)

在 “应用程序” —— “附件” 这个菜单下，你也许会用到里面的 “计算器” 和 “文本编辑器”（文本编辑器就是 `windows` 上的记事本），这两个软件的操作和 `windows` 上的差不多，在本文中我们就不过多介绍。

![](G:\Desktop\codes\NOIP\NOI Linux的使用\1-2主界面-应用程序-编程-计算器文本编辑器.png)



### GUIDE 编程软件介绍

我们现在打开 `GUIDE` 这个程序，可以看到他的主界面。

![](G:\Desktop\codes\NOIP\NOI Linux的使用\5-5 GUIDE主界面.png)

常用的按钮在上图中都已经标注出来了。

也许你在疑问：“为什么没有新建文件的按钮？“，其实是有的，只不过在这一节中没有标注出来，在下面的章节中，我会教你如何编写 c++ 代码。

`GUIDE` 的默认字体非常小，所以你 **非常有必要学会如何修改字体大小**。

我们在工具栏中点击编辑 —— 选项，可以打开 `GUIDE` 的设置窗口。

![](G:\Desktop\codes\NOIP\NOI Linux的使用\5-2.png)

![](G:\Desktop\codes\NOIP\NOI Linux的使用\5-3.png)

在其中的 “语法高亮显示” 中，我们可以修改字体、颜色以及大小。

在 ”语法高亮显示” 中，我们要修改 “全部字体” 的大小，所以请点击 **“全部字体”** 。

![](G:\Desktop\codes\NOIP\NOI Linux的使用\5-4.png)

![](G:\Desktop\codes\NOIP\NOI Linux的使用\5-6.png)

选择好你喜欢的字体和字体大小后（字体大小一般18~22就差不多啦），一路点击 “OK” 按钮，就修改好字体大小了。

在 `GUIDE` 中，是没有 “编译运行” 这个选项的（所以你写好代码之后，需要先点击 ”编译“ 按钮，编译成功后，再点击 “运行” 按钮来运行你的程序。

### 考试文件的提取

比赛还未开始时，你会有一个压缩包，压缩包里面装的是你这次比赛的题目。但这个压缩包是有密码的，等考试开始时，你的监考老师会告诉你密码。

![](G:\Desktop\codes\NOIP\NOI Linux的使用\3-1.png)

现在，桌面上有一个压缩包，我们暂且就当他是你比赛的题目，我们可以在这个文件上按右键。

![](G:\Desktop\codes\NOIP\NOI Linux的使用\3-2.png)

点击提取到此处，就会提示你输入解压密码。

![](G:\Desktop\codes\NOIP\NOI Linux的使用\3-3.png)

输入密码后，软件会自动帮你把压缩包里的内容解压到一个文件夹中。

![](G:\Desktop\codes\NOIP\NOI Linux的使用\3-4.png)

![](G:\Desktop\codes\NOIP\NOI Linux的使用\3-5.png)



### 开始做题

我们进入比赛题目的文件夹，在里面新建一个 “空白文档”，将文档的名字修改成 **题目的英文名.cpp** （一定要加上 **.cpp** 的后缀）。

![](G:\Desktop\codes\NOIP\NOI Linux的使用\4-1.png)

![](G:\Desktop\codes\NOIP\NOI Linux的使用\4-2.png)

然后打开 `GUIDE` 这个编程软件。

把 `calc.cpp` 这个文件拖进 `GUIDE` 中，就可以写代码了。

![](G:\Desktop\codes\NOIP\NOI Linux的使用\5-7.png)

代码编写完成后，记得 **先点编译按钮，再点运行按钮** ，也就是先编译，再运行。

![](G:\Desktop\codes\NOIP\NOI Linux的使用\5-8.png)



### 使用自带的工具对比输出文件

本章内容较高级，并不是每位同学都要用到，看不懂也没关系。

点击左上角的 ”应用程序——附件——终端“，可以打开类似于 `windows` 上的命令行工具。

你可能需要用到下面三条命令：

1. `ls` 类似于 `windows` 上的 `dir` 命令，作用是显示当然目录的所有文件名。
2. `cd XXXX` 进入 `XXXX` 文件夹
3. `diff file1.txt file2.txt` 比对 `file1.txt` 和 `file2.txt` 是否相同，类似于 `windows` 上的 `dir` 命令。

相信用法请看视频。



### 结束语

此文档是仓促之中写完的，旨在于向参加 csp 认证的同学科普 `NOI Linux` 的用法，若有编写错误还请向我反馈，十分感谢。

若发现问题，我会第一时间在 github 上修改，如您想关注本文的最新修改，还请访问 github 链接： https://github.com/XiongMr/NOI_Linux_Guide

