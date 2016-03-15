
## 安装

在vim中写markdown，首先安装语法高亮的插件－－[vim-markdown](https://github.com/plasticboy/vim-markdown)．至于预览，则有很多方式：

1. 使用vim插件－－[vim-instant-markdown](https://github.com/suan/vim-instant-markdown)
此方法可以实现markdown实时预览，不过得首先安装nodejs和npm．详细的安装过程见[vim插件汇总－－Markdown插件](http://blog.csdn.net/u012948976/article/details/48227713)．

2. vim其他插件－－[python-vim-instant-markdown
](https://github.com/isnowfy/python-vim-instant-markdown)

3. 通过＂Markdown.pl＂转换成html在浏览器预览
见博文[ vim与markdown ](http://blog.chinaunix.net/uid-20147410-id-3611957.html)．该方式得手动预览．

4. 使用Pandoc
[利用 Pandoc 预览 VIM 中书写的 Markdown](http://www.jmlog.com/use-pandoc-to-preview-markdown-in-vim/)

5. chrome插件－－Markdown Preview Plus
[vim编辑markdown时实现预览 ](http://howiefh.github.io/2013/05/16/vim-markdown-preview/)

**关于产生文章目录的几种方式**

1. 安装完插件－－[vim-markdown](https://github.com/plasticboy/vim-markdown)后，在vim中直接输入命令`:Toc`即可打开显示目录的窗口。

2. 安装插件－－[tagbar](https://github.com/majutsushi/tagbar)，并参考[markdown配置](https://github.com/majutsushi/tagbar/wiki#markdown)设置即可，注意
>g:tagbar_type_markdown 和 ‘ctagstype’: ‘markdown’ 这两个地方需要和你的 vim 所识别的 markdown 格式匹配。检测自己的 vim 所识别的 markdown 文本的格式的方式是在 vim 中输入 :set filetype? ，所显示的 filetype= 后面的内容如果不是
markdown，则需要用来替换上面两个地方。

    并且`'ctagsbin' : '/path/to/markdown2ctags.py',`中的`/path/to`必须替换成自己的路径。

3. 安装插件－－[VOoM](https://github.com/vim-voom/VOoM)和[VOoM(原VOOF)：vim实现带折叠双栏树状文本管理](https://xbeta.info/vim-voof.htm)。
4. 如果想将markdown转为带目录的html文件并在浏览器中预览，可使用githhub项目－－[i5ting_ztree_toc](https://github.com/i5ting/i5ting_ztree_toc)。


## 参考

［1］[在 vim 中显示 markdown 结构大纲](http://blog.yongli1992.com/2015/08/14/vim-markdown-outline/)
----
[↑ 返回上级](https://github.com/asin929/linux-software/blob/master/Office-Application/Office-Application.md)

[← 返回首页](https://github.com/asin929/linux-software)
