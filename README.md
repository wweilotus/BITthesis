# BITthesis
the latex template of BIT thesis for master and doctor
# 编译方式说明
由于文章主体采用了宋体，中文环境推荐使用`XeLatex`编译
> 在Windows系统下，首先采用`XeLatex`编译，在采用`bibtex`编译参考文献，再两次`XeLatex`编译得到`pdf`
由于在Linux系统下，没有宋体和微软字库，推荐安装字库再编译，否者出错

-----------------------------------
# 推荐编译环境加编译器
为力更快的管理自己的文档和不担心编译过程中不出现宏包缺少的现象，推荐使用`TexLive2016+Texstudio`组合

# 目前需要解决的问题
1.标题格式采用了`ctex`中的默认设置，总体上看符合学校要求的格式，但是不是太完美，需要进一步的调整，由于对字体和行间距的理解还没透彻，需要高手来定制
2.部分加粗字体提示字体不能加粗，需要进一步解决
3.封面还不是太完美

## 测试数学公式的显示
$$\int_a^b f(x)$$
