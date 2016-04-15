# wizard_latex_index
在使用texlive和latex-cjk的情况下,目录和书签可能会出现乱码.
在命令行中使用python chinesePdfLaTex.py <[*.tex]>命令//暂时只支持python3
即可编译出中文目录和中文书签的pdf文件


注意!!!
需要在tex文件中使用包
\usepackage[CJKbookmarks=true]{hyperref} 
