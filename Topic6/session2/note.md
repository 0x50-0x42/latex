# Blocks and columns

## Blocks

* Sometimes we need to display information that is important or that stands out. In that case, we can use one of the following blocks:
```tex
\begin{block}{Title}
	...
\end{block}
```
<p align = "center">
OR
</p>

```tex
\begin{alertblock}{Title}
	...
\end{block}
```
<p align = "center">
OR
</p>

```tex
\begin{example}
	...
\end{example}
```

* The content that needs to be dispayed goes into the respective environments.

<ins>Note</ins>: <em>We donot mention the title in the `example` block.</em>

## Columns

* To organize the content into multiple columns, we typeset using the `columns` environment.

```tex
\begin{columns}
	...
\end{columns}
```
* We denote the size of the column by using the `\column{}` command and mention the size w.r.t to the textwidth.
```tex
\column{X\textwidth}`
```
Here, the size of the colum is `X` times the `\textwidth`.

* If the content of one frame are too large to fit in one frame and the content are not being displayed properly, then we can use the following:
```tex
\begin{frame}[allowframebreaks]{Frame name}
	...
\end{frame}
```
The `allowframebreaks` argument will split the content so that it continues to the next slide. So, in simple words `allowframebreaks` splits the content into multiple slides.

See: [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic6/session2/doc1.tex), [doc2.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic6/session2/doc2.tex), [doc3.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic6/session2/doc3.tex), [doc4.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic6/session2/doc4.tex).

---
