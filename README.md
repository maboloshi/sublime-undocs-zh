# Sublime Text 非官方中文文档

本项目为 [Sublime Text Unofficial Documentation][undocs-github] 的中文翻译版本，由 Sublime-China 社区发起翻译维护。

> 欢迎任何形式的转载，但请务必注明出处，尊重他人劳动共创开源社区
>
> 转载请注明：本文档由 Sublime China 社区 [sublime-china.com](http://sublime-china.com) 组织翻译

翻译同步 commit 版本: **a571f5b**

## 如何参与贡献

本项目中包含了 `.sublime-project` 文件，预定义了项目配置及对应的编译系统，通过 Sphinx 来编译生成 HTML 文档，请使用 Sublime Text 打开。

### 本地编译(HTML 预览)

安装 [Sphinx][]，注意需 **Python 2.7** 版本，Python 3+ 无法工作

    pip install sphinx

使用 ReadTheDocs 主题

    pip install sphinx_rtd_theme

编译完成后，在浏览器中打开 `build/html/index.html` 查看效果。

[undocs]: http://docs.sublimetext.info/
[undocs-github]: https://github.com/guillermooo/sublime-undocs
[Sphinx]: http://sphinx-doc.org/
