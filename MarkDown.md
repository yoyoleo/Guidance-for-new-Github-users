### Markdown教程

#### 1 支持 Markdown 的编辑器
##### Windows
推荐[Sublime Text 3](https://www.sublimetext.com/3)，强大优雅的编辑器。
MarkdownPad，一款可以直接预览排版效果的编辑器。

##### Mac
推荐 Ulysess，专注写作的编辑器，功能强大，体验一流。
[Macdown](https://macdown.uranusjr.com/)，可以预览排版效果。

##### Linux
推荐 VIM，编辑器之神。当然，Emacs是神的编辑器。
ReText，也可以预览。

##### Web
推荐简书，有 Markdown 写作/预览模式。
作业部落，功能强大的 Markdown 编辑器。
与其他常用工具配合
在 Firefox 浏览器上，推荐插件 It’s All Text!，可以将网页上的文本框转化为 Markdown 编辑器。
在和 Evernote 配合使用时，推荐使用马克飞象。

##### 扩展阅读
[《好用的 Markdown 编辑器一览》](https://www.williamlong.info/archives/4319.html)
欢迎补充，随时更新。

#### 2 Markdown 语法
现在可以在作业部落的左侧窗口中试试看了。无需注册，直接开始输入文字就好。

要事第一
首先需要注意：在 Markdown 中另起一段时，需要多敲一次回车键，来在段落之间添加一个空行。这是与其他常见文档格式的不同之处。
这是因为，在一些 Markdown 解释器中，会把相邻的两行合并成同一个段落。
例如，当我们这样书写时：
**这是第一段。
这是第二段。**
实际上看到的效果是这样：
这是第一段。这是第二段。
虽然并非所有 Markdown 解释器都会用同样的解释方式，但是为了避免出错，还是多敲一次回车来添加一个空行吧。

标题
Markdown 中，只需要在文本前面加上“#”，就会被认为是加了一个标题。同理，你还可以增加二级、三级、四级、五级标题和六级标题，只需要增加“#” 即可。例如：
一级标题
二级标题
三级标题
四级标题
五级标题
六级标题
列表
实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
当你要罗列一些内容时，列表是很有用的工具。为了说明哪些条目属于这个列表，我们需要引入“项目标记”。

列表项目标记通常放在段落开头，后面要跟着一个空格。列表的各个条目之间可以不留空行。

若列表中的条目没有特定顺序时，可以使用 无序列表。加号“+”或减号“-”都可以作为列表标记，后面要跟一个空格。例如：

Red
Green
Blue
或者

- Red
- Green
- Blue

实际显示的效果都是这样的（在不同的环境下显示效果可能会有差异）：

Red
Green
Blue
若想在段落前加上数字序号，就需要用到有序列表了。使用数字、一个英文句号和一个空格即可。例如：

1 Red

2 Green

3 Blue

实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：

1 Red
2 Green
3 Blue
删除线
~~ 哈哈哈哈哈哈哈~~

实际效果：

哈哈哈哈哈哈哈哈

图片
Markdown 中可以插入图片，只需要感叹号、方括号和圆括号即可。例如：
! [Alt text] (/path/to/img.jpg)
一个英文感叹号 “!” 后紧跟方括号，里面可以写这张图片的说明；再紧跟一对圆括号，里面写这张图片的网址。例如：
! [吃面条] (http://upload-images.jianshu.io/upload_images/19107-4a17a25a90d42a5e.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：
吃面条

有些 Markdown 编辑器也支持拖拽插入图片，这就简单多了。例如简书 或者 Ulysses 就有这种功能。

链接
在文档中插入链接的语法和插入图片的语法很像，只是少了最前面的英文感叹号"!"。
在方括号写下链接文字，圆括号写下网址即可。例如：
[好中文的样子] (http://www.jianshu.com/p/d409bb2b5d6c)
实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：
好中文的样子

引用
可以使用">" 标记来引用其他人的言论、书籍或报纸的内容。只需要在段落的第一行最前面加上 > 即可：

”每位作者都应该学习 Markdown。”

实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：

”每位作者都应该学习 Markdown。”

引用可以嵌套，只要根据层次的不同，加上不同数量的 > 即可：

这是第一级引用。

这是第二级引用。

现在回到第一级引用。

实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：

这是第一级引用。

这是第二级引用。
现在回到第一级引用。

在引用的区域内，也可以使用其他的 Markdown 语法，包括标题、列表等：

>## 这是一个标题。

>1. 这是第一行列表项。
>2. 这是第二行列表项。

实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：

这是一个标题。
这是第一行列表项。
这是第二行列表项。
强调
在Markdown中，可以使用 “*”和 “_” (下划线)来表示加粗和倾斜。

在需要斜体的文本左右各加一个“*”或“_” ：

*吹吹那热风，听听那冷雨，看哪，好中文的样子。*

_吹吹那热风，听听那冷雨，看哪，好中文的样子。_

实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：

吹吹那热风，听听那冷雨，看哪，好中文的样子。

吹吹那热风，听听那冷雨，看哪，好中文的样子。

在需要加粗的文本左右各加两个“*”或“_” ：

**吹吹那热风，听听那冷雨，看哪，好中文的样子。**

__吹吹那热风，听听那冷雨，看哪，好中文的样子。__

实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：

吹吹那热风，听听那冷雨，看哪，好中文的样子。

吹吹那热风，听听那冷雨，看哪，好中文的样子。

分割线
在 Markdown 中，可以用分隔线来将内容分成不同区域。

只需要连续三个减号"-"或者三个“*”即可。例如：

— 或 ***

实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：

如何在简书用markdown插入代码
第一：要在简书设置上该为markdown；
第二：是新建文章，记住，若是之前的文章不会生效的；
第三：把输入法切换为英文，之后点击esc键下的那个键，最终结果为

Paste_Image.png

代码引用
需要引用代码时，如果引用的语句只有一段，不分行，可以用 ` 将语句包起来。
如果引用的语句为多行，可以将```置于这段代码的首行和末行。
代码引用的案例截图：

Paste_Image.png

表格
相关代码：

Paste_Image.png

显示效果：（第二行左边加冒号显示效果靠左，右边加冒号显示效果靠右，两边都加冒号显示效果居中，注意：冒号一定要和虚线紧挨着。）

Tables	Are	Cool
col 3 is	right-aligned	$1600
col 2 is	centered	$12
zebra stripes	are neat	$1
相关代码：

Paste_Image.png
显示效果：

dog	bird	cat
foo	foo	foo
bar	bar	bar
baz	baz	baz
显示链接中带括号的图片

代码如下:

![][1]
[1]: http://latex.codecogs.com/gif.latex?\prod%20\(n_{i}\)+1
1
2
3 常见问题
Q： 我该去哪里下载 Markdown 软件？

A： Markdown 是一种标准而非软件，任何支持 Markdown 语法的编辑器都可以使用，无论是何种操作系统、哪类设备。请看“3 支持 Markdown 的编辑器”，或者问问 Google。

Q：在简书里怎么切换 Markdown？为什么切换了没有反应？

A：建议使用 Chrome 或 Firefox 浏览器。在简书中，点击右上角个人头像-设置，在“常用编辑器”中选中markdown，然后保存。注意一行小字：“切换后对新建文章生效”。然后点击右上角”写新文章“，再点击工具栏右侧倒数第三个按钮“切换到预览模式”，屏幕应该会分成左右两个区域。在左侧区域输入内容、添加标记，右侧就会实时显示 Markdown 效果了。

Q： 为什么我按说明写了标记，但是没法正常显示？
A： 很可能是你误把中文标点当成了英文标点。在 Markdown 中使用标点符号作为标记时，要使用英文标点符号。没关系，人们总会犯这种小错误。

Q： 为什么我写了正确的标记，但是在编辑窗口中看不到任何效果？
A： 许多 Markdown 编辑器都不是所见即所得的——“所见即所得”是指你对格式的修改会马上反映在屏幕上，就像 Word 那样。如果你的编辑器没有没有实时预览功能，就不会看到格式的变化。Macdown和简书 都支持实时预览，你需要先打开这个功能，才能看到这些格式标记的效果。

Q： Markdown 可以排版表格吗？
A： 可以，如果你熟练的话，排版表格也会很快。表格的语法请见“Markdown 语法说明（简体中文版）”。

Q： Markdown可以排版数学公式吗？
A： 可以。只要有相应的扩展，Markdown 可以支持LaTeX 公式、甚至画流程图和甘特图。

Q： 标题效果和加粗有区别吗？
A： 看似没有，其实还是有的。这涉及到如何解释 Markdown 标记的问题，一般和 CSS 有关。更多信息，请看“4 扩展阅读”部分。

Q： 加图片时，无 IT 背景人士一般会采用从桌面拖拽的方式。Markdown 支持拖拽吗？
A： 拖拽图片插入文档或上传到网站，不是 Markdown 语法本身的内容。不过有些网站和 Markdown 编辑器支持拖拽方式，例如 Ulysess 和 简书 。

Q： Markdown 正文可以调整字号吗？
A： 同样和解释 Markdown 标记的方式有关。更多信息，请看“4 扩展阅读”部分。

Q： Markdown 段落开头不能空两格，看着很难受啊。有办法解决吗？
A： 办法嘛……若是在自己机器上的 Markdown 编辑器中，也许你可以修改 CSS。若是在 简书 之类网站上，可能只能手工在每段开始前手工添加五个“&n bsp;”了。记得，是“&nb sp;”，字符和字母之间都没有空格。最后的分号也是有必要的哦~

4 扩展阅读
更多关于 Markdown 语法或工具的内容，可以参考：
Markdown 语法说明（简体中文版）
献给写作者的 Markdown 新手指南
Markdown 是定义文章逻辑结构，而非定义样式的。一般来说，Markdown 最终呈现出的样式，是由对应的层叠样式表（CSS）所定义的。如果想要自己调整出想要的样式，可以从 CSS 开始。这里有一份 CSS 教程：《CSS 入门教程》

Markdown 新手手册（本文）

更多内容，请关注专题《GC4WPS03E05-番外》

5 补充
左右两边加~ ：~ 123456 ~
实际效果：123456
左右两边加 ·（Tab上边的键）： **·**123456 ·
实际效果：123456
父类的无序标号
- 横线前面空两个空格，后面空一个空格，出现小白圈
