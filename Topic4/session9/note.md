# Figure and sub-figures

## Figure environment

* For positioning the image, captioning it, etc., we use the `figure` environment.
* Syntax:
	* `\begin{figure}[position]`<br>`\includegraphics[...]{...}`<br>`\caption{...}`<br>`\end{figure}`
	* The `position` can be:
		* `h` $\rightarrow$ <em>here</em>.
		* `b` $\rightarrow$ <em>bottom</em>.
		* `t` $\rightarrow$ <em>top</em>.
* To list the figures and their corresponding page numbers, like we listed the list of tables, we use `\listoffigures`.

## Sub-figure

* We can have two or more figures under one single figure itself.
* For this, we need to use the `caption` and `subcaption` packages.
* Syntax:

```tex
\begin{figure}[<position>]
	\begin{subfigure}{<width>}
		\includegraphics{...}
		\caption{...}
	\end{subfigure}
	...
	\caption{...}
\end{figure}
```

See: [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic4/session9/doc1.tex), [doc2.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic4/session9/doc2.tex).

---
