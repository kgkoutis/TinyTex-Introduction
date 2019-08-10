# TinyTex-Introduction

Follow the installation instructions [here](https://yihui.name/tinytex/)

Then create an example.tex folder like

```latex
\documentclass{article}
\begin{document} example for a very \tiny{tiny} \normalsize \LaTeX \ document
\end{document}
```

then run 

```bash
sudo tlmgr install latexmk
latexmk -pdf
```

Please follow more instructions [here](https://mg.readthedocs.io/latexmk.html)
