

# 淮北师范大学模板使用说明

[TOC]


## 使用的前提

为了使用该模板，需要安装一个`TeX`的发行版本。可以选择`Texlive`或者`Miktex`,他们都是跨平台的。而`Texlive`打包了比较多的宏包，较为庞大，`Miktex`则是临时下载没有的宏包。这里我推荐使用`Miktex`。但是对于Mac，推荐使用`MacTeX`，它是为Mac定制的发行版本，应该比较合适。特别提醒`CTeX`套装无法运行该模板。你可以选择卸载`CTeX`套装，安装我推荐的发行版本，或者不使用该模板。关于编译方式需选择`XeLaTeX`,否则无法正常编译该模板,如果熟悉`latexmk`的可以用它来编译，这更好。

如果你不想在本地安装`TeX`的发行版本，其实可以使用 [Overleaf](https://www.overleaf.com) 在线编译平台，同样请使用`XeLaTeX`编译。由于这个网址服务器在国外，加载速度比较慢，请耐心等待~~或者搭梯子~~。
## 模板使用说明

为了正确使用该模板，请按照提示安装好可使用的TeX发行版本。因为论文内容比较多，因此采取了分文件的方式来构成该文档。主文档`HBNUthesis.tex`的位置位于根下，正确编译后所得的pdf文件就在这里。`Figure`文件夹是存放图片的文件夹，该文件夹已经加入图片文件夹的位置，插入图片是无需多加路径，直接用文件名即可。关于`Body`文件夹只需要把里面的`Information.tex`正确填入即可。而你需要编辑的仅有`Body`文件夹下的文件。

当你需要毕业论文的打印时。可以打开`Cover and reconsitution`文件夹，封面的制作程序已经做好了，使用它应该能的到你想要的`a3`封面，你可以自己再做调整。关于整篇论文的打印，可以在运行主文档`HBNUthesis.tex`时选择用用`openright`选项，如果它生成的pdf仍然不满意，可以用`Reconsitution.tex`自己拼接和加空白页，这样总能完成工作。


## 几点说明

- 该模板应该能够在`Mac`和`Windows`系统下运行。`windows`用户无需更改配置，但是`Mac`用户请打开`Settings/Seetting.tex`文件下，搜索`Windows`,按找到位置处注释的提示操作，即可运行。在`Mac`上使用首先需要解决字体的问题，我的方法是将`windows`中的字体文件安装到`Mac`上，如果有其他可以完成的方法自然更好。Linux目前我还没有测试，欢迎广大校友测试提出`issue`。

- 该模板是在厦门大学博士学位论文模板的基础上修改得到的，因为本科论文与博士学位论文的要求差别比较的，所以定制了该模板。

-  在使用该模板之前，请把原始编译出来的文档读一下，对于你的使用是很有帮助的。

- 由于本人水平有限，因此该模板写的并不好，但是应该勉强能够满足本科毕业论文的要求。必然还仍然可能有许多错误的地方，希望各位使用者如果能发现错误之处能够及时提出。可以给我发邮件或者直接在 `github`上面提`issue`。欢迎大家的参与，共同完善母校的模板。

- 由于本人是一名理科生，对文科的同学毕业论文的额外需求可能了解不多。虽说文科生用这个模板的可能性比较小，如果有人用，有额外的需求也可以提出。

<<<<<<< HEAD:HBNUthesis/Readme.md
##注意
参考文献引用需要进行四次顺序编译，分别是

xelatex HBNUthesis.tex

bibtex HBNUthesis.aux

xelatex HBNUthesis.tex

xelatex HBNUthesis.tex

才能正确编译出参考文献的引用
=======
## 注意：

bibtex编译次序依次是
xetex HBNUthesis.tex 
bibtex HBNUthesis.aux 
xetex HBNUthesis.tex 
xetex HBNUthesis.tex
方能得到正确参考文献的引用


>>>>>>> 57bb4417fce216fdd9b7b586ea806d2499c2fb74:Readme.md


## 联系方式

邮箱： [tdhypocrites@163.com](mailto:tdhypocrites@163.com)

该项目github项目的地址是 : [Link](https://github.com/TDHypocrites/HBNU-Undergraduate-thesis-template)
