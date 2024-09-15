# Beamer

* Used to create presentation slides.
* Document class: `beamer`.
* Again, as usual, the `\begin{document}...\end{document}` environment is used.
* Each slide in a presentation is known as a frame.
* Inside the `document` environment, we write multiple `frame` environments.
* A frame environment:
```tex
\begin{document}
...
...
	\begin{frame}[t|c|b]{Frame Title}
		...
	\end{frame}
	...
	...
\end{document}
```
The arguments `t`, `c` and `b` denote the alignment of the text on the slide(it's optional). The `Frame Title` denotes the title of the frame(this is also optional).

* We can choose themes and color themes for a slides in our presentations.
* Commands:
	* `\usetheme{...}`
	* `\usecolortheme{...}`
* We also use `\tableofcontents` command to convey the reader what points are to be covered. It's usually written in a slide called <em>outline</em>.
* We write sections before the `\begin{frame}` command.
* The code that we write within the `frame` environment is pure $\LaTeX$, there is no other form of code used. That is we can create tables, insert images and do everything that we could do in the `article`, `book` and `report` documentclasses, the only differences is that now we are working with presentation instead of writing article, book or report.

* We can find various themes and colorthemes in [https://hartwork.org/beamer-theme-matrix/](https://hartwork.org/beamer-theme-matrix/). Here, the names mentioned vertically are the names of the themes and the names mentioned horizontally are the names of the colorthemes.

See: [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic6/doc1.tex).

---
