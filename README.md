# 一份圈量子引力笔记

这是关于圈量子引力的一份note，目前还没完全 self-contain，后续有读Thiemann的书的计划，将同时修改补充此note。

## 获取方式

1. 你可以直接下载release；
2. 你可以clone此项目，自己编译一遍。

### 编译 ![](https://www.zhihu.com/equation?tex=\LaTeX) 文件方式

### 命令行

1. 运行 `latexmk -xelatex NotesOnLQG.tex`，或按照 `xelatex-biber-xelatex*2` 的次序编译四次。
2. 可选：运行上一步后再运行 `makeindex NotesOnLQG.nlo -s nomencl.ist -o NotesOnLQG.nls`，然后再用 `xelatex` 编译一次。这一步省略也行，只是不会在开头产生一个符号列表。

### 如果你用VScode

项目里已经提供了`settings.json`，运行recipe `latexmk with xelatex` 和 `makeindex -> xelatex` 即可。
