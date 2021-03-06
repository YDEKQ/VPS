## ★★★★★ MacDown .MD神器
## 简介:
* MarkDown :让文档更容易读、写和随意改。  
* HTML     :发布的格式，
* Markdown :书写的格式。
* 纯文本 + 样式, 兼容性极强! 任何文本编辑器,任何平台都能打开!   


## 标题:
分6个等级. 一个#代表一级(最大),6个#代表六级(最小).   #:写在行首才生效的. 

# \#&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;一级标题
## \#\\\\\\#&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;二级标题
### \#\#\#&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;三极标题
#### \#\#\\\\#\#&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;四级标题
##### \#\#\#\#\#&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;五级标题
###### \#\#\#\\#\#\#&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;六级标题  


## 引用:



## 字体:
*斜体*  文字前后加\*号  
**粗体** 文字前后加\**号  
**\*粗斜*** 文字前后加\*\*\*号  



## 制作表格:

marks.

用 | 当单元格的边框

|name|sex|Tel|Age|  
|:—|:—:|:—:|—:|        这行必须要   : 来控制 居中 还是左右对齐.  
|徐健|M|137|?|
|钱伟|F|130|?|



## 代码区块:

行首 加四个空格 
区块内的Markdown 用到的特殊符号: & 、 \< 和 \> 会自动转成 HTML 实体，这样的方式让你非常容易输入  
Markdown 插入范例用的 HTML 原始码，只需要复制贴上，再加上缩进就可以了




## 添加图片:
![图片名字][image-1]  
复制文件地址办法:用 alfred2 安装插件  实现快捷键 ⌘ + P 复制文件路径  
或者 图片拖进终端  会显示文件路径 复制就好了.




## 超级链接:

[我的邮箱][1]  
效果:  [我的邮箱][2]  



## 分割线
三个以上的 \* -   行内不能有其他字符


\\ 反斜杠 + 特殊语法符号:打出符号本身        比如 # \* ,   \\\* 结束

特殊字符: 要打出&  


换行方法: 文件末尾 加两个空格  再按 ↵

  
## 列表符号:
\*  
无序列表 - + \* 后面+空格  
有序列表 数字1234 后面跟 英文.  
4个空格 代表 缩进式的代码段  

多个空格:默认变一个空格 
要打出多个空格: 输入 \\&nbsp;



\@: Markdown

 [简书-Markdown 新手指南]()(http://jianshu.io/p/q81RER)
 [简书-Markdown 简明教程]()(http://www.jianshu.com/p/7bd23251da0a)
  


## 添加图片 比文字链接 前面多一个!号
 
 参考语法 ![Alt text]()(/path/to/img.jpg)
 前面是书本链接 后面是图片的链接地址. 
 图片: [***Jane Eyre**\*]()(http://book.douban.com/subject/1141406/) is not just ***Jane Eyre**\*
 ![]()(http://img3.douban.com/mpic/s1108264.jpg)
 

 
 
## [其他]()(chrome://not-a-link)　 这是一个空链接! 颜色好看 -.-颜色好看
 
 引用 &gt; 后面加空格   
 
 
 要写列表了，就直接 \*\*\* ，分行下来
 
  无序列表 -/+/* 后面加空格(最多加3空格 可以缩进项目列表). -/+/* 要在行的最前面. 
- 1
- 2
- 3
	 
	 
	 
 单行长文字!!　　　　上面下面一行 各自加上三个连续的  中间那行 就显示一个框了.
 
\~
这是一个很长很长很长的一行这是一个很长很长很长的一行这是一个很长很长很长的一行这是一个很长很长很长的一行这是一个很长很长很长的一行这是一个很长很长很长的一行这是一个很长很长很长的一行这是一个很长很长很长的一行这是一个很长很长很长的一行这是一个很长很长很长的一行这是一个很长很长很长的一行这是一个很长很长很长的一行
\~
 
 
删除线\~\~ 文字前后各加两个连续的\~ 
 
 
---
分割线 上下行 各加三个或者三个以上的 - \* \_ 符号建立分割线 符号行内 除了空格 不能有其他任何东西.   
---
 
行内代码 ` #hello *90* ` 用 \` 代码内容 \`就好了
 
 
特殊字符: &lt; 和 &amp;  
&lt; 用于起始标签
&amp; 用于标记html实体 要输入这些字符 需要用 &amp;lt 和 &amp;amp
 
空白行 表示另起一段
 
 
代码区块: 只要简单的缩进4空格 也就是一个tab 就变成代码区块了. 一个代码区块 会持续到没有缩进的那一行为止 或者是文件结尾.
代码区块里面 &amp; &lt; &gt; \* 都不会被当作特殊记号被用掉 而是会正常的显示.
 
 
\---- -- 这个上面是i 标题二级 任何数量= - 都有效.
 
 例子如下，在 Markdown 文件里加上一段 HTML 表格：
 
 
&lt;table&gt;
    &lt;tr&gt;  
        &lt;td&gt;Foo&lt;/td&gt;
  &lt;td&gt;xoo&lt;/td&gt;
    &lt;/tr&gt;
    &lt;tr&gt;  
        &lt;td&gt;Foo&lt;/td&gt;
  &lt;td&gt;xoo&lt;/td&gt;
    &lt;/tr&gt;
 
&lt;/table&gt;
 

教程链接   https://github.com/riku/Markdown-Syntax-CN/blob/master/syntax.md  

特殊字符:   \< 用 &lt;     &用 &amp;   才能正常显示

段落:   上下会有一空行的


[http://maogm.com/blog/markdown-syntax.html#html][6]



[1]:	xujian0219@126.com
[2]:	xujian0219@126.com
[6]:	http://maogm.com/blog/markdown-syntax.html#html

[image-1]:	/Users/v/Desktop/Pic/JB0XRv0.png
