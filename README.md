# TongjiLaTex620- 同济大学LaTex论文模板（620）

**直接给出了windows下所需要的字体（见字体文件夹，右键管理员权限安装）；**

**增加了算法列写宏包；**

**debug了参考文献最后一页页眉显示为附录的问题；**

*这些都是一些极为细小的工作，且本项目理念与marquistj13理念背道而驰。本项目在于节省模板使用者对于LaTex所投入的精力，将精力尽可能放在论文本身的撰写上。而marquistj13认为LaTex模板使用者需要自身对LaTex进行一定的深入了解，以便更加优雅的进行论文撰写。故由于以上原因（贡献甚微+理念相悖），对模板进行了不同的修改和制定。*

## 环境和编译方式

环境：[texlive2018](http://tug.org/texlive/acquire.html)  

文本编辑器：[notepad++](https://notepad-plus-plus.org/) 用于文字撰写  

编译器：texworks.exe(texlive自带的就很好用)

编译选择文件 thesis.tex

编译方式建议选择XeLaTex

参考文献编译方式建议选择 biber

编译顺序为 XeLaTex + biber + XeLaTex+ XeLaTex（带参考文献）

## 文件夹结构

data文件夹里为具体论文的章节（chap）、封面（cover）、附录、致谢等，其中介绍了表格、图片、算法如何在LaTex中撰写。

figures文件夹里为论文所需要的图片。

ref文件夹中为参考文献，参考文献格式为bibtex格式，可以在百度学术，bing学术，谷歌学术原网站生成bibtex的引用格式。

而thesis.tex为需要编译的文件，其把data里的章节和figures里的图片以及ref里的.bib文件整合成一个完整的论文。

如有兴趣可以参见[具体的LaTex写作文献](http://www.latexstudio.net/archives/6058.html)。

如无时间，想将精力集中在论文撰写上，在列写公式时可以百度[LaTex数学符号](https://jingyan.baidu.com/article/4b52d702df537efc5c774bc9.html)等，列写表格、图片、以及算法参见chap01&chap02。

## 神秘bug出现

建议在编译 thesis.tex 的texworks中选择“文件——删除辅助文件”，而后重新 XeLaTex + biber + XeLaTex+ XeLaTex 编译。

如还不能解决，*请看编译器给出的错误信息，然后善用百度、bing、谷歌（条件允许的情况下）予以处理*
