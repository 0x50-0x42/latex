# Multiple `.tex` files

* When a $\LaTeX$ document grows large it is advised to split the content into multiple `.tex` files and then include all of them in the `main.tex` file using the `\include{}` command.
* Example:

Consider the following code for `main.tex`:
```tex
\documentclass{book}
\usepackage{lipsum}

\begin{document}
	\chapter{Initial}
	\lipsum[1-2]
	
	\include{ch01} % ch01 is the name of the .tex file
\end{document}
```
Here, `ch01` is the name of the `.tex` file, which is given below:

```tex
\chapter{Introduction}
\lipsum[1-10]
```
* This was just using one `.tex` file but we can create multiple `.tex` files and include them.