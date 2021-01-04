# Thesis-Slides
毕业论文开题报告与答辩幻灯片模板

如果认为字体太大, 可以讲 `11pt` 改为 `10pt`。

```latex
\documentclass[11pt]{beamer}
```

模板的中英文均为衬线字体

```latex
\usefonttheme{serif}
```

如果幻灯片主题内容全为英文，英文字体为非衬线，只有数学字体为衬线字体是很好的选择，字体主题更改为

```latex
\usefonttheme[onlymath]{serif}
```


Beamer 主题为 Madrid，颜色主题为 rose，可以根据需要修改。

```latex
\usetheme{Madrid}
\usecolortheme{rose}
```

**注意：** 编译请使用 PDFTeXify 或 PDFLaTeX 编译运行，否则部分数学符号显示可能有问题。
