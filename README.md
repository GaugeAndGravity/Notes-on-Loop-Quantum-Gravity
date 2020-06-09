# 一份圈量子引力笔记

编译 $\LaTeX$ 文件方式：

1. 运行 `latexmk -xelatex NotesOnLQG.tex`，或按照 `xelatex-biber-xelatex*2` 的次序编译四次。
2. 运行 `makeindex NotesOnLQG.nlo -s nomencl.ist -o NotesOnLQG.nls`，然后再用 `xelatex` 编译一次。跳过也行，就是没有符号列表。
